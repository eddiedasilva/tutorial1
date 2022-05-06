pipeline {
    agent { docker { image 'foodtrucks-web' } }
    stages {
        stage('build') {
            steps {
                sh 'setup-docker.sh'
            }
        }
    }
}
