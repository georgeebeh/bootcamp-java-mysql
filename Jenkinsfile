pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out repo'
                git branch: 'feature/app', url: 'https://github.com/georgeebeh/bootcamp-java-mysql.git'
            }
        }
    }
}