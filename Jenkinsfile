pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                sh '''
                  echo $PATH
                  ls -al /desco/group/sysdevops/bin/
                  ls -al /desco/systems/k8s/bin/
                '''
            }
        }
    }
}
