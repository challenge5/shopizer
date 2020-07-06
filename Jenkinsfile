pipeline {
    agent {label 'ShopizerBuild'}
    stages {
        stage('source') {
            steps {
                git 'https://github.com/challenge5/shopizer.git'
            }
        }
        stage('Build') {
            steps {
                sh './mvnw clean install'
            }
        }
    }
}
