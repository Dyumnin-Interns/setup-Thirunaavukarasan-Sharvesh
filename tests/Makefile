SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/dut.v
VERILOG_SOURCES += $(PWD)/wrappers/xor_test.v
xor:
	$(MAKE) sim MODULE=dut_test TOPLEVEL=xor_test
include $(shell cocotb-config --makefiles)/Makefile.sim
