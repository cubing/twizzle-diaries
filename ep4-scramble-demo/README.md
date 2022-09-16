# How to use `cubing.js` for scrambles

<a href="https://www.youtube.com/watch?v=EE0mzwPBFAU&list=PLFh3NgpDbzN4VkcfjEZSQ_TYQv_OEjbjF&index=4">YouTube video<br>
<img src="./Twizzle%20Diaries%20%E2%80%94%20Ep.%204%20%E2%80%94%20How%20to%20use%20cubing.js%20for%20scrambles.jpeg" width="256"></img>
</a>

## Running

To run this code:

- Download code from <https://github.com/cubing/twizzle-diaries/archive/refs/heads/main.zip> (or `git clone`, if you know how)
  - Unzip and enter the `ep4-scramble-demo` folder.
- Start a web server. For example:
  - If you're not familiar the commandline, consider something like [this Chrome extension](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb) to serve the folder.
  - If you're familiar with the commandline, one of these may be convenient:
    - Python 3: `python3 -m http.server`
    - `node` & `npm`: `npx http-server`
    - [`caddy`](https://caddyserver.com/): `caddy file-server --listen :8000 --browse`

## Changes from the video

- The code that gets the event from the URL now includes `?? "333"`. This will default to 3x3x3 if no event is specified in the URL bar.
