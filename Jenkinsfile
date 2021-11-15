node {
  stage('d') {
    sshagent (credentials: ['git-hub-ssh-key']) {
      sh './bash.sh'
    }
  }
}