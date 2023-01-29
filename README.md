# Quad Channel FM Decoder

Built with GNU Radio Companion and [osmosdr](https://github.com/osmocom/gr-osmosdr), this script will allow a user to tune an SDR to a portion of the spectrum where multiple radio stations can be seen at the same time. Using the sub-channel tuning knobs, up to 4 individual FM Radio Stations can be decoded at the same time.

![Quad-Channel FM Decoder](https://ftp.mclarkdev.com/uploads/media/fm_decode.png)

While tuned to each station, the script will both save the autio waveform to disk and make a TCP socket available for remote monitoring.

