CC=g++
CV=-I/usr/include/opencv
CV2=-lml -lcvaux -lhighgui -lcv -lcxcore
OPENCV = `pkg-config opencv --cflags --libs`
all:
	
	$(CC) main.cpp HOG.cpp HOGFeaturesOfBlock.cpp $(OPENCV) -o featureExtractor

