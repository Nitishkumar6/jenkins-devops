pipeline {
	agent {docker{image 'maven:3.6.3'}}
	stages{
		stage("build"){
			steps{
				sh 'mvn --version'
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