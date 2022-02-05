pipeline {
  agent any
  stages {
    stage('git_import') {
      steps {
        git(url: 'https://github.com/anuj6244/test.git', branch: 'main')
      }
    }

    stage('build') {
      steps {
        withAnt()
      }
    }

  }
}