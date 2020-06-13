pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changelog '.*prod.*'
			}
		
            steps {                
                echo 'Hello World changelog'
            }
        }
    }
}
