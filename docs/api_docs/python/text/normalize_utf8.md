<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="text.normalize_utf8" />
<meta itemprop="path" content="Stable" />
</div>

# text.normalize_utf8

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api" align="left">

</table>

<a target="_blank" href="https://github.com/tensorflow/text/tree/master/tensorflow_text/python/ops/normalize_ops.py">View
source</a>

Normalizes each UTF-8 string in the input tensor using the specified rule.

<pre class="devsite-click-to-copy prettyprint lang-py tfo-signature-link">
<code>text.normalize_utf8(
    input, normalization_form='NFKC', name=None
)
</code></pre>

<!-- Placeholder for "Used in" -->

See http://unicode.org/reports/tr15/

<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2"><h2 class="add-link">Args</h2></th></tr>

<tr>
<td>
`input`
</td>
<td>
A `Tensor` or `RaggedTensor` of type string. (Must be UTF-8.)
</td>
</tr><tr>
<td>
`normalization_form`
</td>
<td>
One of the following string values ('NFC', 'NFKC',
'NFD', 'NFKD'). Default is 'NFKC'.
</td>
</tr><tr>
<td>
`name`
</td>
<td>
The name for this op (optional).
</td>
</tr>
</table>

<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2"><h2 class="add-link">Returns</h2></th></tr>
<tr class="alt">
<td colspan="2">
A `Tensor` or `RaggedTensor` of type string, with normalized contents.
</td>
</tr>

</table>
