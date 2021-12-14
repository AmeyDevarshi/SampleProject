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
                 bat 'javac first_pipeline11\\hello.java'
            }    
        }
    }
    post {
    always {
        cleanWs()
        }
    }
}


