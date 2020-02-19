pipeline {
    agent any 
    stages {
        stage('Make') { 
            steps {
               sh label: '', script: 'make all'
            }
        }
        stage('Exec') { 
            steps {
                sh label: '', script: './a.out'
            }
        }
    }
    post {
    always {
                chuckNorris()
        }
    }
}
