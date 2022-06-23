pipeline {
    agent any
    stages {
        stage('exercise 1') {
            steps {
                grep -o -i devops example.txt | wc -l
            }
        }
        stage('exercise 2') {
            steps {
                sed -i.bak 's/devops/hello_world/g' example.txt
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
