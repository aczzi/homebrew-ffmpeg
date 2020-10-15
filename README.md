# homebrew-ffmpeg

In order to use this tap, you need to install Homebrew.

Install libmysofa

```
git clone https://github.com/hoene/libmysofa.git
cd libmysofa/build
cmake -DCMAKE_BUILD_TYPE=Debug ..
make
make install
```

Then, to run a default installation, run:

```
brew tap aczzi/ffmpeg
brew install aczzi/ffmpeg/ffmpeg413
brew install aczzi/ffmpeg/ffmpeg431
```

FROM [homebrew-ffmpeg](https://github.com/homebrew-ffmpeg/homebrew-ffmpeg/)
