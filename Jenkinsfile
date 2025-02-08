pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/yourusername/hello-world-jenkins.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying Hello World..."'
                sh 'cp index.html /var/www/html/index.html' // Modify as needed
            }
        }
    }
}

