pipeline {
  agent any
  stages {
    stage('BuildLab4') {
      parallel {
        stage('BuildLab4') {
          steps {
            echo 'Lab 4 Pipeline'
          }
        }

        stage('Create Web Page') {
          steps {
            echo 'Mensaje'
          }
        }

        stage('create css') {
          steps {
            echo 'crear css'
          }
        }

        stage('crear los repositorios') {
          steps {
            echo 'crear reporte'
          }
        }

      }
    }

    stage('Pruebas') {
      parallel {
        stage('Pruebas') {
          steps {
            echo 'Mostrar pruebas'
          }
        }

        stage('Pruebas del responsive') {
          steps {
            echo 'testear el responsive'
          }
        }

        stage('Pruebas de rendimiento') {
          steps {
            echo 'pruebas de rendimiento'
          }
        }

      }
    }

    stage('Seguridad') {
      parallel {
        stage('Seguridad') {
          steps {
            echo 'Ver parÃƒÂ¡metros de seguridad'
          }
        }

        stage('PENTEST INTERNO') {
          steps {
            echo 'Pentest interno es tambiÃ©n conocido como la evaluaciÃ³n interna. Pentest interno es una evaluaciÃ³n crÃ­tica, sistemÃ¡tica y detallada de redes informÃ¡ticas. Generalmente un pentest interno es realizado por los profesionales de empresa de pentesting, '
          }
        }

        stage('PENTEST EXTERNO ') {
          steps {
            echo 'Pentest externo es tambiÃ©n conocido como evaluaciÃ³n externa. Pentest externo es una evaluaciÃ³n crÃ­tica, sistemÃ¡tica y detallada de redes informÃ¡ticas desde afuera. Generalmente un pentest externo es realizado por los profesionales de empresa de pentesting, utilizando tÃ©cnicas establecidas con el objeto de emitir informes y formular sugerencias para el mejoramiento de la seguridad. '
          }
        }

      }
    }

    stage(' puesta en escena') {
      parallel {
        stage(' puesta en escena') {
          steps {
            echo 'puesta en escena'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Poner la aplicación en un host'
          }
        }

        stage('gestion del dominio') {
          steps {
            echo 'gestión del dominio'
          }
        }

      }
    }

    stage('Producci�n') {
      steps {
        echo 'Producci�n'
      }
    }

  }
}