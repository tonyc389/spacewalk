# Makefile for spacewalk backend
#

# what is the backend top dir
TOP     = ..

# Specific stuff
SUBDIR		= server

FILES		= __init__
SPACEWALK_FILES		= __init__ \
		  apacheServer apacheHandler apacheAuth apacheRequest \
                  apacheUploadServer \
		  configFilesHandler \
		  rhnAuthPAM rhnCapability rhnChannel \
                  rhnDependency \
                  rhnAction \
                  rhnHandler rhnImport rhnMapping rhnLib rhnPackage \
                  rhnPackageUpload basePackageUpload rhnRepository \
                  rhnSession rhnUser rhnVirtualization taskomatic
SUBDIRS		= rhnSQL rhnServer action \
			  handlers importlib action_extra_data \
			  config_common repomd

include $(TOP)/Makefile.defs
