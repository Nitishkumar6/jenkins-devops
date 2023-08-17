pipelines{
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
	post{
		always{
			echo "i am always run"
		}
		success{
			echo "i run when you are successfull"
		}
	}
}