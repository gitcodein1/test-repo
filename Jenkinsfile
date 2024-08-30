pipeline {
    agent any
    stages {
        stage("TASK1") {
            when {
                changelog '.*test.*'
            }
            sh 'cat file1.txt'
        }
    }
}
