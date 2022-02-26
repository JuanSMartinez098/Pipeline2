pipeline {
  agent any
  stages {
    stage('Paso1') {
      parallel {
        stage('Paso1') {
          steps {
            build 'PROYECTO-MAVEN-PRODUCCION'
          }
        }

        stage('Paso1.1') {
          steps {
            build 'JOB1.1'
          }
        }

      }
    }

    stage('Paso2') {
      steps {
        build 'JOB3.1'
      }
    }

  }
}