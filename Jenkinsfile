pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                script {
                    git branch: 'main', url: 'https://github.com/TONGTONGSHI45/demo-counter-app.git'
                }
            }
        }

        stage('UNIT testing') {
            steps {
                script {
                    sh 'mvn test'
                }
            }
        }
    }
}

