pipeline {
	agent any

  environment {
		VERSION = '1.0.0'
	}

	stages {
		stage('Deploy') {
			steps {
        // wget o curl
				bat 'copy C:\\Users\\virtual\\.m2\\repository\\bootcamp\\jenkins\\war-example\\' + env.VERSION + '\\war-example-' + env.VERSION + '.war C:\\Users\\virtual\\ambientes\\tomcat1\\apache-tomcat-9.0.96\\webapps\\ROOT.war'
			}
		}
	}
}
