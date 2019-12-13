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
            echo 'Ver parÃƒÆ’Ã‚Â¡metros de seguridad'
          }
        }

        stage('PENTEST INTERNO') {
          steps {
            echo 'Pentest interno es tambiÃƒÂ©n conocido como la evaluaciÃƒÂ³n interna. Pentest interno es una evaluaciÃƒÂ³n crÃƒÂ­tica, sistemÃƒÂ¡tica y detallada de redes informÃƒÂ¡ticas. Generalmente un pentest interno es realizado por los profesionales de empresa de pentesting, '
          }
        }

        stage('PENTEST EXTERNO ') {
          steps {
            echo 'Pentest externo es tambiÃƒÂ©n conocido como evaluaciÃƒÂ³n externa. Pentest externo es una evaluaciÃƒÂ³n crÃƒÂ­tica, sistemÃƒÂ¡tica y detallada de redes informÃƒÂ¡ticas desde afuera. Generalmente un pentest externo es realizado por los profesionales de empresa de pentesting, utilizando tÃƒÂ©cnicas establecidas con el objeto de emitir informes y formular sugerencias para el mejoramiento de la seguridad. '
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

      }
    }

    stage('Produccion') {
      steps {
        echo 'Producción'
      }
    }

  }
}