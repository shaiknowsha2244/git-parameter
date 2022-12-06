pipeline {
    agent any
     options {
    skipDefaultCheckout true
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('notify') {
            steps {
                slackSend channel: '#slack-for-integration', message: 'it is done', tokenCredentialId: 'slack'
            }
        }
    }
}
