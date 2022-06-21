pipeline {

    agent any
    stages {

            stage('Building Docker Image') {
                steps {
                    sh "npm install"
                    sh "docker build . -t node-web-app"
                }
            }

        }
    }
