# dpdk-apps

# steps to build:
make (or) #meson build; ninja -C build;

# steps to run:
./build/dpdk-app -w af:00.1 -w b1:00.1 -l 26-29 -- -p 3
