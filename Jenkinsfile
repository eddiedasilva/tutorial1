pipeline {
    agent { docker { image 'foodtrucks-web' } }
    stages {
        stage('build') {
          steps {
                sh 'export PATH = $PATH:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin'
            }
          steps {
                sh 'bash ./FoodTrucks/setup-docker.sh'
            }
        }
      }
}
