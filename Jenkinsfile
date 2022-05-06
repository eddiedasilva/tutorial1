pipeline {
    agent { docker { run 'zen_kalam' } }
    stages {
        stage('build') {
            steps {
                docker 'start zen_kalam'
            }
        }
    }
}
