pipeline {
    agent any
    stages{
        stage('clone'){
            steps{
                sh 'echo "clone"'
            }
        }
        stage('test'){
            steps{
                sh 'echo "test"'
                sh 'uname -r'
            }
        }
        stage('createfile'){
            steps{
                sh 'touch text-$BUILD_ID'
            }
        }
    }
}