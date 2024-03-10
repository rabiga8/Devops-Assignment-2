pipeline {
  agent any
  stages {
    stage('Create new file') {
      steps {
        writeFile(file: 'status.txt', text: 'Hey it worked!')
      }
    }

  }
}