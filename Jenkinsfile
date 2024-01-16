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
    }
    // This is a comment to test if commenting out this line resolves the issue
    // 如果注释掉这一行是否解决了问题
}
