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
                 bat (
                    label: 'JAVAC Tests',
                    script: """
                        java -version
                        javac -version
                        dir
                        javac hello.java
                        if errorlevel 1 exit /b 1
                    """
                    )
            }    
        }
    }
    post {
    always {
        cleanWs()
        }
    }
}


