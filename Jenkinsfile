pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building '
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test'
          }
        }

        stage('test para') {
          steps {
            echo 'test para'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}