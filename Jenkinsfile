pipeline {
    agent {
executeDocker(dockerImage: 'node:6-alpine', dockerWorkspace: '/home/node') {
    sh 'npm install && npm test'
}
    }
    stages {
        stage('Build') { 
            executeDocker(dockerImage: 'node:6-alpine', dockerWorkspace: '/home/node') {
    sh 'npm install && npm test'
}
        }
    }
}