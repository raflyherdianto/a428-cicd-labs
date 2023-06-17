Node {
    stage('Build') {
        git '/home/a428-cicd-labs'
        sh 'npm install'
    }
    stage('Test') {
        sh './jenkins/scripts/test.sh'
    }
}