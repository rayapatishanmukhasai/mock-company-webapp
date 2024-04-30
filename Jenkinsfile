pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */

   agent any
       stages {
           stage('Build') {
               steps {
                   // Add build steps here, such as compiling code
                   echo 'Building...'
                   bat './gradlew assemble'
               }
           }
           stage('Test') {
               steps {
                   // Add test steps here, such as running unit tests
                   echo 'Testing...'
                   bat './gradlew test'
               }
           }
           stage('Deploy') {
               steps {
                   // Add deployment steps here, such as deploying to a server
                   echo 'Deploying...'
               }
           }
       }
}
