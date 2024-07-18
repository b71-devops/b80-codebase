pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Pull-Codebase') {
            steps {
                git branch: 'main', url: 'https://github.com/b71-devops/b80-codebase.git'
            }
        }
    }
}