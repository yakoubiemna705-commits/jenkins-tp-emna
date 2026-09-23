pipeline {
    agent any

    stages {
        stage('Checkout GIT') {
            steps {
                  echo 'Code déjà récupéré automatiquement par Jenkins - test poll SCM'
            }
        }

        stage('Afficher la date') {
            steps {
                sh 'date'
            }
        }
    }
}
