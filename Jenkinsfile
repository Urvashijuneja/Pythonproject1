pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git 'https://github.com/Urvashijuneja/pythonProject1'
            }
        }
         stage('Test') {
            steps {
                echo 'This is to test repo'
            }
        }
         stage('Build') {
            steps {
                echo 'This is to build repo'
            }
        }
    }
}