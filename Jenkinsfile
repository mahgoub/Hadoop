pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'master', url: 'https://github.com/mahgoub/Hadoop.git'
                echo "Checking out code..."
            }
        }

        stage('Build') {
            steps {
                echo "Building the application..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the application..."
            }
        }
    }
}

