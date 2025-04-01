pipeline {
    agent any

    tools {
        nodejs 'node22'
    }

    stages {
        stage('Prepare') {
            steps {
                echo 'Node.js version:'
                sh 'node -v'
            }
        }

        stage('Build') {
            steps {
                echo 'Simulating build...'
                sh 'npm -v'
            }
        }

        stage('Test') {
            steps {
                echo 'Simulating tests...'
                sh 'echo JENKINS_URL=$JENKINS_URL'
            }
        }
    }
}
