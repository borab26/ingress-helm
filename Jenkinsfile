pipeline{

	agent any

	stages {
	
		stage ('Kubernetis deploy'){
			steps {
					sh ("/usr/local/bin/kubectl  apply -f ingress.yaml")
				
			}
		}
	}

}
