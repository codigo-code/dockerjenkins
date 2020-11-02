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
      parallel {
        stage('Fin') {
          steps {
            echo 'finitoooloca'
          }
        }

        stage('Guardando....') {
          steps {
            sh 'writeFile file: "tiburcio", text: "pedoooooo"'
          }
        }

      }
    }

  }
  environment {
    DEMO = '1'
    CARLOTO = 'Chorrita'
  }
}