pipeline {
    agent {
        label; 'maven'
    }

    parameters {
        booleanParam name: 'CLEAN_BEFORE', description: 'Executa o passo de "clean" antes do build'
    }

    stages {

        stage('Clean') {
            when { 
                expression { return params.CLEAN_BEFORE }     
            }

            steps {
                echo 'Stage Clean'
            }

        }

        stage('Compile') {
            steps {
                echo 'Stage Compile'
            }
        }

         stage('Compile') {
            steps {
                echo 'Stage Compile'
            }
        }
    }
}