export MakeInc_cmd=${SRCROOT}/makedefs/MakeInc.cmd
export MakeInc_def=${SRCROOT}/makedefs/MakeInc.def
export MakeInc_rule=${SRCROOT}/makedefs/MakeInc.rule
export MakeInc_dir=${SRCROOT}/makedefs/MakeInc.dir


include $(MakeInc_cmd)
include $(MakeInc_def)


DATAFILES = \
	cpu_capabilities.h	\
	cpu_number.h	\
	io_map_entries.h \
	lock.h	\
	locks.h	\
	machine_cpuid.h 	\
	machine_routines.h	\
	machine_kpc.h 		\
	pal_routines.h		\
	pal_hibernate.h		\
	simple_lock.h

INSTALL_MI_LCL_LIST = cpu_capabilities.h

INSTALL_MI_DIR = machine

EXPORT_MI_LIST = ${DATAFILES}

EXPORT_MI_DIR = machine

include $(MakeInc_rule)
include $(MakeInc_dir)


