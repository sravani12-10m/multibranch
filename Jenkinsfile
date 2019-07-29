node('master')

{
stage('Continuous Download-master') 
   
	 {
	
    git 'https://github.com/sunildevops77/maven.git'
    
	}

stage('Continuous build-master') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}

}


