init:
	helm init --client-only
	helm repo add jenkins-x http://chartmuseum.jenkins-x.io
	helm repo add jenkins-x https://charts.bitnami.com/bitnami
	

build: clean init
	helm dependency build .
	helm lint .

lint:
	helm dependency build .
	helm lint .

clean: 
	rm -rf charts
	rm -rf requirements.lock
