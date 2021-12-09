pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat "rmdir  /s /q SampleProject"
                bat "git clone https://github.com/AmeyDevarshi/SampleProject.git"
            }    
    }
        
}
