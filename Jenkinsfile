
pipeline {
    agent any

    stages {
        stage('Checkout GIT SSSSSSSSS') {
            steps {
                echo 'Pulling...'
                git branch: 'main',
                    url: 'https://github.com/Eya-Nakkaii/Jenkins-DevOps.git'
            }
        }

        stage('Maven Check') {
            steps {
                echo 'Checking Maven...'
                sh 'mvn -version'
            }
        }
    }
}
