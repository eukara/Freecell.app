include $(GNUSTEP_MAKEFILES)/common.make

PACKAGE_NAME=Freecell
APP_NAME=Freecell

VERSION=0

Freecell_OBJC_FILES=\
	Card.m\
	CardView.m\
	Game.m\
	GameController.m\
	GameView.m\
	History.m\
	HistoryController.m\
	PreferencesController.m\
	Result.m\
	Table.m\
	TableLocation.m\
	TableMove.m\
	main.m

Freecell_C_FILES=\
	vccRand.c

Freecell_RESOURCE_FILES=\
	Cards/bonded.png\
	Cards/large-bonded.png\
	Cards/unedited-bonded.png\
	Freecell.icns

Freecell_LOCALIZED_RESOURCE_FILES=\
        MainMenu.nib\
        Localizable.strings\
        Credits.html

Freecell_LANGUAGES=\
	English\
        Dutch\
        Finnish\
        French\
        Japanese\
        Spanish

Freecell_PRINCIPAL_CLASS=Freecell

Freecell_MAIN_MODEL_FILE=Freecell

ADDITIONAL_CPPFLAGS+= -DGNUSTEP

-include GNUmakefile.preamble
include $(GNUSTEP_MAKEFILES)/application.make
-include GNUmakefile.postamble
