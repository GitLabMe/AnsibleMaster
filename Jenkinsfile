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
      parallel {
        stage('command') {
          steps {
            sh 'ls -al'
          }
        }

        stage('readme') {
          steps {
            echo 'now jenkins'
          }
        }

        stage('directory') {
          steps {
            sh 'mkdir playbook'
          }
        }

      }
    }

    stage('built') {
      steps {
        sh 'touch myfile'
      }
    }

  }
}