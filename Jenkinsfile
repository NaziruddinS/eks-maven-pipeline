pipeline {  

    agent any
        
    tools{
        maven "maven_399"
    }
    stages {
        stage('Clone') {
            steps {
               git 'https://github.com/vinothkumarselvaarasan/maven-web-app.git'
            }
        }
        stage('Build') {
            steps {
               sh 'mvn clean package'
            }
        }
    }
}
