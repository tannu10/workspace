pipeline{
    agent any
    environment{
	staging_server=54.196.240.97
    }
    stages{
	stage('Deploy to Remote)
	    steps{
		sh 'scp${WORKSPACE}/* root@$(staging_server)://var/www/html/
	    }
    }
}
