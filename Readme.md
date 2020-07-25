# Wahoo Kickr in-the-browser

This project was part of [RemoteHack #4](https://remotehack.space/hacks/04.html). Our goal was to use the Web Bluetooth API to display live data from a Wahoo Kickr smart trainer, and to control the resistance of the trainer from the browser.

We didn't get that close, but the hope was to tie this in with WebSockets to include the smart trainer in a multiplayer game (or just for Ben to be able to make my life physically harder).

# Getting started

1. Start a web server, e.g. with `python -m SimpleHTTPServer 5000`
2. Visit the page: http://localhost:5000
3. Click "Connect", and find your Wahoo Kickr
4. See your instantaneous power reading
5. Check the console for additional information and debugging logs

# Caveats

- This is not tested or production-ready in any way!
- We didn't get power control working. It looks like Wahoo Kickr doesn't support the Fitness Machine profile/service (FTMS), and I've asked [on Twitter](https://twitter.com/spikeheap/status/1287048498710487040).

# MIT License

Copyright 2020 Ryan Brooks

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.