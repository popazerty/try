installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = TuxboxPlugins CutListEditor PicturePlayer MediaScanner MediaPlayer SocketMMI DVDBurn \
	IniMyTube IniSHOUTcast IniLastFM IniZapHistoryBrowser AccuWeather IniGmailReader FileCommander \
	IniEcasa IniWebcamViewer RemoteIPTVClient

if !ENABLE_SH
SUBDIRS += IniHbbTV IniAirPlayer 
endif

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

install_PYTHON = __init__.py
