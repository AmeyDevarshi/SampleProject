pipeline {
    agent any
    tools{
        maven 'Maven'
    }
    stages {
        stage('build') {
            steps {
                echo "Hello"
            }    
        }
        stage('build1') {
            steps {
                script {
                    javac "first_pipeline11\\hello.java"
                }
            }    
        }
    }
}
