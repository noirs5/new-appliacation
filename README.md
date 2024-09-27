pipeline {
	agent any 
    	stages {
        	stage("build") {
            	steps {
                	echo 'building the appliacation...'
                }
            }
            stage("test") {
            	steps {
                	echo 'testing the appliacation...'
                }
           }
           stage("deploy") {
           		steps { 
                	echo 'deploying the appliacation...'
                }
           }
 	}          
}
