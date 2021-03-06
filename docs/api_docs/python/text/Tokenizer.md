<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="text.Tokenizer" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="__init__"/>
<meta itemprop="property" content="tokenize"/>
</div>

# text.Tokenizer

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api" align="left">

</table>

<a target="_blank" href="https://github.com/tensorflow/text/tree/master/tensorflow_text/python/ops/tokenization.py">View
source</a>

Base class for tokenizer implementations.

<pre class="devsite-click-to-copy prettyprint lang-py tfo-signature-link">
<code>text.Tokenizer(
    name=None
)
</code></pre>

<!-- Placeholder for "Used in" -->

## Methods

<h3 id="tokenize"><code>tokenize</code></h3>

<a target="_blank" href="https://github.com/tensorflow/text/tree/master/tensorflow_text/python/ops/tokenization.py">View
source</a>

<pre class="devsite-click-to-copy prettyprint lang-py tfo-signature-link">
<code>@abc.abstractmethod</code>
<code>tokenize(
    input
)
</code></pre>

Tokenizes the input tensor.

<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2">Args</th></tr>

<tr>
<td>
`input`
</td>
<td>
An N-dimensional UTF-8 string (or optionally integer) `Tensor` or
`RaggedTensor`.
</td>
</tr>
</table>

<!-- Tabular view -->
 <table class="responsive fixed orange">
<colgroup><col width="214px"><col></colgroup>
<tr><th colspan="2">Returns</th></tr>
<tr class="alt">
<td colspan="2">
An N+1-dimensional UTF-8 string or integer `Tensor` or `RaggedTensor`.
</td>
</tr>

</table>
