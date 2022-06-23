pipeline {
    agent any
    stages {
        stage('exercise 1') {
            steps {
               sh '''
                . ./exercise1.sh
               sh '''
            }
        }
        stage('exercise 2') {
            steps {
               sh ''' 
                . ./exercise2.sh
               sh ''' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
