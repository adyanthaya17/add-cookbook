pipeline {
    agent {label 'chef-server'}
    stages {
        stage('Initialize chef') {
            steps {
                sh 'cd /home/oss/chef-repo'
            }
        }
        stage('Build') {
            steps {
                sh 'knife node run_list set ucp1 recipe[ntp]'
            }
        }
    }
}
