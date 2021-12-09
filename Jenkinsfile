pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                javac hello.java
            }    
    }
        stage('build next'){
            steps {
                javac reply.java
            }
        }
}
