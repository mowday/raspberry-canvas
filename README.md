Raspberry Canvas
================

A lab for running HTML5 canvas on Raspberry PI

### Installation on raspberry
1. Install NodeJS and NPM:
    sudo apt-get install nodejs npm node-semver
2. Install GIT:
    sudo apt-get install git
3. Install required libraries:
    sudo apt-get install libfreetype6 libfreetype6-dev libfreeimage3 libfreeimage-dev
4. Pull project from GitHub:
    git clone https://github.com/mowday/raspberry-canvas.
    git clone https://github.com/luismreis/node-openvg-canvas.git
5. To test:
    cd node-openvg-canvas
    npm install
    export PATH=$PWD/bin:$PATH
    examples/swissClock.js