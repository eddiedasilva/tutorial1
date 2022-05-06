pipeline {
    agent { docker { image 'foodtrucks-web' } }
    stages {
        stage('initialize') {
          steps {
                sh 'export PATH = $PATH:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin'
            }
        stage('build') {
          steps {
                sh 'bash ./FoodTrucks/setup-docker.sh'
            }
        }
      }
   }
}
