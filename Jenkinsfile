node {
    stage('Checkout') {
        checkout scm
    }
    stage('Build') {
        sh 'npm install'
    }
    stage('Test') {
        sh './jenkins/scripts/test.sh'
    }
}