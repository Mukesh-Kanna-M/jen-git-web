pipeline {
    agent any 

    stages {
        stage('Clone') {
            steps {
                git branch: 'main' , url: 'https://github.com/Mukesh-Kanna-M/jenkins-webhook-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }
}
