pipeline {
    agent {
        label 'MAVEN'
    }
    stages{
        stage ('git'){
            git 'https://github.com/sudhaaws9/spring-petclinic.git'
        }
        stage('Build'){
            sh 'mvn clean package'
        }
        
    }
}