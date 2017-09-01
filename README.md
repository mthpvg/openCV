# openCV

## MacOS setup

From: https://medium.com/@acarabott/installing-opencv3-on-macos-sierra-10-12-2-with-c-11-python-3-ffmpeg-gstreamer-tbb-80413092b57d
```bash
brew install python
pip2 install --upgrade pip setuptools
pip2 install numpy
brew install python3
pip3 install --upgrade pip setuptools
pip3 install numpy
brew tap homebrew/science
brew install opencv3 --c++11 --with-contrib --with-examples --with-ffmpeg --with-gstreamer --with-python3 --with-tbb --with-qt5 --with-opengl --with-nonfree

touch /usr/local/lib/python2.7/site-packages/opencv3.pth
echo /usr/local/opt/opencv3/lib/python2.7/site-packages >> /usr/local/lib/python2.7/site-packages/opencv3.pth

touch /usr/local/lib/python3.6/site-packages/opencv3.pth
echo /usr/local/opt/opencv3/lib/python3.6/site-packages >> /usr/local/lib/python3.6/site-packages/opencv3.pth
```

## Quickstart

```bash
python3 index.py
```
