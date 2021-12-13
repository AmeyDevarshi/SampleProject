pipeline {
    agent any
    tools{
        maven 'Maven'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn hello'
            }    
    }
        stage('build1') {
            steps {
                echo "World"
            }    
    }
        
}
}
