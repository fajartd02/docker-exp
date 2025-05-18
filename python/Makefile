stage1:
	docker build -t fajar-app:stage1 . -f Dockerfile.stage1

stage2:
	docker build -t fajar-app:stage2 . -f Dockerfile.stage2

stage3:
	docker build -t fajar-app:stage3 . -f Dockerfile.stage3

stage4:
	docker build -t fajar-app:stage4 . -f Dockerfile.stage4

stage5:
	docker build -t fajar-app:stage5 . -f Dockerfile.stage5

run1:
	docker run -d -p 8000:8000 fajar-app:stage1

run2:
	docker run -d -p 8000:8000 fajar-app:stage2

run3:
	docker run -d -p 8000:8000 fajar-app:stage3

run4:
	docker run -d -p 8000:8000 fajar-app:stage4

run5:
	docker run -d -p 8000:8000 fajar-app:stage5

hit:
	curl http://localhost:8000

images:
	docker images | grep fajar-app