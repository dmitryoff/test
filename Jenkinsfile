node {
  stage('d') {
    sshagent (credentials: ['git-hub-ssh-key']) {
      sh '/var/lib/jenkins/bash.sh'
    }
  }
}