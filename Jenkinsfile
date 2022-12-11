node {
    
   git branch: 'main', credentialsId: 'b86d813a-1014-466b-a2c6-13397b08500a', url: 'https://github.com/rithvikpreethireddy/arifaproject.git'
    }
	stage('java version') {
	      
           sh 'java -version'
    }
	stage('maven version') {
	       
          sh 'mvn --version'
    }
	stage('maven validate ') {
	       
          sh 'mvn validate'
    }
	
	stage('maven compile') {
	       
          sh 'mvn compile'
    }
	stage('maven test') {
	       
          sh 'mvn test'
    }
	stage('maven package') {
	       
          sh 'mvn package'
    }
        stage('maven deploy') {
		       
          sh 'mvn deploy'
    }
}


