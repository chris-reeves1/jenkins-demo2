pipeline{
    agent any
    stages{
        stage('Make directory'){
            sh "mkdir ~/jenkins-test"
        }
        stage("make a file"){
            sh "touch ~/jenkins-test/file1.txt"
        }
    }
}
