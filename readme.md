* https://www.hackster.io/idreams/getting-started-with-rgb-matrix-panel-adaa49
* Install Prerequisites   sudo apt-get install -y --force-yespython2.7-dev python-pillow python3-dev python3-pillow libgraphicsmagick++-devlibwebp-dev
* Install library

git clone https://github.com/hzeller/rpi-rgb-led-matrix.git 
cd rpi-rgb-led-matrix 
make all 
make build-python 
make install-python 

* sudo raspi-config enable I2C, close audio in /boot/config.txt -> dtparam=audio=off

* for python ---------------------------

* rss scroll example in folder -> bindings -> python -> example

* To use our 32x32 panel, command is /home/pi/rpi_matrix/rpi-rgb-led-matrix/bindings/python/example# python scroll.py -r 32 -t 64

* a PPM file is pre-save in folder newsimg, you can run code to generate from rss -> python rss.py

* All in one python code python rss.py & python scroll.py

* for C ------------------------------

* too difficult for me :)
