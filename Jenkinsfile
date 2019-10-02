pipeline {
  agent any
  stages {
    stage('Received an event') {
      steps {
        echo 'I just received a testing completed Event'
      }
    }
  }
  triggers {
    eventTrigger(simpleMatch('testingCompleted'))
  }
}