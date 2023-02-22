pipeline {
  agent any
  stages {
    stage('patchingcode') {
      steps {
        echo 'this is myself'
        git(url: 'https://github.com/gitme1992/AnsibleMaster', branch: 'jean12')
      }
    }

    stage('command') {
      steps {
        sh 'la -al'
      }
    }

  }
}