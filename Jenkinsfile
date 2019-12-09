pipeline {
    agent any

    stages {
        stage("Test") {
            steps {
                rtDownload(serverId: 'artifactory-test', specPath: 'spec-dl.json')
            }
        }

    }
}