pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Finished'
      }
    }

    stage('Tests') {
      parallel {
        stage('Test1') {
          steps {
            echo 'test1 completed'
          }
        }

        stage('Test2') {
          steps {
            echo 'Test 2 completed'
          }
        }

        stage('Test3') {
          steps {
            echo 'Test 3 completed'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy completed'
      }
    }

  }
}