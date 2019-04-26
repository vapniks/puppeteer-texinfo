# puppeteer-texinfo
texinfo & info files for puppeteer documentation

To recreate the info files from the texinfo file: 
 1) makinfo puppeteer.texinfo
 2) sudo cp puppeteer.info* /usr/share/info/
 3) cd /usr/share/info/
 4) sudo install-info puppeteer.info dir
 
