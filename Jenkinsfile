pipeline {
    agent any
    tools {
        nodejs 'NodeJS_23_10' // Refers to the NodeJS installation configured earlier
    }
    stages {
        stage('Prepare') {
            steps {
                sh 'node -v' // Displays Node.js version to confirm installation
            }
        }
        stage('Build') {
            steps {
                sh 'npm -v' // Simulates build by showing npm version
            }
        }
        stage('Test') {
            steps {
                echo "JENKINS_URL: ${env.JENKINS_URL}" // Displays the JENKINS_URL environment variable
            }
        }
    }
}
