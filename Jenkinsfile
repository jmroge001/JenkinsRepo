pipeline {
  agent any
  stages {
    stage('pull') {
      steps {
        echo 'Pull me'
      }
    }
    stage('test') {
      steps {
        timeout(time: 23)
      }
    }
    stage('package') {
      steps {
        echo 'i\'m a package'
      }
    }
    stage('deploy') {
      steps {
        timestamps()
      }
    }
  }
}