Embedding VCollab Presenter in Internet Browsers
=================================================

VCollab Presenter control can also be embedded in various Internet
Browsers.

VCollab supports plug in presenter for the following browsers:

-  Microsoft Internet Explorer (v6.0 and above) - 32 bit & 64 bit

   -  How to enable Internet Explorer 64 bit?

-  Mozilla Firefox - 32 bit (It is supported till version **51**. Above
   that, **Firefox ESR** version is only supported.)

-  Opera- 32 bit

**Quick view**

-  Open any supported internet browser

-  Drag and drop a CAX file inside the browser to view quickly.

**Steps to embed VCollab Presenter control in HTML source page**

    Insert the following piece of code in the HTML source page.

    <object classid='CLSID:FE5180BC-62B4-40F0-83E2-AB4D96B12558'
    width='600px' height='450px' >

    <param name='Filepath' value='Provide cax file full path here'/>

    <param name="VC\_MAJOR\_VER" value="4">

    <param name="VC\_MINOR\_VER" value="5">

    <param name ='xpForceClear' value ='1' />

    <object type='application/x-vnd-vcollab-cax' data='Provide cax file
    path here' width='600px height='450px' ><br/>

    <div style='text-align:center;'>VCollab Presenter is supported in
    Microsoft Internet Explorer (32-bit & 64-bit), Mozilla Firefox
    (32-bit) and Google Chrome (32-bit) browsers on Windows

    operating systems. <br/>Other operating systems are not supported as
    of now. <br/></div> <br/><div style='text-align:center;'>VCollab
    Presenter

    (Lite) is required to view this page. <br/><a
    href='http://www.marechi.com/DownloadPresenter.aspx'>Click Here to
    Download VCollab Presenter

    Lite</a><br/><br/>If you have VCollab Presenter (Lite) installed on
    your system, <br/>and still see this message, <a

    href='http://www.vcollab.com/presentertroubleshooting.html'
    target='\_blank' >click here</a></div>

    </object>

    </object>

    **Example HTML Source Code**

    <HTML>

    <HEAD>

    <TITLE>VCollab Presenter</TITLE>

    </HEAD>

    <BODY>

    <p align = center ><Font face = Arial size = 8>VCollab Presenter
    </font></p>

    <P>

    <div style='text-align:center;'>

    <object classid='CLSID:FE5180BC-62B4-40F0-83E2-AB4D96B12558'
    width='600px' height='450px' >

    <param name='Filepath'
    value='http://vcollab.com/EPresenter/Models/airbag.cax\ `*'/* <https://s3.amazonaws.com/marechi/5cb03517-856b-4c7e-b4ac-767c9ee2f20c.cax'/>`__>

    <param name="VC\_MAJOR\_VER" value="4">

    <param name="VC\_MINOR\_VER" value="5">

    <param name ='xpForceClear' value ='1' />

    <object type='application/x-vnd-vcollab-cax'
    data='http://vcollab.com/EPresenter/Models/airbag.cax' width='600px'
    height='450px' ><br/>

    <div style='text-align:center;'>VCollab Presenter is supported in
    Microsoft Internet Explorer (32-bit & 64-bit), Mozilla Firefox
    (32-bit) and Google Chrome (32-bit) browsers on Windows operating
    systems. <br/>Other operating systems are not supported as of now.
    <br/></div> <br/><div style='text-align:center;'>VCollab Presenter
    (Lite) is required to view this page. <br/><a
    href='http://www.marechi.com/DownloadPresenter.aspx'>Click Here to
    Download VCollab Presenter Lite</a><br/><br/>If you have VCollab
    Presenter (Lite) installed on your system, <br/>and still see this
    message, <a
    href='http://www.vcollab.com/presentertroubleshooting.html'
    target='\_blank' >click here</a></div></object></object></div>

    </P>

    </HTML>

**Note**:

    The fields in red and bold are mandatory.

    **Example** **Link**

    http://www.vcollab.com//Presenter/VCollab\_HTML\_Sample.html
