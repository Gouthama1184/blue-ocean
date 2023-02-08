pipeline {
  agent any
  stages {
    stage('installing apache') {
      steps {
        sh '''pipeline {
    agent any

    stages {
        stage(\'Install apache2\') {
            steps {
                sh (\'sudo apt-get update && sudo apt install -y apache2\')
            }
        }
    }
}'''
        }
      }

    }
  }