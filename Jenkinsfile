pipeline {
    agent  {
        label 'ansible'
    }

    stages {
        
        stage('Ansible role molecule test') {
            steps {
                sh 'molecule test'
            }
        }
    }
}