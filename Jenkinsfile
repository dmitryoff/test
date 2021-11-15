node {
  stage('d') {
    sshagent (credentials: ['ssh1']) {
      sh '/var/lib/jenkins/bash.sh'
    }
  }
}