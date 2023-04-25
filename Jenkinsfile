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
                  cat /etc/*release*
                  ps a
                  route
                  ifconfig
                '''
            }
        }
    }
}
