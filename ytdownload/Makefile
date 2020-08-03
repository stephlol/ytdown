export TARGET = iphone:13.5:10.0
export ARCHS = arm64
INSTALL_TARGET_PROCESSES = ytd
include $(THEOS)/makefiles/common.mk
XCODEPROJ_NAME = ytdownload
ytdownload_XCODE_SCHEME = ytdownload
ytdownload_CODESIGN_FLAGS = -Sentitlements.xml 
include $(THEOS_MAKE_PATH)/xcodeproj.mk