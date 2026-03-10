pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        git url: 'https://github.com/Mayur-2403/lab-internal.git',
            branch: 'main'
      }
    }
    stage('Run Python') {
      steps {
        sh 'python3 script.py'
      }
    }
  }
}
