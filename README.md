# Markdown

> Investigating the limits of HTML and CSS in GitHub rendered Markdown.

HTML attributes:

<div>
	<div align="center">Beep</div>
	<div dir="rtl">Boop</div>
</div>

Manual spacing:

<div>
	<div>
		foo:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bar baz bop bap
	</div>
	<div>
		foo:<em hidden>........</em>bar baz bop bap
	</div>
	<div>
		bidazzle:&nbsp;&nbsp;&nbsp;bar baz bop bap
	</div>
	<div>
		biduzzle:<em hidden>...</em>bar baz bop bap
	</div>
	<div>
		foo:&#x2003;&#x2003;&#x2003;&#x2003;&#x2003;&#x2003;&#x2003;&#x2003;bar baz bop bap
	</div>
	<div>
		bidazzle:&#x2003;&#x2003;&#x2003;bar baz bop bap
	</div>
	<br>
	<br>
</div>

Definition list:

<dl>
	<dt>Beep</dt>
	<dd>Beep</dd>
	<dt>Boop</dt>
	<dd>Boop</dd>
</dl>

HTML table:

<table>
	<tbody>
		<tr>
			<td align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint( pt1[, pt2[, pt3[, ...]]] )</a></td>
			<td align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr>
			<td align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint( pt1[, pt2[, pt3[, ...]]] )</a></td>
			<td align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr>
			<td align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint( pt1[, pt2[, pt3[, ...]]] )</a></td>
			<td align="left">create a string from a sequence of Unicode code points</td>
		</tr>
	</tbody>
</table>

Another HTML table:

<table width="100%">
	<tbody>
		<tr>
			<td width="30%" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint( pt1[, pt2[, pt3[, ...]]] )</a></td>
			<td width="70%" align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr>
			<td width="30%" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint( pt1[, pt2[, pt3[, ...]]] )</a></td>
			<td width="70%" align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr>
			<td width="30%" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint( pt1[, pt2[, pt3[, ...]]] )</a></td>
			<td width="70%" align="left">create a string from a sequence of Unicode code points</td>
		</tr>
	</tbody>
</table>

Another HTML table:

<table width="100%">
	<tbody width="100%">
		<tr width="100%">
			<td width="30%" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point"><code>fromCodePoint()</code></a></td>
			<td width="70%" align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr width="100%">
			<td width="30%" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point"><code>fromCodePoint</code></a></td>
			<td width="70%" align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr width="100%">
			<td width="30%" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint()</a></td>
			<td width="70%" align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr width="100%">
			<td width="30%" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint</a></td>
			<td width="70%" align="left">create a string from a sequence of Unicode code points</td>
		</tr>
	</tbody>
</table>

Another HTML table:

<table width="100%">
	<tbody>
		<tr>
			<td width="200px" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point"><code>fromCodePoint()</code></a></td>
			<td align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr>
			<td width="200px" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point"><code>fromCodePoint</code></a></td>
			<td align="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr>
			<td width="200px" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint()</a></td>
			<tdalign="left">create a string from a sequence of Unicode code points</td>
		</tr>
		<tr>
			<td width="200px" align="left"><a href="https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point">fromCodePoint</a></td>
			<td align="left">create a string from a sequence of Unicode code points</td>
		</tr>
	</tbody>
</table>

Markdown table:

| function | description |
|:--- |:--- |
| [fromCodePoint( pt1\[, pt2\[, pt3\[, ...\]\]\] )](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point) | create a string from a sequence of Unicode code points |
| [`fromCodePoint( pt1[, pt2[, pt3[, ...]]] )`](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point) | create a string from a sequence of Unicode code points |
| [`fromCodePoint( pt1[, pt2[, pt3[, ...]]] )`](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point) | create a string from a sequence of Unicode code points |
| [fromCodePoint](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point)( pt1\[, pt2\[, pt3\[, ...]]] ) | create a string from a sequence of Unicode code points |
| [fromCodePoint](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point)() | create a string from a sequence of Unicode code points |
| [fromCodePoint](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point) | create a string from a sequence of Unicode code points |
| [`fromCodePoint()`](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point) | create a string from a sequence of Unicode code points |
| [`fromCodePoint`](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point) | create a string from a sequence of Unicode code points |
| [fromCodePoint](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/@stdlib/string/from-code-point) | create a string from a sequence of Unicode code points |