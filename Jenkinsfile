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
        echo 'i\'m a test'
      }
    }
    stage('package') {
      steps {
        echo 'i\'m a package'
      }
    }
    stage('deploy') {
      steps {
        echo 'i\'m deploying'
      }
    }
  }
}