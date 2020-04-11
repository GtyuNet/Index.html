# Index.html
html
<HTML>
<head>
<title>Blanter Wisdom : Documentation</title>
<link href='css/style.css' rel='stylesheet' type='text/css'/>
<script src='js/prism.js' type='text/javascript'></script>
</head>
<body>
<div id='header'>
<div class='wrapper'>
<h1>Blanter Wisdom : Documentation</h1>
</div>
</div>
<div id='wrapper' class='wrapper'>
<center><blockquote><b>USE</b> <code>CTRL + F</code> <b>FOR SEARCH TARGET CODE.</b></blockquote></center>

<div class='content'>
<h2>Meta Tag and SEO Settings</h2>
<pre><code class="language-markup">
&lt;meta content='xxxxx' property='fb:admins'/&gt;
&lt;meta content='xxxxx' property='fb:app_id'/&gt;
&lt;link href='https://plus.google.com/+YOURGPLUS/posts' rel='publisher'/&gt;
&lt;link href='https://plus.google.com/+YOURGPLUS/about' rel='author'/&gt;
&lt;link href='https://plus.google.com/+YOURGPLUS' rel='me'/&gt;
&lt;meta content='xxxxx' name='google-site-verification'/&gt;
&lt;meta content='@xxxxx' name='twitter:creator'/&gt;
&lt;meta content='#eff2f2' name='theme-color'/&gt;
&lt;meta content='#eff2f2' name='msapplication-navbutton-color'/&gt;
&lt;meta content='#eff2f2' name='apple-mobile-web-app-status-bar-style'/&gt;
</code></pre><br/>
</div>


<div class='content'>
<h2>Social Media</h2>
<pre><code class="language-markup">
&lt;ul class='sosmed'&gt;
&lt;li&gt;&lt;a class='fcb' href='#' itemprop='sameAs' target='_blank' title='Facebook'&gt;&lt;i class='fa fa-facebook'/&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a class='twtx' href='#' itemprop='sameAs' target='_blank' title='Twitter'&gt;&lt;i class='fa fa-twitter'/&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a class='igr' href='#' itemprop='sameAs' target='_blank' title='Instagram'&gt;&lt;i class='fa fa-instagram'/&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a class='ytx' href='#' itemprop='sameAs' target='_blank' title='Youtube'&gt;&lt;i class='fa fa-youtube'/&gt;&lt;/a&gt;&lt;/li&gt;
  &lt;/ul&gt;
</code></pre>
<blockquote>Change <i>#</i> with Your URL. Example : <i>href='https://facebook.com'</i> </blockquote>
</div>

<div class='content'>
<h2>Menu Navigation</h2>
<pre><code class="language-markup">
&lt;ul class='nav'&gt;
&lt;li class='current-menu-item'&gt;&lt;a expr:href='data:blog.homepageUrl' itemprop='url' title='Home'&gt;&lt;span itemprop='name'&gt;Home&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='News'&gt;&lt;span itemprop='name'&gt;News&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='Health'&gt;&lt;span itemprop='name'&gt;Health&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='Technology'&gt;&lt;span itemprop='name'&gt;Technology&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='World'&gt;&lt;span itemprop='name'&gt;World&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='Trending'&gt;&lt;span itemprop='name'&gt;Trending&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a class='submenu' href='#' itemprop='url' title='More Menu'&gt;&lt;span itemprop='name'&gt;More Menu&lt;/span&gt;&lt;/a&gt;
&lt;ul&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='Sub Menu 1'&gt;&lt;span itemprop='name'&gt;Sub Menu 1&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='Sub Menu 2'&gt;&lt;span itemprop='name'&gt;Sub Menu 2&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='Sub Menu 3'&gt;&lt;span itemprop='name'&gt;Sub Menu 3&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href='#' itemprop='url' title='Sub Menu 4'&gt;&lt;span itemprop='name'&gt;Sub Menu 4&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;&lt;/li&gt;&lt;div class='nav-line' style='left:0;width:57px;overflow:hidden'/&gt;&lt;/ul&gt;
</code></pre>
<blockquote>Change <i>#</i> with Your URL. Example : <i>href='http://goo.gl'</i> Material Icons : <i>https://material.io/tools/icons/</i> </blockquote>
</div>
<div class='content'>
If you put label url on navigation, please put <i>?&amp;max-results=5</i> too. Example : <i>https://goo.gl/search/label/News?&amp;max-results=5
<br/>

<div class='content'>
<h2>Table Codes</h2>
<pre><code class="language-markup">
&lt;table cellpadding=&quot;0&quot; cellspacing=&quot;0&quot; style=&quot;text-align: left;&quot;&gt;&lt;tbody&gt;
&lt;tr&gt;&lt;th&gt;Item Name&lt;/th&gt;&lt;th&gt;Item Version&lt;/th&gt;&lt;th&gt;Item Price&lt;/th&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Blanter Satu&lt;/td&gt;&lt;td&gt;v2.0&lt;/td&gt;&lt;td&gt;IDR 1&amp;nbsp;&lt;a class=&quot;rightlink&quot; href=&quot;https://www.idblanter.com/&quot; rel=&quot;nofollow&quot; target=&quot;_blank&quot;&gt;Buy Now&lt;/a&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Blanter Dua&lt;/td&gt;&lt;td&gt;v2.1&lt;/td&gt;&lt;td&gt;IDR 0&amp;nbsp;&lt;a class=&quot;rightlink&quot; href=&quot;https://www.idblanter.com/&quot; rel=&quot;nofollow&quot; target=&quot;_blank&quot;&gt;Download&lt;/a&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Blanter Tiga&lt;/td&gt;&lt;td&gt;v1.5&lt;/td&gt;&lt;td&gt;IDR 0&amp;nbsp;&lt;a class=&quot;rightlink&quot; href=&quot;https://www.idblanter.com/&quot; rel=&quot;nofollow&quot; target=&quot;_blank&quot;&gt;Download&lt;/a&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Blanter Empat&lt;/td&gt;&lt;td&gt;v2.0&lt;/td&gt;&lt;td&gt;IDR 1&amp;nbsp;&lt;a class=&quot;rightlink&quot; href=&quot;https://www.idblanter.com/&quot; rel=&quot;nofollow&quot; target=&quot;_blank&quot;&gt;Buy Now&lt;/a&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Blanter Lima&lt;/td&gt;&lt;td&gt;v3.0&lt;/td&gt;&lt;td&gt;IDR 1&amp;nbsp;&lt;a class=&quot;rightlink&quot; href=&quot;https://www.idblanter.com/&quot; rel=&quot;nofollow&quot; target=&quot;_blank&quot;&gt;Buy Now&lt;/a&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Blanter Enam&lt;/td&gt;&lt;td&gt;v1.2&lt;/td&gt;&lt;td&gt;IDR 1&amp;nbsp;&lt;a class=&quot;rightlink&quot; href=&quot;httsp://www.idblanter.com/&quot; rel=&quot;nofollow&quot; target=&quot;_blank&quot;&gt;Buy Now&lt;/a&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Blanter Tujuh&amp;nbsp;&lt;/td&gt;&lt;td&gt;v1.0&lt;/td&gt;&lt;td&gt;IDR 0&amp;nbsp;&lt;a class=&quot;rightlink&quot; href=&quot;https://www.idblanter.com/&quot; rel=&quot;nofollow&quot; target=&quot;_blank&quot;&gt;Download&lt;/a&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Blanter Delapan&amp;nbsp;&lt;/td&gt;&lt;td&gt;v1.0&lt;/td&gt;&lt;td&gt;IDR 1&amp;nbsp;&lt;a class=&quot;rightlink&quot; href=&quot;https://www.idblanter.com/&quot; rel=&quot;nofollow&quot; target=&quot;_blank&quot;&gt;Buy Now&lt;/a&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;/tbody&gt;&lt;/table&gt;
</code></pre>
</div>

<div class='content'>
<h2>Button on Posts</h2>
<pre><code class="language-markup">
&lt;a class=&quot;buttonx&quot; href=&quot;https://www.idblanter.com&quot; target=&quot;_blank&quot;&gt;Download&lt;/a&gt;
</code></pre>
</div>

<br/>
<h2>DESIGN BY RHINOKAGE RIO (RIO ILHAM HADI) SITE : WWW.IDBLANTER.COM</h2>
</div>


</div><br/><br/>
<blockquote><b><center>MORE OPTIONS ON "AUTHOR BOX" AND "WIDGETS" FOLDER ON BLANTER WISDOM FILE.</center></b></blockquote>
<center><p>Copyright © 2018 <b>Blanter Wisdom</b> - Design by <a href="https://www.idblanter.com" target="_blank" title="Dunia Blanter"><b>Dunia Blanter</b></a></p></center>

<script>
$('pre').attr('class', 'line-numbers');
Prism.hooks.add("after-highlight",function(e){var t=e.element.parentNode;if(!t||!/pre/i.test(t.nodeName)||t.className.indexOf("line-numbers")===-1){return}var n=1+e.code.split("\n").length;var r;lines=new Array(n);lines=lines.join("<span></span>");r=document.createElement("span");r.className="line-numbers-rows";r.innerHTML=lines;if(t.hasAttribute("data-start")){t.style.counterReset="linenumber "+(parseInt(t.getAttribute("data-start"),10)-1)}e.element.appendChild(r)})
</script>
<script type='text/javascript'>
var pres = document.getElementsByTagName(&quot;pre&quot;);
for (var i = 0; i &lt; pres.length; i++) {
  pres[i].addEventListener(&quot;dblclick&quot;, function () {
    var selection = getSelection();
    var range = document.createRange();
    range.selectNodeContents(this);
    selection.removeAllRanges();
    selection.addRange(range);
  }, false);
}
</script>
</body>
</HTML>
