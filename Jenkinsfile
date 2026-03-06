pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/girmedivya040-collab/webproject.git'
            }
        }

        stage('Deploy Website') {
            steps {
                bat 'xcopy /E /I /Y * C:\\xampp\\htdocs\\shoppro'
            }
        }

    }
}