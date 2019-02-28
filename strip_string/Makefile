NULL_STRING:=
space_var:= $(NULL_STRING) $(NULL_STRING)
.PHONY: all
$(warning space_var is [$(space_var)])
$(warning strip space_var is [$(strip $(space_var))])
#ifneq ($(space_var), "")
#all: $(space_var) 
#else
#all:;@echo "nothing to do"
#endif

#ifneq ($(strip $(space_var)),)
#ifneq "$(strip $(space_var))" ""
#ifneq ($(space_var),)
ifneq "$(space_var)" ""
all: 
	@echo "something"
else
all:
	@echo "nothing to do"
endif
