
pipeline {
    agent any

    stages {

        stage('Install') {
            steps {
                dir('frontend') {
                    bat 'npm install'
                }
            }
        }

        stage('Build') {
            steps {
                dir('frontend') {
                    bat 'npm run build'
                }
            }
        }
    }
}



