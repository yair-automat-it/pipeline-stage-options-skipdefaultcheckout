pipeline {
	agent any
	
	stages {
		stage ('Build') {
			agent any
			options { 
				skipDefaultCheckout() 
			}
			steps {
				echo "Hello World"
			}
		}
	}
}
