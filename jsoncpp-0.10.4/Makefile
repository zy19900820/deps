
all:
	mkdir -p mybuild;
	cd mybuild;cmake -DJSONCPP_WITH_TESTS=off -DBUILD_STATIC_LIBS=ON -DBUILD_SHARED_LIBS=OFF ..; make

install:
	cd mybuild;make install;

clean:
	rm -rf mybuild;
