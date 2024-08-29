pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
        ansiblePlaybook credentialsId: 'New_ssh_key', inventory: 'hosts', playbook: 'nginx_install.yaml', vaultTmpPath: ''
        }
      }
  }
}
