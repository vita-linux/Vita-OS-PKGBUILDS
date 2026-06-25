# ON JUNE (06/24/2026)
  CC [M]  drivers/iio/buffer/kfifo_buf.o
  CC [M]  drivers/fpga/dfl-pci.o
  CC [M]  drivers/gnss/sirf.o
  CC [M]  drivers/iio/accel/mma7455_core.o
In file included from ./include/trace/bpf_probe.h:131,
                 from ./include/trace/define_trace.h:134,
                 from drivers/infiniband/hw/hfi1/trace_dbg.h:118,
                 from drivers/infiniband/hw/hfi1/trace.h:15,
                 from drivers/infiniband/hw/hfi1/trace.c:6:
./drivers/infiniband/hw/hfi1/./trace_dbg.h:60:16: fatal error: error writing to /tmp/ccHvNwIR.s: Success
   60 |         struct va_format vaf = {                                        \
      |                ^~~~~~~~~
drivers/infiniband/hw/hfi1/trace.c:532:1: note: in expansion of macro ‘__hfi1_trace_fn’
  532 | __hfi1_trace_fn(IOCTL);
      | ^~~~~~~~~~~~~~~
      
      
compilation terminated.
make[6]: *** [scripts/Makefile.build:289: drivers/infiniband/hw/hfi1/trace.o] Error 1
make[5]: *** [scripts/Makefile.build:548: drivers/infiniband/hw/hfi1] Error 2
make[4]: *** [scripts/Makefile.build:548: drivers/infiniband/hw] Error 2
make[3]: *** [scripts/Makefile.build:548: drivers/infiniband] Error 2
make[3]: *** Waiting for unfinished jobs....
  AR      drivers/net/built-in.a
  CC [M]  drivers/net/netdevsim/bpf.o
  CC [M]  drivers/iio/adc/ad799x.o
