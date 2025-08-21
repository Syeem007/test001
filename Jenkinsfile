pipeline {
  agent any
  parameters {
    string(name: 'BRANCH', defaultValue: 'main', description: 'Which Git branch to build?')
  }
  stages {
    stage('Build') {
      steps {
        sh "echo Building branch: ${params.BRANCH}"
      }
    }
  }
}
