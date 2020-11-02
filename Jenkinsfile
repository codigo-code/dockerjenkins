pipeline {
  agent any
  stages {
    stage('Compilando') {
      parallel {
        stage('Compilando') {
          steps {
            echo 'Muestro $DEMO'
          }
        }

        stage('Vieja Zorra') {
          steps {
            echo '$CARLOTO'
          }
        }

      }
    }

    stage('Fin') {
      steps {
        echo 'finitoooloca'
      }
    }

  }
  environment {
    DEMO = '1'
    CARLOTO = 'Chorrita'
  }
}