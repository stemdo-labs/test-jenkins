pipeline {
    agent {
        kubernetes {
           inheritFrom 'CLAUDIA'
        }
    }
 
    stages {
        stage('Inicio') {
            steps {
                echo 'Iniciando la pipeline...'
                sh """
                pwd
                ls
                """
            }
        }
        stage('Preparación') {
            steps {
                echo 'Preparando los recursos...'
            }
        }
        stage('Pruebas') {
            steps {
                echo 'Ejecutando pruebas...'
            }
        }
        stage('Finalización') {
            steps {
                echo 'Pipeline completada exitosamente.'
            }
        }
    }
}

 
