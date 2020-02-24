pipeline {
   agent any
   stages {
      stage('Mail') {
         steps {
            mail bcc: '', body: 'Test OK', cc: '', from: '', replyTo: '', subject: 'Test', to: 'bharathcy@gmail.com'
         }
      }
      stage('Build') {
		steps {
			sh label: '', script: '''pip3 install flask
			python3 app.py'''         }
      }

   }
}
