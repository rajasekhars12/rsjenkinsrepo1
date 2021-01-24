node {
    
     stage('git clone') {
     git 'https://github.com/rajasekhars12/repo.git' 
   }
   stage('clean') {
      sh 'mvn clean'
   }
   stage('validate') {
      sh 'mvn validate'
   }
   stage('compile') {
      sh 'mvn compile'
   }
   stage('package') {
      sh 'mvn package'
   }
   stage('deploy') {
      sh 'mvn deploy'
   }
   }
	


