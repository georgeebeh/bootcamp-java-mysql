pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out repo'
                sh git clone 'https://github.com/georgeebeh/bootcamp-java-mysql.git'
            }
        }
    }
}