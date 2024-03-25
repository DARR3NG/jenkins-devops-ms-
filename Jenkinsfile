//SCRIPTED
/*node {
	
		echo "Build"
	
	
		echo "Test"
	
	
		echo "Integration Test"
	
}*/

//DECLARATIVE
pipeline{
	agent{
		label "node"
	}

	stages{
		stage("Build"){
			steps{
				echo "Build"
			}
		}

		stage("Test"){
			steps{
				echo "Test"

			}
		}

		stage("Integration Test"){
			steps{
				echo "Integration Test"

			}

		}
	}
	
}
