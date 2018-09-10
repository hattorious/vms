SHELL ?= /bin/bash

default:

start: generate-ignition
	@vagrant up

generate-ignition:
	ct --platform=vagrant-virtualbox < config.yml > ignition/config.ign

.PHONY: default start generate-ignition
