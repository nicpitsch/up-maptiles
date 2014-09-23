UP-maptiles
=============

Simple local map tileserver with a test map

# Usage

Clone this repo somewhere and run `python corsserver.py 8002` in it. This will start a local server on port 8002, which you can access at `0.0.0.0:8002`, `127.0.0.1:8002` or your local network IP, `192.168.???.???:8000`. It sends super friendly CORS headers so you can access it from everywhere.

The tile URL scheme is `hostName+':8002/{z}/{x}/{y}.jpg'`, in this particular case in CRS EPSG 21781, if you find your offsets are weird, this is why.
