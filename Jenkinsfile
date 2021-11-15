node {
  stage('d') {
    sshagent (credentials: ['ssh1']) {
      sh 'ssh -o StrictHostKeyChecking=no -l cloudbees 192.168.100.242 uname -a'
    }
  }
}