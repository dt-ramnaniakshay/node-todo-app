//jenkins pipeline
pipeline {
    agent any
    stages{
        stage('clone code'){
            steps{
                checkout scm
            }
        }
        stage('installing  required dependecies'){
            steps{
                sh "npm install"
            }
        }
    }
}