pipeline {
    agent any
    
    stages {
        stage('Deploy') {
            steps {
                sh "scp -r ${WORKSPACE}/* root@http:example1.000.pe:/htdocs/"
            }
        }
    }
}
