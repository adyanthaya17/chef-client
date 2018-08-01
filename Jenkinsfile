pipeline {
    agent {label 'ucp1'}
    stages {
        stage('Run') {
            steps {
                sh 'sudo chef-client'
            }
        }
    }
}
