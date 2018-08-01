pipeline {
    agent {label 'chef-server'}
    stages {
        stage('Run') {
            steps {
                sh '/home/oss/run-client.sh'
            }
        }
    }
}
