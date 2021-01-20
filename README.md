# jenkins
pipeline {

agent any

stages {
stage("build")
{
steps{
echo "Buliding"
}
}
stage("test")
{
step{
echi "testing"

}
}
stage("deploy"){
step{
echo "deploy"
}
}
}
