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

      }
    }

  }
}