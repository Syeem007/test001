pipeline {
  agent any
  parameters {
    string(name: ${params.BRANCH_NAME}, defaultValue: ${params.BRANCH_NAME}, description: 'Which Git branch to build?')
  }
  stages {
    stage('Build') {
      steps {
        sh "echo Building branch: ${params.BRANCH_NAME}"
      }
    }
  }
}

