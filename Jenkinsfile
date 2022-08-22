pipeline {
    agent any

    stages {
        stage('git clone version1 branch') {
            steps {
                git 'https://github.com/Urvashijuneja/pythonProject1'
            }
        }
         stage('Test version1 branch') {
            steps {
                echo 'This is to test repo'
            }
        }
         stage('Build version1 branch') {
            steps {
                echo 'This is to build repo'
            }
        }
    }
}