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
            echo 'Ver parÃ¡metros de seguridad'
          }
        }

        stage('PENTEST INTERNO') {
          steps {
            echo 'Pentest interno es también conocido como la evaluación interna. Pentest interno es una evaluación crítica, sistemática y detallada de redes informáticas. Generalmente un pentest interno es realizado por los profesionales de empresa de pentesting, '
          }
        }

        stage('PENTEST EXTERNO ') {
          steps {
            echo 'Pentest externo es también conocido como evaluación externa. Pentest externo es una evaluación crítica, sistemática y detallada de redes informáticas desde afuera. Generalmente un pentest externo es realizado por los profesionales de empresa de pentesting, utilizando técnicas establecidas con el objeto de emitir informes y formular sugerencias para el mejoramiento de la seguridad. '
          }
        }

      }
    }

  }
}