pipeline {
    agent none

    stages {
        stage('cloning docker file') {
            steps {
                sh 'git clone https://github.com/vn-venkatesh/2nd-project/Dockerfile'
            }
        }
        
        stage('cloning docker file') {
            steps {
                sh 'docker build -d .'
            }
        }    
    }
}
