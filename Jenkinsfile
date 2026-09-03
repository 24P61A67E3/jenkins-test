pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build started'
            }
        }

        stage('Run Python') {
            steps {
                bat '"C:\\Users\\Dell\\AppData\\Local\\Python\\bin\\python.exe" test.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing completed'
            }
        }
    }
}
