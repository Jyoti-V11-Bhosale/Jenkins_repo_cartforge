pipeline {
    agent any
    tools {
        nodejs 'npm'
    }
    environment {
        Name = "Jyoti"
    }

    stages {
        stage('clone') {
            steps {
                echo 'Hello World'
                git branch: 'main', url: 'https://github.com/Jyoti-V11-Bhosale/Jenkins_repo_cartforge.git'
            }
        }
         stage('build') {
            steps {
                echo 'Hello World'
                sh 'npm i'
            }
        }
         stage('deplyo') {
            steps {
                echo 'Hello World'
                sh 'npm run build '
            }
        }
    }
}
