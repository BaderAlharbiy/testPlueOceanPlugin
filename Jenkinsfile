pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Build Completed'
      }
    }

    stage('Test 2') {
      parallel {
        stage('Test Stgaes') {
          steps {
            echo 'Running test 2'
          }
        }

        stage('test 1') {
          steps {
            echo 'Running test 1'
          }
        }

      }
    }

    stage('Deloy ') {
      steps {
        echo 'Deplyemet stges'
      }
    }

  }
}