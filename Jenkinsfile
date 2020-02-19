pipeline {
    agent any 
    stages {
        stage('Make') { 
            steps {
                make all
            }
        }
        stage('Exec') { 
            steps {
                ./a.out
            }
        }
    }
}
