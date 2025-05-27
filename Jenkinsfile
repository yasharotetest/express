pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/expressjs/express.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Build') {
            steps {
                bat 'npm install'
            }
        }


    }
}
