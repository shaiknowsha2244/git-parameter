pipeline {
    agent any
    parameters {
    gitParameter branchFilter: 'origin/(.*)', defaultValue: 'master', name: 'BRANCH_NAME', type: 'PT_BRANCH'
  }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
