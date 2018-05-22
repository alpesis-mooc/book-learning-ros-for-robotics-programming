BUILD_DIR = _build

CC = g++
HEADERS = /opt/ros/kinetic/include
LIBS_DIR = /opt/ros/kinetic/lib
LIBS = -lroscpp -lrosconsole -lroscpp_serialization -lrostime 


all:
	$(CC) chatter_publisher.cpp -o $(BUILD_DIR)/chatter_publisher -I$(HEADERS) -L$(LIBS_DIR) $(LIBS)
	$(CC) chatter_subscriber.cpp -o $(BUILD_DIR)/chatter_subscriber -I$(HEADERS) -L$(LIBS_DIR) $(LIBS)
 
