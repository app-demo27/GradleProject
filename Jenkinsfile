pipeline{
     tools {
         gradle 'Gradlev6'
     }
     stages{
          stage('checkout') {
           // checkout the code
               git https://github.com/app-demo27/GradleProject.git

        }
        stage('Build') {
           // Run the maven build
                bat 'gradle clean build'

        }
        stage('Results') {
             bat 'echo "Looks like it went well!"'
        }
     }
}
