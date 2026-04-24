# SKY_4K________SIGN-sky4k

This repository contains m3u8 playlist files for various SKY 4K channels.

## How to play in the browser

An `index.html` file has been provided to easily play these streams directly in your browser using [hls.js](https://github.com/video-dev/hls.js).

To view the streams:

1. You need to serve the directory using a local web server (opening the file directly from the filesystem might cause CORS or loading issues).
2. If you have Python 3 installed, you can run the following command in your terminal from the root of this repository:

   ```bash
   python3 -m http.server 8000
   ```

3. Open your web browser and navigate to: [http://localhost:8000](http://localhost:8000)

4. You can select the channel from the sidebar and watch the stream.
