sound_DATA = beep.wav
sounddir = $(datadir)/sounds/freedesktop/stereo

UPDATE_SOUND_CACHE = touch -m $(datadir)/sounds/freedesktop || :

install-data-hook:
	mv $(DESTDIR)$(datadir)/sounds/freedesktop/stereo/beep.wav $(DESTDIR)$(datadir)/sounds/freedesktop/stereo/hexchat_beep.wav
	$(UPDATE_SOUND_CACHE);

uninstall-hook:
	$(UPDATE_SOUND_CACHE);
