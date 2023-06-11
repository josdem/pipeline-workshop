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
          sh 'export customer.email="contact@josdem.io"
        }
      }
      stage('storing value') {
        steps {
          sh 'echo $customer.emai
        }
      }
   }
}
