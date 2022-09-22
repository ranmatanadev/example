pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/ranmatanadev/example.git'
                sh "ls -ltr"
            }
        }
    }
}
