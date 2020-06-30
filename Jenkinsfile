@Library('jen-pipe-lib@testbranch') _

pipeline
{
	agent any 
	stages
	{
		stage('from jenkinsfile')
		{
			steps
			{
				echo "from jenkinsfile..."
				echo "Hi..."
			}
		}
		stage('from lib')
		{
			steps
			{
				fromLibarary()
				fromTestBranch()
        			echo "HELLLLOOO"
			}
		}
	
	}
}
