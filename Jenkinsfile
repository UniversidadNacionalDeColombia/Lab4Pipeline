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
            echo 'Ver parámetros de seguridad'
          }
        }

        stage('PENTEST INTERNO') {
          steps {
            echo 'Pentest interno es tambi�n conocido como la evaluaci�n interna. Pentest interno es una evaluaci�n cr�tica, sistem�tica y detallada de redes inform�ticas. Generalmente un pentest interno es realizado por los profesionales de empresa de pentesting, '
          }
        }

        stage('PENTEST EXTERNO ') {
          steps {
            echo 'Pentest externo es tambi�n conocido como evaluaci�n externa. Pentest externo es una evaluaci�n cr�tica, sistem�tica y detallada de redes inform�ticas desde afuera. Generalmente un pentest externo es realizado por los profesionales de empresa de pentesting, utilizando t�cnicas establecidas con el objeto de emitir informes y formular sugerencias para el mejoramiento de la seguridad. '
          }
        }

      }
    }

  }
}