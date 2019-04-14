THEOS_DEVICE_IP = xxx.xxx.xxx.xxx
ARCHS = arm64
include /home/DevelopApple/theos/makefiles/common.mk

TWEAK_NAME = CydiaPlus
CydiaPlus_FILES = Tweak.xm
CydiaPlus_FRAMEWORKS = UIKit

include $(THEOS_MAKE_PATH)/tweak.mk

after-install::
	install.exec "killall -9 Cydia"
