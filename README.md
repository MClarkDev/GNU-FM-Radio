# Quad Channel FM Decoder

Built with GNU Radio Companion and [osmosdr](https://github.com/osmocom/gr-osmosdr), this script will allow a user to tune an SDR to a portion of the spectrum where multiple radio stations can be seen at the same time. Using the sub-channel tuning knobs, up to 4 individual FM Radio Stations can be decoded at the same time.

![Quad-Channel FM Decoder](https://ftp.mclarkdev.com/uploads/media/fm_decode.png)

## Stream Recording

By default, each of the 4x tuners will save a stream recording to disk.

## Network Streaming

By default, each of the 4x tuners will open a TCP socket, awaiting connections from clients. This socket will stream the raw output received by the tuner. This stream may then be processed by tools like Audacity.

Tuner 1: TCP/2000<br/>
Tuner 2: TCP/2001<br/>
Tuner 3: TCP/2002<br/>
Tuner 4: TCP/2003

