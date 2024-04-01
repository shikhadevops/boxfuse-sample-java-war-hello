pipeline {
    agent any
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
