pipeline {
	agent any
	stages {
		stage ("--Clean Project---") {
			steps {
				bat "gradlew build"
			}
		}
		stage ("--Create WarFile---") {
			steps {
				bat "gradlew run"
			}
		}
		
	}
}