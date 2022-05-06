pipeline {
    agent { docker { image 'foodtrucks-web' } }
    stages {
        stage('build') {
            steps {
                sh 'FoodTrucks/setup-docker.sh'
            }
        }
    }
}
