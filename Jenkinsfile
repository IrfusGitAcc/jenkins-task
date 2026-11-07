
pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'develop',
                    url: 'https://github.com/IrfusGitAcc/jenkins-task.git'

                echo 'Git repository cloned successfully'
                sh 'pwd'
                sh 'ls -la'
            }
        }
    }
}

