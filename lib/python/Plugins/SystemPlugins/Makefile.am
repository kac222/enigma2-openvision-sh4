installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = SoftwareManager PositionerSetup Satfinder \
	SatelliteEquipmentControl Videomode VideoTune Hotplug \
	DefaultServicesScanner DiseqcTester CommonInterfaceAssignment \
	CableScan FastScan OSDPositionSetup OSD3DSetup HdmiCEC VideoClippingSetup \
	VideoEnhancement WirelessLan NetworkWizard SH4OSDAdjustment VFD-Icons

if ENABLE_SPARK
SUBDIRS += SH4BoosterControl
endif

if ENABLE_SPARK7162
SUBDIRS += SparkUnionTunerType SH4BoosterControl
endif

install_PYTHON =	\
	__init__.py
