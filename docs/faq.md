# Electron Release Server FAQ

### What files should I upload?

Electron Release Server uses explicit file compatibility naming in order to avoid unexpected issues, there is no strict policy on file naming.

- Windows: `.exe`, `.nupkg` etc
- Linux: `.deb`, `.tar.gz`, etc
- OS X: `.dmg`, etc

32 bit releases are made available to all clients, but 64 bit files are served to compatible clients if available.

### How should I name my releases?

Electron Release Server requires applications to follow [SemVer](http://semver.org). And even if you're not using Electron Release Server, you should follow it!

### I have it working locally, but how to get it onto a server now?

If you don't have a Node.js server already running and secure, consider this tutorial to get you started:
https://www.youtube.com/watch?v=kR06NoSzAXY

If you are failing at npm install, make sure you have enough RAM on your server.

Sails tool works with many other hosts like Heroku, so you aren't just limited to DigitalOcean. 
