pipeline {
    agent any
    stages {
        stage ('git checkout')
            steps{
                git branch: 'main', URL: 'https://github.com/shikhadevops/boxfuse-sample-java-war-hello.git'
        }
        stage ('Build')
            steps {
                sh 'mvn install clean package' 
             }
    }

}
    