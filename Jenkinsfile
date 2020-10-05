node{
     stage('checkout') {
      // checkout the code
           bat 'git init'
           bat 'git pull https://github.com/app-demo27/GradleProject.git'
          
   }
   stage('Build') {
      // Run the maven build
           bat 'gradle clean build'
          
   }
   stage('Results') {
        bat 'echo "Looks like it went well!"'
   }
}
