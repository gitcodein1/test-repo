pipeline {
    agent any
    stages {
        stage("TASK1") {
            when {
                changelog '.*test.*'
            }
            steps {
                sh 'cat file1.txt'
            }
        }
    }
}
