pipeline {
    agent any

    tools {
        maven "mvn"
    }
    stages {
        step {
            script {
                dockerImage = docker.build('demojenkinsmvc:latest')
            }
        }
    }
}