pipeline {
    agent { docker { image 'nginx:fromDockerfile' } }
    stages {
        stage('build') {
            steps {
                docker 'start fromDockerfile'
            }
        }
    }
}
