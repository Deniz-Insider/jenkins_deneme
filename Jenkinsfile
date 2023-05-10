pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat set +e 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        bat 'python3 main.py'
      }
    }
  }
}
