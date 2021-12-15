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
                 bat ( build first_job1 )
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


