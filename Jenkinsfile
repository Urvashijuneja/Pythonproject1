 pipeline {
    agent any

    stages {
        stage('git clone master branch') {
            steps {
                git 'https://github.com/Urvashijuneja/pythonProject1'
            }
        }
         stage('Test master branch') {
            steps {
                echo 'This is to test repo'
            }
        }
         stage('Build master branch') {
            steps {
                echo 'This is to build repo'
            }
        }
    }
}