pipeline {
  agent {
  docker {
    image 'nagendra1991/my-centos'
    label 'docker-agent'
    registryCredentialsId 'dockerhub'
    registryUrl 'https://hub.docker.com/'
  }
}
   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
   }
}
