---
title: Markdown syntax test page
permalink: /markdownguide/permalink/
description: ""
---
<font color = "red"><b>[Refer to this]</b> Additional reference guide to markdown syntax, syntax examples below</font>

Besides the basic markdown syntax, inline HTML may be used to augment options available for texts/ paragraph

* <font color = "blue"> Colored font example </font>

* <font size="5" color = "blue"> Colored font example with adjusted font size</font>

* <b> bold fonts</b>

* <p> Paragraph example</p>

* Paragraph with newline .<br/> This is the next line (newline).<br/>


* <div style="background-color: #ffd966; padding : 20px"> A section with different background color (hexcode) </div>


Embbeding links using attributes table
Embedded link s (within table) in this example facilitates navigation

| Title example | Link no. |
| --- | --- |
| Title 1 | * [name of title link 1](#1)|
| Title 2 | * [name of title link 2](#2)|


<a id='1'></a>
<b>Title 1</b><br/>
This is a place holder for a section example under Title 1<br/>
String 1<br/>
String 2<br/>
String 3<br/>

<a id='2'></a>
<b>Title 2</b><br/>
This is a place holder for a section example under Title 2

<b> Youtube videos </b> <br/>
While it's not possible to embed video in markdown, the best and easiest way is to extract a frame from the video and link the video url on the image. 
[![Alt text](/images/About%20Create/CreateVisionYTimage.png)](https://safe.menlosecurity.com/https://www.youtube.com/watch?v=fsBoM23PKMs&t=1s)