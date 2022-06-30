pipeline {
  agent any
  stages {
    stage('First Stage') {
      steps {
        timestamps() {
          sh '''#!/bin/bash

echo "Shell Script in timestamp"'''
        }

      }
    }

    stage('Second Stage') {
      steps {
        echo 'Preparing tests'
      }
    }

    stage('Third Stage - Processing') {
      steps {
        sleep 10
      }
    }

    stage('Fourth Stage - Final') {
      steps {
        echo 'Done'
      }
    }

  }
}