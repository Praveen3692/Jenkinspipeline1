pipeline {
    agent any{
    statges {
     stage("Pull Code"){
         steps {
               echo "Pulling code from Github..."
            }
         }
     stage("Build") {
           steps {
                 echo "Building Packegs from code..."
            }
          }
   Stage("Test") {
          steps {
                 echo "Testing Package"
          }
         }
   Stage("deploy")
         steps {
                echo "deploying Application..."
                }
         }
    }
 }
