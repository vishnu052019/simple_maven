pipeline {
  agent any
  stages {
    stage('code') {
      steps {
        git(url: 'https://github.com/pavansw/simple_maven.git', branch: 'master', poll: true)
      }
    }

  }
}