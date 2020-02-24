pipeline {
   agent any
   stages {
      stage('Build') {
		steps {
			sh label: '', script: '''pip3 install flask
			python3 app.py'''         }
      }

   }
}
