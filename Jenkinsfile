@Library('jen-pipe-lib@master') _
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
