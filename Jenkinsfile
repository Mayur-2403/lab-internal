pipeline{
  agent any
  stages{
    stage('Clone'){
      stage{
        git url: 'https://github.com/Mayur-2403/lab-internal.git', branch: 'main'
      }
    }
    stage('Run Script'){
      stage{
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
