
pipeline {
    agent any

    stages {
        stage('Verification Git') {
            steps {
                checkout scm
                sh 'ls -la'
                sh 'cat README.md'
            }
        }

        stage('Hello World') {
            steps {
                echo 'Hello World ! Jenkins et GitHub fonctionnent.'
            }
        }
    }
}
