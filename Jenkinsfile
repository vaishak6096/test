pipeline{
agent any
stages{
stage('Test'){
steps{
bat 'python -m unittest discover'}}
stage('Run')
{steps{bat 'python app.py'}}
stage('Deploy'){
steps{echo 'deploying successfully'}}}
post{
success{
echo 'Build, run and deploy successful...'
}
failure{
echo 'Something went wrong'}}}