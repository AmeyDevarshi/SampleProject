 pipeline {
    agent any
    environment {
        PATH = "C:\\Program Files\\apache-maven-3.8.4\\bin:$PATH" 
    }
    tools{
        maven 'Maven'
    }
    stages {
        stage('build') {
            steps {
                mvn clean install 
            }    
        }
        stage('build1') {
            steps { 
                batchFile('javac hello.java')
                batchFile('javac reply.java')
                
                 
                    //label: 'JAVAC Tests',
//                     script: """
//                            java -version
//                            javac -version
//                            dir
//                            javac hello.java
// //                            C:\\windows\\system32\\cmd.exe /k " java -version "
// // 		           C:\\windows\\system32\\cmd.exe /k " javac -version "
// //                            C:\\windows\\system32\\cmd.exe /k " javac hello.java"
//                            if errorlevel 1 exit /b 1
//                     """
                    //)
            }    
        }
    }
    post {
    always {
        cleanWs()
        }
    }
}


