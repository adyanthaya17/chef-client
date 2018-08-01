pipeline {
    agent {label 'ucp1'}
    stages {
        stage('Run') {
            steps {
                sh 'cd /home/oss && chef-client'
            }
        }
    }
}
