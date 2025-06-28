pipeline {
   agent {
       label 'docker-agent-alpine'
   }

   stages {
      stage('Hello') {
         steps {
                sh 'java -version'
                echo "Get working directory"
                sh 'pwd'
                echo "running through POOL SCM"
         }
      }
   }
}
