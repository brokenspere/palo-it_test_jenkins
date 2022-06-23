pipeline {
    agent any
    stages {
        stage('exercise 1') {
            steps {
               sh '''
                grep -o -i devops example.txt
                wc -l
               sh '''
            }
        }
        stage('exercise 2') {
            steps {
               sh ''' 
                sed -i.bak 's/devops/hello_world/g' example.txt
                cat example.txt
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
