pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                sh '''
                  hostname
                  id
                  pwd
                  env
                  ps aux
                  route
                  ifconfig
                '''
            }
        }
    }
}
