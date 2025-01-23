pipeline {
    agent any
 
    stages {
        stage('Inicio') {
            steps {
                echo 'Iniciando la pipeline...'
                ls
                pwd
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

 
