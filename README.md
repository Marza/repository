mvn-repo
========

Marza's Maven Repository


Maven
---

<pre>
&lt;repositories&gt;
	&lt;repository&gt;
		&lt;id&gt;marza-repo&lt;/id&gt;
		&lt;url&gt;https://github.com/marza/mvn-repo/raw/master/releases&lt;/url&gt;
    &lt;/repository&gt;
&lt;/repositories&gt;
</pre>

SBT
----

<pre>
resolvers += "marza-mvn-repo" at "https://github.com/marza/mvn-repo/raw/master/releases"
</pre>
