// @Library('jsl-common@main')

pipeline {
    agent any
    stages {
        stage('Summary') {
            steps {
                script {
                    def h = "TEST" // getCommitHash()
                    echo """
                    COMMIT HASH IS: ${h}, OK? This time?
                    """
                }
            }
        }
    }
}