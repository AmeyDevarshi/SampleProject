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
                 echo "World !" 
            }    
        }
    }
}

post {
    always {
        cleanWs()
    }
}
