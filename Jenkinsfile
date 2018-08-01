pipeline {
    agent {label 'chef-server'}
    stages {
        stage('Initialize chef') {
            steps {
                sh '/home/oss/chef-client-run.sh'
            }
        }
      
    }
} 
