node {
  stage('d') {
    sshagent (credentials: ['git-hub-ssh-key']) {
      sh '/bin/bash bash.sh'
    }
  }
}
