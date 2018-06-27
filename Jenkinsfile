pipeline {
  agent any
  stages {
    stage('githubpull') {
      steps {
        git(url: 'git@github.com:sudhanshu7348/sonarqubePlaybook.git', poll: true, branch: 'sonarqubePlaybook')
      }
    }
  }
}