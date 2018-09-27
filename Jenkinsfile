/*timestamps {

node () {

	stage ('first') {
 	 echo "First"
	}
	stage ('second') {
 		echo "Second"	
	}
	stage ('test')
	{
		load 'C:\\Users\\vaishal\\Desktop\\test\\Jenkinsfile1'
	}
}
}*/
pipeline {
    agent any
    stages {
        stage('First') {
            steps {
                echo "Hi First"
            }
        }
	stage('Second') {
            steps {
                echo "Hi Second"
		load 'C:\\Users\\vaishal\\Desktop\\test\\abc.groovy'
            }
        }
    }
}
