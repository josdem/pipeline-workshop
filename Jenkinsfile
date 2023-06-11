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
          script{
            System.setProperty("CUSTOMER_EMAIL", "contact@josdem.io")
          }
        }
      }
      stage('reading value') {
        steps {
          sh 'echo $CUSTOMER_EMAIL'
        }
      }
   }
}
