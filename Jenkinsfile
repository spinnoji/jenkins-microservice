pepeline{

agent {docker {image 'maven:3.6.3'}} 
stages{
	stage('Build') {
		steps{
       sh 'mvn --version'
         echo "build"
                     }}


 	
	 stage('Test') {
                steps{
      echo "Test"
        }}


 stage('Iintegraton test') {
                steps{
       echo "Integration test"
                     }
}
}
}
