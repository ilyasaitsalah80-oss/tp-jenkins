pipeline {
    agent any

    stages {
        stage('Build & Tests') {
            steps {
                bat 'mvn clean verify checkstyle:checkstyle pmd:pmd pmd:cpd spotbugs:spotbugs'
            }
        }
    }
}