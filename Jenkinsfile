pipeline{
    agent any
    stages{
        stage('Make directory'){
            steps{
            sh "mkdir ~/jenkins-test"
            }
        }
        stage("make a file"){
            steps{
            sh "touch ~/jenkins-test/file1.txt"
            }
        }
    }
}
