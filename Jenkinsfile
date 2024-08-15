pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/SaeidNK/srerepo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add build commands here, like mvn clean install or npm install
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment commands here, like kubectl apply or any deploy scripts
            }
        }
    }
}
