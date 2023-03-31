pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Show files') {
            steps {
                sh 'ls -ltr'
            }
        }
        stage('Run JS file') {
            steps {
                sh 'welcome.js'
            }
        }
    }
}
