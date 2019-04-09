init:
	helm init --client-only

build: clean init
	helm dependency build .
	helm lint .

lint:
	helm dependency build .
	helm lint .

clean: 
	rm -rf charts
	rm -rf requirements.lock
