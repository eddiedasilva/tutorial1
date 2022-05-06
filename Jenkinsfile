pipeline {
    agent { docker { image 'nginx' } }
    stages {
        stage('build') {
            steps {
                docker 'run --network host -d eddiedasilva/tutoria1'
            }
        }
    }
}
