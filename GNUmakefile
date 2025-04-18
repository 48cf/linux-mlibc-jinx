jinx:
	curl -Lo $@ https://codeberg.org/mintsuki/jinx/raw/branch/trunk/jinx
	chmod +x $@

distro-base: jinx
	./jinx build base
