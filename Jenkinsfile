pipeline {
  agent any
  stages {
    stage('fetch code') {
      steps {
        git(url: 'https://github.com/chaitanya-03c/FrescoPlay1.git', branch: 'master')
      }
    }

    stage('deploy') {
      steps {
        sh '''javac JenkinsDemo.java
java JenkinsDemo'''
      }
    }

  }
}