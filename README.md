# Scraping
<table class="wikitable">

<tbody>

<tr>

<th>Pattern</th>

<th>Matches</th>

<th>First defined in CSS level</th>

</tr>

<tr>

<td>`<span class="nt">E</span>`</td>

<td>an element of type E</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">link</span>`</td>

<td>an E element is the source anchor of a hyperlink of which the target is not yet visited (:link) or already visited (:visited)</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">active</span>`</td>

<td>an E element during certain user actions</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">::</span><span class="nd">first-line</span>`</td>

<td>the first formatted line of an E element</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">::</span><span class="nd">first-letter</span>`</td>

<td>the first formatted letter of an E element</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="p">.</span><span class="nc">c</span>`</td>

<td>all elements with class="c"</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="p">#</span><span class="nn">myid</span>`</td>

<td>the element with id="myid"</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">.</span><span class="nc">warning</span>`</td>

<td>an E element whose class is "warning" (the document language specifies how class is determined)</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">#</span><span class="nn">myid</span>`</td>

<td>an E element with ID equal to "myid"</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="p">.</span><span class="nc">c</span><span class="p">#</span><span class="nn">myid</span>`</td>

<td>the element with class="c" and ID equal to "myid"</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="nt">E</span> <span class="nt">F</span>`</td>

<td>an F element descendant of an E element</td>

<td>1</td>

</tr>

<tr>

<td>`<span class="o">*</span>`</td>

<td>any element</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="o">[</span><span class="nt">foo</span><span class="o">]</span>`</td>

<td>an E element with a "foo" attribute</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="o">[</span><span class="nt">foo</span><span class="o">=</span><span class="s2">"bar"</span><span class="o">]</span>`</td>

<td>an E element whose "foo" attribute value is exactly equal to "bar"</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="o">[</span><span class="nt">foo</span><span class="o">~=</span><span class="s2">"bar"</span><span class="o">]</span>`</td>

<td>an E element whose "foo" attribute value is a list of whitespace-separated values, one of which is exactly equal to "bar"</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="o">[</span><span class="nt">foo</span><span class="o">|=</span><span class="s2">"en"</span><span class="o">]</span>`</td>

<td>an E element whose "foo" attribute has a hyphen-separated list of values beginning (from the left) with "en"</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">first-child</span>`</td>

<td>an E element, first child of its parent</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">lang</span><span class="o">(</span><span class="nt">fr</span><span class="o">)</span>`</td>

<td>an element of type E in language "fr" (the document language specifies how language is determined)</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">::</span><span class="nd">before</span>`</td>

<td>generated content before an E element's content</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">::</span><span class="nd">after</span>`</td>

<td>generated content after an E element's content</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span> <span class="o">></span> <span class="nt">F</span>`</td>

<td>an F element child of an E element</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span> <span class="o">+</span> <span class="nt">F</span>`</td>

<td>an F element immediately preceded by an E element</td>

<td>2</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="o">[</span><span class="nt">foo</span><span class="o">^=</span><span class="s2">"bar"</span><span class="o">]</span>`</td>

<td>an E element whose "foo" attribute value begins exactly with the string "bar"</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="o">[</span><span class="nt">foo</span><span class="o">$=</span><span class="s2">"bar"</span><span class="o">]</span>`</td>

<td>an E element whose "foo" attribute value ends exactly with the string "bar"</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="o">[</span><span class="nt">foo</span><span class="o">*=</span><span class="s2">"bar"</span><span class="o">]</span>`</td>

<td>an E element whose "foo" attribute value contains the substring "bar"</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">root</span>`</td>

<td>an E element, root of the document</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">nth-child</span><span class="o">(</span><span class="nt">n</span><span class="o">)</span>`</td>

<td>an E element, the n-th child of its parent</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">nth-last-child</span><span class="o">(</span><span class="nt">n</span><span class="o">)</span>`</td>

<td>an E element, the n-th child of its parent, counting from the last one</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">nth-of-type</span><span class="o">(</span><span class="nt">n</span><span class="o">)</span>`</td>

<td>an E element, the n-th sibling of its type</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">nth-last-of-type</span><span class="o">(</span><span class="nt">n</span><span class="o">)</span>`</td>

<td>an E element, the n-th sibling of its type, counting from the last one</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">last-child</span>`</td>

<td>an E element, last child of its parent</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">first-of-type</span>`</td>

<td>an E element, first sibling of its type</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">last-of-type</span>`</td>

<td>an E element, last sibling of its type</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">only-child</span>`</td>

<td>an E element, only child of its parent</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">only-of-type</span>`</td>

<td>an E element, only sibling of its type</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">empty</span>`</td>

<td>an E element that has no children (including text nodes)</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">target</span>`</td>

<td>an E element being the target of the referring URI</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">enabled</span>`</td>

<td>a user interface element E that is enabled</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">disabled</span>`</td>

<td>a user interface element E that is disabled</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">checked</span>`</td>

<td>a user interface element E that is checked (for instance a radio-button or checkbox)</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span><span class="p">:</span><span class="nd">not</span><span class="o">(</span><span class="nt">s</span><span class="o">)</span>`</td>

<td>an E element that does not match simple selector s</td>

<td>3</td>

</tr>

<tr>

<td>`<span class="nt">E</span> <span class="o">~</span> <span class="nt">F</span>`</td>

<td>an F element preceded by an E element</td>

<td>3</td>

</tr>

</tbody>

</table>
