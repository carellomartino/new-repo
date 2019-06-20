pipeline {
    agent any

    stages {
        stage('Descargar repo') {
            steps {
                git poll: true, url: 'https://github.com/carellomartino/https://github.com/carellomartino/new-repo.git'
                sh '''
                echo 'Repositorio descargado'
                '''
            }
        }
    }         
}
