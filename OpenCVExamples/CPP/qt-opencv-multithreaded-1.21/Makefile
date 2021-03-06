#############################################################################
# Makefile for building: qt-opencv-multithreaded
# Generated by qmake (2.01a) (Qt 4.8.1) on: Sun Oct 28 21:25:43 2012
# Project:  qt-opencv-multithreaded.pro
# Template: app
# Command: /usr/bin/qmake-qt4 -spec /usr/share/qt4/mkspecs/linux-g++ -o Makefile qt-opencv-multithreaded.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_WEBKIT -DAPP_VERSION=1.21 -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtGui -I/usr/include/qt4 -I. -I.
LINK          = g++
LFLAGS        = -Wl,-O1
LIBS          = $(SUBLIBS)  -L/usr/lib/x86_64-linux-gnu -lopencv_core -lopencv_imgproc -lopencv_highgui -lopencv_ml -lopencv_video -lopencv_features2d -lopencv_calib3d -lopencv_objdetect -lopencv_contrib -lopencv_legacy -lopencv_flann -lQtGui -lQtCore -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/bin/qmake-qt4
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = main.cpp \
		MainWindow.cpp \
		CaptureThread.cpp \
		Controller.cpp \
		ImageBuffer.cpp \
		CameraConnectDialog.cpp \
		ProcessingThread.cpp \
		FrameLabel.cpp \
		MatToQImage.cpp \
		ImageProcessingSettingsDialog.cpp moc_MainWindow.cpp \
		moc_CaptureThread.cpp \
		moc_Controller.cpp \
		moc_CameraConnectDialog.cpp \
		moc_ProcessingThread.cpp \
		moc_FrameLabel.cpp \
		moc_ImageProcessingSettingsDialog.cpp
OBJECTS       = main.o \
		MainWindow.o \
		CaptureThread.o \
		Controller.o \
		ImageBuffer.o \
		CameraConnectDialog.o \
		ProcessingThread.o \
		FrameLabel.o \
		MatToQImage.o \
		ImageProcessingSettingsDialog.o \
		moc_MainWindow.o \
		moc_CaptureThread.o \
		moc_Controller.o \
		moc_CameraConnectDialog.o \
		moc_ProcessingThread.o \
		moc_FrameLabel.o \
		moc_ImageProcessingSettingsDialog.o
DIST          = /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		qt-opencv-multithreaded.pro
QMAKE_TARGET  = qt-opencv-multithreaded
DESTDIR       = 
TARGET        = qt-opencv-multithreaded

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET): ui_ImageProcessingSettingsDialog.h ui_CameraConnectDialog.h ui_MainWindow.h $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: qt-opencv-multithreaded.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/common/gcc-base.conf \
		/usr/share/qt4/mkspecs/common/gcc-base-unix.conf \
		/usr/share/qt4/mkspecs/common/g++-base.conf \
		/usr/share/qt4/mkspecs/common/g++-unix.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/release.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		/usr/lib/x86_64-linux-gnu/libQtGui.prl \
		/usr/lib/x86_64-linux-gnu/libQtCore.prl
	$(QMAKE) -spec /usr/share/qt4/mkspecs/linux-g++ -o Makefile qt-opencv-multithreaded.pro
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/common/gcc-base.conf:
/usr/share/qt4/mkspecs/common/gcc-base-unix.conf:
/usr/share/qt4/mkspecs/common/g++-base.conf:
/usr/share/qt4/mkspecs/common/g++-unix.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/modules/qt_webkit_version.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/release.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/unix/gdb_dwarf_index.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/share/qt4/mkspecs/features/include_source_dir.prf:
/usr/lib/x86_64-linux-gnu/libQtGui.prl:
/usr/lib/x86_64-linux-gnu/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -spec /usr/share/qt4/mkspecs/linux-g++ -o Makefile qt-opencv-multithreaded.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/qt-opencv-multithreaded1.21 || $(MKDIR) .tmp/qt-opencv-multithreaded1.21 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/qt-opencv-multithreaded1.21/ && $(COPY_FILE) --parents MainWindow.h CaptureThread.h Controller.h ImageBuffer.h CameraConnectDialog.h ProcessingThread.h FrameLabel.h Structures.h Config.h MatToQImage.h ImageProcessingSettingsDialog.h Robot.h ColorCalibration.h .tmp/qt-opencv-multithreaded1.21/ && $(COPY_FILE) --parents main.cpp MainWindow.cpp CaptureThread.cpp Controller.cpp ImageBuffer.cpp CameraConnectDialog.cpp ProcessingThread.cpp FrameLabel.cpp MatToQImage.cpp ImageProcessingSettingsDialog.cpp .tmp/qt-opencv-multithreaded1.21/ && $(COPY_FILE) --parents ImageProcessingSettingsDialog.ui CameraConnectDialog.ui MainWindow.ui .tmp/qt-opencv-multithreaded1.21/ && (cd `dirname .tmp/qt-opencv-multithreaded1.21` && $(TAR) qt-opencv-multithreaded1.21.tar qt-opencv-multithreaded1.21 && $(COMPRESS) qt-opencv-multithreaded1.21.tar) && $(MOVE) `dirname .tmp/qt-opencv-multithreaded1.21`/qt-opencv-multithreaded1.21.tar.gz . && $(DEL_FILE) -r .tmp/qt-opencv-multithreaded1.21


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_MainWindow.cpp moc_CaptureThread.cpp moc_Controller.cpp moc_CameraConnectDialog.cpp moc_ProcessingThread.cpp moc_FrameLabel.cpp moc_ImageProcessingSettingsDialog.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_MainWindow.cpp moc_CaptureThread.cpp moc_Controller.cpp moc_CameraConnectDialog.cpp moc_ProcessingThread.cpp moc_FrameLabel.cpp moc_ImageProcessingSettingsDialog.cpp
moc_MainWindow.cpp: ui_MainWindow.h \
		FrameLabel.h \
		Structures.h \
		MainWindow.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) MainWindow.h -o moc_MainWindow.cpp

moc_CaptureThread.cpp: CaptureThread.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) CaptureThread.h -o moc_CaptureThread.cpp

moc_Controller.cpp: CaptureThread.h \
		ProcessingThread.h \
		Structures.h \
		Controller.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) Controller.h -o moc_Controller.cpp

moc_CameraConnectDialog.cpp: ui_CameraConnectDialog.h \
		CameraConnectDialog.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) CameraConnectDialog.h -o moc_CameraConnectDialog.cpp

moc_ProcessingThread.cpp: Structures.h \
		ProcessingThread.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) ProcessingThread.h -o moc_ProcessingThread.cpp

moc_FrameLabel.cpp: Structures.h \
		FrameLabel.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) FrameLabel.h -o moc_FrameLabel.cpp

moc_ImageProcessingSettingsDialog.cpp: ui_ImageProcessingSettingsDialog.h \
		Structures.h \
		ImageProcessingSettingsDialog.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) ImageProcessingSettingsDialog.h -o moc_ImageProcessingSettingsDialog.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all: ui_ImageProcessingSettingsDialog.h ui_CameraConnectDialog.h ui_MainWindow.h
compiler_uic_clean:
	-$(DEL_FILE) ui_ImageProcessingSettingsDialog.h ui_CameraConnectDialog.h ui_MainWindow.h
ui_ImageProcessingSettingsDialog.h: ImageProcessingSettingsDialog.ui
	/usr/bin/uic-qt4 ImageProcessingSettingsDialog.ui -o ui_ImageProcessingSettingsDialog.h

ui_CameraConnectDialog.h: CameraConnectDialog.ui
	/usr/bin/uic-qt4 CameraConnectDialog.ui -o ui_CameraConnectDialog.h

ui_MainWindow.h: MainWindow.ui \
		FrameLabel.h \
		Structures.h
	/usr/bin/uic-qt4 MainWindow.ui -o ui_MainWindow.h

compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_uic_clean 

####### Compile

main.o: main.cpp MainWindow.h \
		ui_MainWindow.h \
		FrameLabel.h \
		Structures.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cpp

MainWindow.o: MainWindow.cpp CameraConnectDialog.h \
		ui_CameraConnectDialog.h \
		ImageProcessingSettingsDialog.h \
		ui_ImageProcessingSettingsDialog.h \
		Structures.h \
		Controller.h \
		CaptureThread.h \
		ProcessingThread.h \
		MainWindow.h \
		ui_MainWindow.h \
		FrameLabel.h \
		Config.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o MainWindow.o MainWindow.cpp

CaptureThread.o: CaptureThread.cpp CaptureThread.h \
		ImageBuffer.h \
		Config.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o CaptureThread.o CaptureThread.cpp

Controller.o: Controller.cpp Controller.h \
		CaptureThread.h \
		ProcessingThread.h \
		Structures.h \
		ImageBuffer.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o Controller.o Controller.cpp

ImageBuffer.o: ImageBuffer.cpp ImageBuffer.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ImageBuffer.o ImageBuffer.cpp

CameraConnectDialog.o: CameraConnectDialog.cpp CameraConnectDialog.h \
		ui_CameraConnectDialog.h \
		Config.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o CameraConnectDialog.o CameraConnectDialog.cpp

ProcessingThread.o: ProcessingThread.cpp ImageBuffer.h \
		ProcessingThread.h \
		Structures.h \
		MatToQImage.h \
		Config.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ProcessingThread.o ProcessingThread.cpp

FrameLabel.o: FrameLabel.cpp FrameLabel.h \
		Structures.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o FrameLabel.o FrameLabel.cpp

MatToQImage.o: MatToQImage.cpp MatToQImage.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o MatToQImage.o MatToQImage.cpp

ImageProcessingSettingsDialog.o: ImageProcessingSettingsDialog.cpp ImageProcessingSettingsDialog.h \
		ui_ImageProcessingSettingsDialog.h \
		Structures.h \
		Config.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ImageProcessingSettingsDialog.o ImageProcessingSettingsDialog.cpp

moc_MainWindow.o: moc_MainWindow.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_MainWindow.o moc_MainWindow.cpp

moc_CaptureThread.o: moc_CaptureThread.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_CaptureThread.o moc_CaptureThread.cpp

moc_Controller.o: moc_Controller.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_Controller.o moc_Controller.cpp

moc_CameraConnectDialog.o: moc_CameraConnectDialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_CameraConnectDialog.o moc_CameraConnectDialog.cpp

moc_ProcessingThread.o: moc_ProcessingThread.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_ProcessingThread.o moc_ProcessingThread.cpp

moc_FrameLabel.o: moc_FrameLabel.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_FrameLabel.o moc_FrameLabel.cpp

moc_ImageProcessingSettingsDialog.o: moc_ImageProcessingSettingsDialog.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_ImageProcessingSettingsDialog.o moc_ImageProcessingSettingsDialog.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

