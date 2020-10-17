pipeline {
  agent any
  stages {
    stage('Echoing hello') {
      steps {
        echo 'This is a test of the first step'
      }
    }

    stage('Exploring') {
      steps {
        sh '''touch ./test.txt
echo " this is a test" > test.txt'''
      }
    }

  }
}