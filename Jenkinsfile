pipeline {
    agent { docker { image 'foodtrucks-web' } }
    stages {
        stage('build') {
            steps {
                sh 'bash ./FoodTrucks/setup-docker.sh'
            }
        }
    }
}
