## Enline CSS ##
Use inline CSS without writing inline CSS (created when building mail templates!).

### Classes ###
Using Enline you can take control of inline CSS to the point of individual elements rather than by grouping. You can also edit the original Sass file to fit your projects needs.

<small><strong>Normal (messy) Inline CSS</strong></small>
<pre>
&lt;div style=&quot;padding: 10px; margin-top: 15px;&quot;&gt;
	&lt;p style=&quot;font-size:14px; color: #eee;&quot;&gt;Hello World&lt;/p&gt;
	&lt;span class=&quot;icon&quot; style=&quot;width:10px; height:10px;&quot;&gt;&lt;/span&gt;
&lt;/div&gt;
</pre>

<small><strong>Enline CSS</strong></small>
<pre>
&lt;div class=&quot;p-10 m-t-15&quot;&gt;
	&lt;p class=&quot;fs-14 fc-#eee&quot;&gt;Hello World&lt;/p&gt;
	&lt;span class=&quot;icon w-10 h-10&quot;&gt;&lt;/span&gt;
&lt;/div&gt;
</pre>



### Class List ###

The following classes are supported in Enline,
    
| Class    | For                        | Value | Demo       | Output                          |
|----------|:--------------------------:|:-----:|:----------:|:-------------------------------:|
| fs       |font-size                   |1-100px|fs-12       |font-size:12px;                  | 
| fw       |font-weight                 |100-900|fw-200      |font-weight:200;                 |
| fc       |font-color                  |defined|fc-#000     |font-color:#000;                 |
| p        |padding                     |1-100px|p-10        |padding: 10px;                   | 
| p-l      |padding-left                |1-100px|p-l-10      |padding-left:10px;               |
| p-r      |padding-right               |1-100px|p-r-10      |padding-right:10px;              |
| p-b      |padding-bottom              |1-100px|p-b-10      |padding-bottom:10px;             |
| p-t      |padding-top                 |1-100px|p-t-10      |padding-top: 10px;               |
| m        |margin                      |1-100px|m-10        |margin: 10px;                    | 
| m-l      |margin-left                 |1-100px|m-l-10      |margin-left:10px;                |
| m-r      |margin-right                |1-100px|m-r-10      |margin-right:10px;               |
| m-b      |margin-bottom               |1-100px|m-b-10      |margin-bottom:10px;              |
| m-t      |margin-top                  |1-100px|m-t-10      |margin-top: 10px;                |
| b-r      |border-radius               |1-100px|b-r-10      |border-radius:10px;              |
| b-t-l-r  |border-top-left-radius      |1-100px|b-t-l-r-10  |border-top-left-radius:10px;     |
| b-t-r-r  |border-top-right-radius     |1-100px|b-t-r-r-10  |border-top-right-radius:10px;    |
| b-b-l-r  |border-bottom-left-radius   |1-100px|b-b-l-r-10  |border-bottom-left-radius:10px;  |
| b-b-r-r  |border-bottom-right-radius  |1-100px|b-b-r-r-10  |border-bottom-right-radius:10px; |
| w        |width                       |1-100px|w-10        |width: 10px;                     | 
| h        |height                      |1-100px|h-10        |height: 10px;                    | 
| col      |column						|1-12   |col-5		 |width: width:41.66667%           |
