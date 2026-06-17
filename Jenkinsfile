pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/kaushikd25/myGradleApp2.git'
            }
        }

        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }

        stage('Run') {
            steps {
                sh './gradlew run'
            }
        }
    }
}
