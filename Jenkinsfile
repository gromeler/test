pipeline {
  agent any
  stages {
    stage('Git checkout') {
      parallel {
        stage('Git checkout') {
          steps {
            git 'https://github.com/gromeler/test'
          }
        }

        stage('') {
          steps {
            sleep 1
          }
        }

      }
    }

    stage('Unittest') {
      steps {
        sleep 1
      }
    }

  }
}