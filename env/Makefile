init:
	helm init --client-only
	helm repo add jenkins-x http://chartmuseum.jenkins-x.io
	helm repo add bitnami https://charts.bitnami.com/bitnami
	helm repo add stable https://kubernetes-charts.storage.googleapis.com
	

build: clean init
	helm dependency build .
	helm lint .

lint:
	helm dependency build .
	helm lint .

clean: 
	rm -rf charts
	rm -rf requirements.lock
