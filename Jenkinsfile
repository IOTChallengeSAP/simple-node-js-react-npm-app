pipeline {
executeDocker(dockerImage: 'node:6-alpine', dockerWorkspace: '/home/node') {
    sh 'npm install && npm test'
}
}