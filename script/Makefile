BRANCH?=main
GROUP?=
sync:
	tsrc sync

checkout:
ifdef GROUP
	tsrc foreach -g $(GROUP) -- git checkout $(BRANCH)
endif
ifndef GROUP
	tsrc foreach -- git checkout $(BRANCH)
endif

pull:
	tsrc foreach -- git checkout $(BRANCH)
	tsrc foreach -- git pull $(BRANCH)