install:
	test -e ~/bin/ctf-bash || ln -s $$(readlink -f ctf-bash) ~/bin/ctf-bash
	docker build -t my-ctf-tools .

rebuild:
	docker build --no-cache -t my-ctf-tools .
