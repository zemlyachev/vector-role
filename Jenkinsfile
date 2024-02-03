pipeline {
    agent  {
        label 'ansible'
    }

    stages {
        
        stage('Get from git') {
            steps {
                git branch: 'main', credentialsId: '1e71d56a-fb25-4a47-8f49-f50b41ba28ad', url: 'git@github.com:zemlyachev/vector-role.git'
            }
        }
        
        stage('Ansible role molecule test') {
            steps {
                sh 'molecule test'
            }
        }
    }
}