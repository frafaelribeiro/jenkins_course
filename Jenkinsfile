//Declarative Pipeline

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script{
                    sh "echo iniciando build ..."
                    sh  '''
                        printf "Building \
                        feito!"
                        '''
                }                
                script{
                    sh "zip ./teste.zip . -r"
                }                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
