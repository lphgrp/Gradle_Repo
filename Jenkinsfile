pipeline {
	agent any
	stages {
		stage ("-Build_Project-") {
			steps {
				bat "gradlew build"
			}
		}
		stage ("-Run_Project-") {
			steps {
				bat "gradlew run"
			}
		}
		
	}
}