node {
    stage('Build') {
        sh './jenkins/scripts/build.sh'
        // sh 'npm install'
    }
    stage('Test') {
        sh './jenkins/scripts/test.sh'
    }
}