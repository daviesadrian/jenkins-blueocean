pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building'
          }
        }

        stage('Pareller Build') {
          steps {
            echo 'Parabell Build'
          }
        }

      }
    }

    stage('Testing') {
      steps {
        echo 'Testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}