pipeline {
    agent any
    tools{
        maven 'Maven'
    }
    stages {
        stage('build') {
            steps {
                echo "Hello"
                sh " javac hello.java"
            }    
    }
        
}
}
