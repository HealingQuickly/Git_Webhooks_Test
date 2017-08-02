#!/usr/bin/env groovy

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat "python --version"
                echo "Under project ${env.JOB_NAME}"
                echo "Running build ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}