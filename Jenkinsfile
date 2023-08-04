pipeline {
    agent any

    stages {
        step {
            script {
                dockerImage = docker.build('demoJenkinsMvc:latest')
            }
        }
    }
}