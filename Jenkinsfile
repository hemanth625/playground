I am in A branch

pipeline {
    agent any 
    stages {
        stage('Development') {
            steps {
                echo 'Developement phase is completed' 
            }
        }
        stage('Build') {
            steps {
                build 'build' 
            }
        }
        stage('Deployment') {
            steps {
                build 'deploy'
            }
        }
        stage('Test') {
            steps {
                build 'test'
            }
        }
    }
}
