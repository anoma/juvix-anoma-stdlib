all: test

.PHONY: test
test:
	od -An -N2 -t u2 /dev/urandom | xargs | juvix eval Main.juvix
