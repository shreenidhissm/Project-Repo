pipeline {
  agent any
  stages {
    stage ("SCM checkout") {
      steps {
        echo "cloning the code"
        sh git clone "https://github.com/shreenidhissm/Project-Repo.git"
        }
       }
     stage ("build") {
      steps {
        echo "build the code"
      }
     }
     stage ("push the image") {
       steps {
         echo "push the image to docker-hub"
       }
      }
     stage ("deploy") {
       steps {
         echo "deploy the image"
        }
      }
  }
}
