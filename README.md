sudo apt-get install make

sudo apt-get install build-essential

sudo apt-get install openssl

cd live

sudo ./configure

sudo make

cd testProgs

sudo ./testRTSPClient rtsp://wowzaec2demo.streamlock.net/vod/mp4:BigBuckBunny_115k.mov
