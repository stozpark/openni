include Common/CommonDefs.mak

.PHONY: all

NETPROJ = 
ifneq "$(realpath /usr/bin/gmcs)" ""
	NETPROJ += Boxes.net
endif

all: $(NETPROJ) PointServer Players SceneAnalysis Boxes.java Boxes CircleControl SingleControl TrackPad PointViewer 


.PHONY: PointServer
PointServer:
	$(MAKE) -C ../PointServer

.PHONY: Players
Players:
	$(MAKE) -C ../Players

.PHONY: SceneAnalysis
SceneAnalysis:
	$(MAKE) -C ../SceneAnalysis

.PHONY: Boxes.java
Boxes.java:
	$(MAKE) -C ../Boxes.java

.PHONY: Boxes
Boxes:
	$(MAKE) -C ../Boxes

.PHONY: CircleControl
CircleControl:
	$(MAKE) -C ../CircleControl

.PHONY: SingleControl
SingleControl:
	$(MAKE) -C ../SingleControl

.PHONY: TrackPad
TrackPad:
	$(MAKE) -C ../TrackPad

.PHONY: PointViewer
PointViewer:
	$(MAKE) -C ../PointViewer

.PHONY: Boxes.net
Boxes.net:
	$(MAKE) -C ../Boxes.net
