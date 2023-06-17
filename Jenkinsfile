node {
    stage('Build') {
        git 'https://github.com/raflyherdianto/a428-cicd-labs/tree/react-app'
        sh 'npm install'
    }
    stage('Test') {
        sh './jenkins/scripts/test.sh'
    }
}