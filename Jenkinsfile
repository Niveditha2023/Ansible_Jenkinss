pipeline {
  agent any

  stages {
    stage('Hello') {
      steps {
        sh 'ansible-playbook -i /home/ubuntu/opt/playbooks/hosts /home/ubuntu/opt/playbooks/nginx1-install.yml'
          ansible --version
          ansible-playbook --version
          ansible-galaxy --version
      }
    }
  }
}

