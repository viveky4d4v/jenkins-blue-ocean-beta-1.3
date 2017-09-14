pipeline {
  agent any
  stages {
    stage('Build DEV') {
      steps {
        parallel(
          "Build DEV": {
            echo 'Building..'
            
          },
          "build a": {
            sh 'echo build'
            
          }
        )
      }
    }
    stage('Test DEV') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy DEV') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}