libcpxvta
=========

A windows library, based on FFmpeg, to convert videos to audio files. Currently, it supports .mp3 and .ogg file formats.

The DLL exports the function `cpxvta_convert`:

    int cpxvta_convert(
      const char* inputFileName, 
      const char* outputFileName, 
      ConvertSettings* settings, 
      NotifyProgressCallback callback);
