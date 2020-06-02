pipeline {
    agent any

    stages {
        stage("Test") {
            steps {
                rtDownload(serverId: 'ecosys', specPath: 'spec-dl.json')
            }
        }

    }
}
