def testvariable = "Some text here"

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -la'
                echo "Valiable is ${testvariable}"
            }
        }
        stage('Test'){
            steps {
                sh 'ls -la'
            }
        }
        stage('Deploy') {
            steps {
                sh 'uptime'
            }
        }
    }
}
