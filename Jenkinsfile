pipeline {
    agent any

    stages {
        stage('Checkout GIT') {
            steps {
                echo 'Récupération du code depuis Git...'
                git branch: 'main', url: 'https://github.com/emna-yacoubi/jenkins-tp-emna.git'
            }
        }

        stage('Afficher la date') {
            steps {
                sh 'date'
            }
        }
    }
}
