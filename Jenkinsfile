pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/TheAcademy/sre-course-teams.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build steps here, like `mvn install` or `npm build`
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your testing steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deployment steps here, like `kubectl apply -f`
            }
        }
    }
}
