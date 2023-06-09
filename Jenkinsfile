pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out repo'
                git branch: 'feature/app', url: 'https://github.com/georgeebeh/bootcamp-java-mysql.git'
            }
        }
        stage('build') {
            steps {
                echo 'building artifact'
                // Set up Java environment (assuming JDK is configured on the agent)
                //tool 'Java'
                
                // Run Gradle build
                sh './gradlew build'
             }
        }
    }
}
