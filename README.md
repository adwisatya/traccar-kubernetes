# How to deploy traccar in kubernetes
1. Change variabel {host},{port},{username}, and {password} in configmap.yml
2. Change image source in deployment.yml
3. Apply modified config using:
	- kubectl apply -f configmap.yml
	- kubectl apply -f deployment.yml
	- kubectl apply -f service.yml
	
Watch detailed video in: https://www.youtube.com/watch?v=TsphS1eZAwE