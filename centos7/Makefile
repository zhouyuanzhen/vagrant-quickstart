help:
	@echo "*********************************************"
	@echo "      Help for this Makefile project"
	@echo "\nRun:"
	@echo "\tmake up_vb | up_vmware | down | clean\n"
	@echo "                                  to start ;)"
	@echo "*********************************************"

up_vb:
	@vagrant up --provider=virtualbox

up_vmware:
	@vagrant up --provider=vmware_desktop

down:
	@vagrant halt

clean:
	@vagrant destroy -f
