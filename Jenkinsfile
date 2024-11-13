pipeline {
	agent any

  environment {
		VERSION = '0.0.1'
	}

	stages {
		stage('Deploy') {
			steps {
        // wget o curl
				bat 'copy C:\\Users\\virtual\\.m2\\repository\\bootcamp\\jenkins\\war-example\\' + env.VERSION + '\\war-example-' + env.VERSION + '.war C:\\Users\\virtual\\ambientes\\tomcatProd\\apache-tomcat-9.0.96\\webapps\\portal.war'
			}
		}
	}
}
