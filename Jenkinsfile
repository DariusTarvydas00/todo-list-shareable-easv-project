pipeline {
    agent any

    triggers {
        pollSCM('* * * * *')
    }

    tools {
        nodejs "Node"
    }

    stages {
        stage("Build project"){
            steps {
                sh "docker-compose build"
            }
        }
    }
}