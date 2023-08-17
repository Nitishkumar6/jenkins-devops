pipeline {
	agent any
	stages{
		stage("build"){
			steps{
				echo "build"
			}
		}
		stage("test"){
			steps{
				echo "test"
			}
		}
	}

	post {
		always{
			echo "i run always"
		}
		success{
			echo "i run only when you are success"
		}
		failure {
			echo "i run when you failed"
		}
	}
}