#!/usr/bin/env groovy
def userEmail
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
            userEmail = "contact@josdem.io"
          }
        }
      }
      stage('reading value') {
        steps {
          script {
            print userEmail
          }
        }
      }
   }
}
