.PHONY: image

APP := node-suchen

VERSION ?= "latest"

image:
	docker build -t quay.io/containerbootcamp/$(APP):$(VERSION) .
	docker push quay.io/containerbootcamp/$(APP):$(VERSION)