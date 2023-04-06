pipeline {

    agent any

    stages {
        stage('GIT Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Mridul1703/SME-Project.git'
            }
        }

        stage('UNIT TESTING') {
            steps {
                sh 'mvn test'
            }
        }
    }
}z