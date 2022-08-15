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
                bash "npm i"
                bash "node index.js"
            }
        }
    }
}