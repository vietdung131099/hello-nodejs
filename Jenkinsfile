pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/vietdung131099/hello-nodejs.git'
            }
        }

        stage('Run') {
            steps {
                // sh "npm i"
                // sh "node index.js"
                echo 'Hello world'
            }
        }
    }
}