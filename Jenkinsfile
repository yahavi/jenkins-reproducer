pipeline {
    agent any

    stages {
        stage("Test") {
            steps {
                rtDownload(serverId: 'ECOSYS', specPath: 'spec-dl.json')
            }
        }

    }
}
