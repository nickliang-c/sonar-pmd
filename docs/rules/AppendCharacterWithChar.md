# AppendCharacterWithChar
**Category:** `pmd`<br/>
**Rule Key:** `pmd:AppendCharacterWithChar`<br/>


-----

<!-- (c) 2019 PMD -->
Avoid concatenating characters as strings in <code>StringBuffer</code>/<code>StringBuilder.append</code> methods.

<h2>Noncompliant Code Example</h2>
<pre>
StringBuffer sb = new StringBuffer();
sb.append("a");     // avoid this
</pre>
<h2>Compliant Solution</h2>
<pre>
StringBuffer sb = new StringBuffer();
sb.append('a');     // use this instead
</pre>
