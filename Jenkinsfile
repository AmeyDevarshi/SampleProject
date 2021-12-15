 pipeline {
    agent any
    tools{
        maven 'Maven'
    }
    stages {
        stage('build') {
            steps {
                echo "Hello!"
            }    
        }
        stage('build1') {
            steps { 
                dir("C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\first_pipeline11"){
                git "javac -version"
                }
                 
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


