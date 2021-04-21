pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
                    script {
                    for(x in 5..10){
                        println x //0,1,2,3,4,5
                    }
                }
            }
        }
    }
}
