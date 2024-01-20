pipeline {
	agent any
	stages {
		stage('build'){
			steps {
				echo "build script"
				echo "this stage version ${params.version}"
				}
			}
		stage('test'){
			steps {
				echo "test script"
				echo "this environment ${params.env}"
				}
			}
		}
	}
