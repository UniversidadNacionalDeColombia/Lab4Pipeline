pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Lab 4 Pipeline'
      }
    }

    stage('Pruebas') {
      parallel {
        stage('pruebas del responsive') {
          steps {
            echo 'Mostrar pruebas'
          }
        }

        stage('QA') {
          steps {
            echo 'testear el responsive'
          }
        }

        stage('pruebas de rendimiento') {
          steps {
            echo 'pruebas de rendimiento'
          }
        }

        stage('pruebas de navegadores') {
          steps {
            echo 'pruebas de navegadores'
          }
        }

      }
    }

    stage('Seguridad') {
      parallel {
        stage('audit') {
          steps {
            echo 'Ver parÃƒÆ’Ã‚Â¡metros de seguridad'
          }
        }

        stage('pentest interno') {
          steps {
            echo 'Pentest interno es tambiÃƒÂ©n conocido como la evaluaciÃƒÂ³n interna. Pentest interno es una evaluaciÃƒÂ³n crÃƒÂ­tica, sistemÃƒÂ¡tica y detallada de redes informÃƒÂ¡ticas. Generalmente un pentest interno es realizado por los profesionales de empresa de pentesting, '
          }
        }

        stage('pentest externo') {
          steps {
            echo 'Pentest externo es tambiÃƒÂ©n conocido como evaluaciÃƒÂ³n externa. Pentest externo es una evaluaciÃƒÂ³n crÃƒÂ­tica, sistemÃƒÂ¡tica y detallada de redes informÃƒÂ¡ticas desde afuera. Generalmente un pentest externo es realizado por los profesionales de empresa de pentesting, utilizando tÃƒÂ©cnicas establecidas con el objeto de emitir informes y formular sugerencias para el mejoramiento de la seguridad. '
          }
        }

      }
    }

    stage(' Puesta en escena') {
      parallel {
        stage('validacion de la integracion') {
          steps {
            echo 'puesta en escena'
          }
        }

        stage('validaciones del host') {
          steps {
            echo 'Poner la aplicaciÃ³n en un host'
          }
        }

        stage('validaciones del dominio') {
          steps {
            echo 'gestiÃ³n del dominio'
          }
        }

        stage('validaciones de las conexiones de red') {
          steps {
            echo 'validaciones de las conexiones de red'
          }
        }

      }
    }

    stage('Validacion de tokens') {
      steps {
        echo 'Produccionvalidacion Requerimientos'
      }
    }

    stage('Produccion') {
      steps {
        echo 'Produccion'
      }
    }

  }
}