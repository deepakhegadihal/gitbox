node {
   def mvnHome
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/jglick/simple-maven-project-with-tests.git'
    echo 'Preparation.........'
   }
   stage('Build') {
    echo 'Build.........' 
    bat 'Build.bat'
   }
   stage('Results') {
    echo 'Finished.........' 
   }
}
