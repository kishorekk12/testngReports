pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git 'https://github.com/kishorekk12/testngReports.git'
      }
    }

    stage('build') {
      steps {
        bat 'mvn install'
      }
    }

  }
}
