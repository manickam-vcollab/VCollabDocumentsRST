
- This repository contains VCollab products documents in rst format.  
- This rst format can help us to convert some other formats.
- Every folder contains config.py file it hepls us to configure the theme.
## Build command for html 
     open local path terminal run 
```sh
  make.bat html
```
     this command will create build folder with html files you can just open index.html file with any browser.
## Build command for chm 
     open local path terminal run
```sh
make.bat htmlhelp
```
     it will create build folder along with sub folder which is "htmlhelp" it has .hhp file 
     you can use the .hhp file in "Html Help Workshop" to generate chm file.  
> Note: When ever we are going to build html or chml using this we need to update videos file path in this rst files.(because document live site has different path for videos)

