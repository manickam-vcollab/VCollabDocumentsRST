# Guides to generate html and chm
## File format
- This repository contains VCollab products documents in **rst** format.
## What is sphnix 
- Sphinx is a documentation generator or a tool that translates a set of plain text source files into various output formats, automatically producing cross- 
  references, indices, etc
- Sphinx document reference guide [Sphinx link]

## Installation

     
```sh
  pip install -U sphinx
```


## Configuration of sphnix theme
- Each folder has **config.py** file it hepls us to configure the sphinx theme.
  
## Build command for html 
 Open local path terminal and run following command
     
     
```sh
  make.bat html
```


  This command will create build folder with html files you can just open **index.html** file with any browser.
## Build command for chm 
 Open local path terminal and run following command


```sh
make.bat htmlhelp
```


  This command will create build folder along with sub folder which is called **htmlhelp** it has **.hhp** file 
 you can use this file in to **Html Help Workshop** [Html help] it's an application to generate **chm** file.  
> Note: If you are going to build html or chm you need to update videos file path in rst files.(**because live site folder structure is different**).
> 
> [Sphinx link]: https://www.sphinx-doc.org/en/master/
> [Html help]: https://learn.microsoft.com/en-us/previous-versions/windows/desktop/htmlhelp/microsoft-html-help-downloads

