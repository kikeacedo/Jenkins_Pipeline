pipeline {
  agent any
  stages {
    stage('Get DN') {
      steps {
        echo 'Downloading Delivery'
      }
    }
    stage('Excel Analysis') {
      steps {
        echo 'Analyzing the excel'
      }
    }
    stage('Backup') {
      steps {
        echo 'SVN and PVCS are used for backup'
      }
    }
    stage('Import Repo') {
      steps {
        echo 'Importing Repo'
        fileExists '/Import_Rempo.step'
      }
    }
  }
}