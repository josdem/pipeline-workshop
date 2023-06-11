#!/usr/bin/env groovy
pipeline {
  agent any
    stages {
      stage('printing message') {
        steps {
          echo 'Hello World!'
        }
      }
      stage('storing value') {
        steps {
          sh 'export CUSTOMER_EMAIL="contact@josdem.io"'
        }
      }
      stage('reading value') {
        steps {
          sh 'echo $CUSTOMER_EMAIL'
        }
      }
   }
}
