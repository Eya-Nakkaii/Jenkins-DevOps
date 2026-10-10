
pipeline {
    agent any

    
        stage('Checkout GIT') {
            steps {
                echo 'Pulling...'
                git branch: 'main',
                    url: 'https://github.com/Eya-Nakkaii/Jenkins-DevOps.git'
            }
        }

        stage('Maven Check') {
            steps {
                sh 'mvn -version'
            }
       
    }
}

