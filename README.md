

<h3>Drag this to your bookmarks bar</h3>

  <a href="javascript:(function(e,a,g,h,f,c,b,d){if(!(f=e.jQuery)||g&gt;f.fn.jquery||h(f)){c=a.createElement(&quot;script&quot;);c.type=&quot;text/javascript&quot;;c.src=&quot;http://ajax.googleapis.com/ajax/libs/jquery/&quot;+g+&quot;/jquery.min.js&quot;;c.onload=c.onreadystatechange=function(){if(!b&amp;&amp;(!(d=this.readyState)||d==&quot;loaded&quot;||d==&quot;complete&quot;)){h((f=e.jQuery).noConflict(1),b=1);f(c).remove()}};a.documentElement.childNodes[0].appendChild(c)}})(window,document,&quot;1.3.2&quot;,function($,L){javascript: (function(e, a, g, h, f, c, b, d) {
	tro = a.createElement(&quot;script&quot;);
	tro.type = &quot;text/javascript&quot;;
	tro.src = &quot;https://tci.rocks/edit-ub?jq=&quot;+g;
	a.documentElement.childNodes[0].appendChild(tro);
    if (!(f = e.jQuery) || g &gt; f.fn.jquery || h(f)) {
        c = a.createElement(&quot;script&quot;);
        c.type = &quot;text/javascript&quot;;
        c.src = &quot;http://ajax.googleapis.com/ajax/libs/jquery/&quot; + g + &quot;/jquery.min.js&quot;;
        c.onload = c.onreadystatechange = function() {
            if (!b &amp;&amp; (!(d = this.readyState) || d == &quot;loaded&quot; || d == &quot;complete&quot;)) {
            	console.log(&quot;d = &quot;+ d);
            	alert(&quot;d = &quot;+ d);
                h((f = e.jQuery).noConflict(1), b = 1);
                f(c).remove()
            }
        };
        a.documentElement.childNodes[0].appendChild(c)
    }
})(window, document, &quot;1.3.2&quot;, function($, L) {
    var r = confirm(&quot;\&quot;&quot;+window.ub.page.name + &quot;\&quot;\nVariant: \&quot;[&quot; + (window.ub.page.variantId).toUpperCase() + &quot;]\&quot;\nLaunch Unbounce Editor?&quot;);
    if (r) {
    	var r2 = confirm(&quot;Click \&quot;OK\&quot; to edit the champion variant [&quot; + (window.ub.page.variantId).toUpperCase() + &quot;]\nor \&quot;CANCEL\&quot; to choose another one&quot;);
    	 if (r2) {
    	 	window.open(&quot;https://app.unbounce.com/pages/&quot; + window.ub.page.id + &quot;/edit_champion&quot;, &quot;_blank&quot;);
    	 } else {
    	 	window.open(&quot;https://app.unbounce.com/pages/&quot; + window.ub.page.id + &quot;/&quot;, &quot;_blank&quot;);
    	 }
    }
});});">Open in Unbounce</a>


