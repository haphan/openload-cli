### Openload Downloader via Axel

This is a modified version of a script that I found somewhere that I could not remember.

Credit goes to the rightful author of this script.
 

#### Requirements

- phantom-js
- npm
- axel


#### Installation

```bash
$ git clone https://github.com/haphan/openload-cli.git && cd openload-cli
$ chmod +x openload.js
$ mv openload.js /usr/local/bin/openload
```

#### Usage

```bash
$ openload https://openload.co/embed/foobar.mp4 | bash -xe
```