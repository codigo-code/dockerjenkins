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
            writeFile(file: 'Sorongogo.txt', text: '${CARLOTO}')
            archiveArtifacts 'Sorongogo.txt'
          }
        }

      }
    }

    stage('Finalos') {
      steps {
        sh 'echo ${DANTE}'
      }
    }

  }
  environment {
    DEMO = '1'
    CARLOTO = 'Chorrita'
    DANTE = 'DANTE'
  }
}