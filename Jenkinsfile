pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Step 1: Test message From BlueOcean Pipeline'
      }
    }

    stage('Test') {
      steps {
        junit(allowEmptyResults: true, testResults: 'SampleTestResult')
      }
    }

    stage('Deploy') {
      steps {
        echo 'Test for Deploy'
      }
    }

  }
}