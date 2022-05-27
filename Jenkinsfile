pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
      }
    }
    stage('Test Firefox') {
      parallel {
        stage('Test Firefox') {
          steps {
            sh ''' echo testing'''
          }
        }
        stage('Test Chrome') {
          steps {
            sh ''' echo testing'''
          }
        }
        stage('Test Edge') {
          steps {
            sh '''' echo testing'''
          
        }
      }
    }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }
  }
}

