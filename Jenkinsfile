pipeline {
    agent any
    tools {
        maven 'Maven 3.8.8'
       }
    stages{
        stage('git checkout'){
            steps{
                git 'https://github.com/shikhadevops/boxfuse-sample-java-war-hello.git'
            }
        }
        stage('Build'){
            steps {
                script {
                    sh 'MAVEN clean'
                }
            } 
        }
    }
}    
