.SILENT:
COMP = g++

all: UNIX_Exercice4 Traitement

UNIX_Exercice4: mainex4.o mainwindowex4.o moc_mainwindowex4.o
	echo Creation UNIX_Exercice4
	${COMP} -o UNIX_Exercice4 mainex4.o mainwindowex4.o moc_mainwindowex4.o   /usr/lib64/libQt5Widgets.so /usr/lib64/libQt5Gui.so /usr/lib64/libQt5Core.so /usr/lib64/libGL.so -lpthread

mainex4.o: mainex4.cpp
	echo Creation mainex4.o
	${COMP} -c -pipe -g -std=gnu++11 -Wall -W -D_REENTRANT -fPIC -DQT_DEPRECATED_WARNINGS -DQT_QML_DEBUG -DQT_WIDGETS_LIB -DQT_GUI_LIB -DQT_CORE_LIB -I. -isystem /usr/include/qt5 -isystem /usr/include/qt5/QtWidgets -isystem /usr/include/qt5/QtGui -isystem /usr/include/qt5/QtCore -I. -I. -I/usr/lib64/qt5/mkspecs/linux-g++ -o mainex4.o mainex4.cpp

mainwindowex4.o: mainwindowex4.cpp
	echo Creation mainwindowex4.o
	${COMP} -c -pipe -g -std=gnu++11 -Wall -W -D_REENTRANT -fPIC -DQT_DEPRECATED_WARNINGS -DQT_QML_DEBUG -DQT_WIDGETS_LIB -DQT_GUI_LIB -DQT_CORE_LIB -I. -isystem /usr/include/qt5 -isystem /usr/include/qt5/QtWidgets -isystem /usr/include/qt5/QtGui -isystem /usr/include/qt5/QtCore -I. -I. -I/usr/lib64/qt5/mkspecs/linux-g++ -o mainwindowex4.o mainwindowex4.cpp

moc_mainwindowex4.o: moc_mainwindowex4.cpp
	echo Creation moc_mainwindowex4.o
	${COMP} -c -pipe -g -std=gnu++11 -Wall -W -D_REENTRANT -fPIC -DQT_DEPRECATED_WARNINGS -DQT_QML_DEBUG -DQT_WIDGETS_LIB -DQT_GUI_LIB -DQT_CORE_LIB -I. -isystem /usr/include/qt5 -isystem /usr/include/qt5/QtWidgets -isystem /usr/include/qt5/QtGui -isystem /usr/include/qt5/QtCore -I. -I. -I/usr/lib64/qt5/mkspecs/linux-g++ -o moc_mainwindowex4.o moc_mainwindowex4.cpp



Traitement: maintraitement.o mainwindowtraitement.o moc_mainwindowtraitement.o
	echo Creation Traitement
	${COMP} -L/usr/lib64/mysql -lmysqlclient -lpthread -lz -lm -lrt -lssl -lcrypto -ldl -o Traitement maintraitement.o mainwindowtraitement.o moc_mainwindowtraitement.o /usr/lib64/libQt5Widgets.so /usr/lib64/libQt5Gui.so /usr/lib64/libQt5Core.so /usr/lib64/libGL.so

maintraitement.o: maintraitement.cpp
	echo Creation maintraitement.o
	${COMP} -c -pipe -g -std=gnu++11 -Wall -W -D_REENTRANT -fPIC -DQT_DEPRECATED_WARNINGS -DQT_QML_DEBUG -DQT_WIDGETS_LIB -DQT_GUI_LIB -DQT_CORE_LIB -I. -isystem /usr/include/qt5 -isystem /usr/include/qt5/QtWidgets -isystem /usr/include/qt5/QtGui -isystem /usr/include/qt5/QtCore -I. -I. -I/usr/lib64/qt5/mkspecs/linux-g++ -o maintraitement.o maintraitement.cpp

mainwindowtraitement.o: mainwindowtraitement.cpp
	echo Creation mainwindowtraitement.o
	${COMP} -c -pipe -g -std=gnu++11 -Wall -W -D_REENTRANT -fPIC -DQT_DEPRECATED_WARNINGS -DQT_QML_DEBUG -DQT_WIDGETS_LIB -DQT_GUI_LIB -DQT_CORE_LIB -I. -isystem /usr/include/qt5 -isystem /usr/include/qt5/QtWidgets -isystem /usr/include/qt5/QtGui -isystem /usr/include/qt5/QtCore -I. -I. -I/usr/lib64/qt5/mkspecs/linux-g++ -I/usr/include/mysql -m64 -o mainwindowtraitement.o mainwindowtraitement.cpp

moc_mainwindowtraitement.o: moc_mainwindowtraitement.cpp
	echo Creation moc_mainwindowtraitement.o
	${COMP} -c -pipe -g -std=gnu++11 -Wall -W -D_REENTRANT -fPIC -DQT_DEPRECATED_WARNINGS -DQT_QML_DEBUG -DQT_WIDGETS_LIB -DQT_GUI_LIB -DQT_CORE_LIB -I. -isystem /usr/include/qt5 -isystem /usr/include/qt5/QtWidgets -isystem /usr/include/qt5/QtGui -isystem /usr/include/qt5/QtCore -I. -I. -I/usr/lib64/qt5/mkspecs/linux-g++ -o moc_mainwindowtraitement.o moc_mainwindowtraitement.cpp
