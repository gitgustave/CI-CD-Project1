pipeline {
    agent any
    tools {
        jdk 'java'
        maven 'maven_home'
    }
    stages{
        stage("Clean Up WorkSpace"){
            steps {
                cleanWs()
            }
        }
    
    stages{
        stage("Checkout from SCM"){
            steps{
                git branch: 'main', credentialsId: 'gitgustave', url: 'https://github.com/gitgustave/CI-CD-Project1'
            }
        }
    }