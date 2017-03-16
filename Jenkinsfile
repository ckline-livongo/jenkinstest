node {
   stage('Build') {
      // Run the  build
         sh "ls -al"
         sh "touch file.txt"
   }
   stage('Results') {
      // Archive some files
      archive '*.txt'
   }
}
