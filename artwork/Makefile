IMAGEW=imagew

all: \
	start-48.png \
	start-48@2x.png \
	start-48@3x.png \
	racing-flag-48.png \
	racing-flag-48@2x.png \
	racing-flag-48@3x.png \
	start-48-negate.png \
	start-48-negate@2x.png \
	start-48-negate@3x.png \
	racing-flag-48-negate.png \
	racing-flag-48-negate@2x.png \
	racing-flag-48-negate@3x.png \

start-48.png:start.png
	$(IMAGEW) -w 48 -h 48 $< $@

start-48@2x.png:start.png
	$(IMAGEW) -w 96 -h 96 $< $@

start-48@3x.png:start.png
	$(IMAGEW) -w 144 -h 144 $< $@

racing-flag-48.png:racing-flag.png
	$(IMAGEW) -w 48 -h 48 $< $@

racing-flag-48@2x.png:racing-flag.png
	$(IMAGEW) -w 96 -h 96 $< $@

racing-flag-48@3x.png:racing-flag.png
	$(IMAGEW) -w 144 -h 144 $< $@

start-48-negate.png:start-48.png
	$(IMAGEW) -negate $< $@

start-48-negate@2x.png:start-48@2x.png
	$(IMAGEW) -negate $< $@

start-48-negate@3x.png:start-48@3x.png
	$(IMAGEW) -negate $< $@

racing-flag-48-negate.png:racing-flag-48.png
	$(IMAGEW) -negate $< $@

racing-flag-48-negate@2x.png:racing-flag-48@2x.png
	$(IMAGEW) -negate $< $@

racing-flag-48-negate@3x.png:racing-flag-48@3x.png
	$(IMAGEW) -negate $< $@
