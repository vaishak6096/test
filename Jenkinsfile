pipeline{
agent any
stages{
stage('Test'){
steps{
bat 'python -m unittest discover'}}
stage('Run')
{steps{bat 'python app.py'}}
stage('Deploy'){
steps{echo 'deploying app'}}}
post{
success{
echo 'build run and deploy successful'
}
failure{
echo 'something went wrong'}}}