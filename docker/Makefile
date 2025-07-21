install:
        git clone --depth=1 -b v8.22.0 https://github.com/digibyte/digibyte.git src && \
	cd src && \
	cmake -B build -DENABLE_WALLET=OFF -DBUILD_UTIL=OFF -DTEST_UTIL=OFF -DBUILD_GUI=OFF && \
	cmake --build build && \
	cp build/bin/* /usr/local/bin/ && \
	ls -al /usr/local/bin/
