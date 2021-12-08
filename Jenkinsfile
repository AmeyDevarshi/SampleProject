pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                javac hello.java
            }
            steps {
                javac reply.java
        }
      
    }
}
