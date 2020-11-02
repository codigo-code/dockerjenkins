pipeline {
  agent any
  stages {
    stage('Compilando') {
      parallel {
        stage('Compilando') {
          steps {
            echo 'Muestro $DEMO'
            sh 'echo " el valor de DEMO ES $DEMO"'
          }
        }

        stage('Vieja Zorra') {
          steps {
            sh 'echo "Carloto es $Carloto"'
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