<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="" xml:lang="">
<head>
  <meta charset="utf-8" />
  <meta name="generator" content="pandoc" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
  <title>Apply a Style Until a Condition is Met with @while</title>
  <style>
    html {
      line-height: 1.5;
      font-family: Georgia, serif;
      font-size: 20px;
      color: #1a1a1a;
      background-color: #fdfdfd;
    }
    body {
      margin: 0 auto;
      max-width: 36em;
      padding-left: 50px;
      padding-right: 50px;
      padding-top: 50px;
      padding-bottom: 50px;
      hyphens: auto;
      word-wrap: break-word;
      text-rendering: optimizeLegibility;
      font-kerning: normal;
    }
    @media (max-width: 600px) {
      body {
        font-size: 0.9em;
        padding: 1em;
      }
    }
    @media print {
      body {
        background-color: transparent;
        color: black;
        font-size: 12pt;
      }
      p, h2, h3 {
        orphans: 3;
        widows: 3;
      }
      h2, h3, h4 {
        page-break-after: avoid;
      }
    }
    p {
      margin: 1em 0;
    }
    a {
      color: #1a1a1a;
    }
    a:visited {
      color: #1a1a1a;
    }
    img {
      max-width: 100%;
    }
    h1, h2, h3, h4, h5, h6 {
      margin-top: 1.4em;
    }
    h5, h6 {
      font-size: 1em;
      font-style: italic;
    }
    h6 {
      font-weight: normal;
    }
    ol, ul {
      padding-left: 1.7em;
      margin-top: 1em;
    }
    li > ol, li > ul {
      margin-top: 0;
    }
    blockquote {
      margin: 1em 0 1em 1.7em;
      padding-left: 1em;
      border-left: 2px solid #e6e6e6;
      color: #606060;
    }
    code {
      font-family: Menlo, Monaco, 'Lucida Console', Consolas, monospace;
      font-size: 85%;
      margin: 0;
    }
    pre {
      margin: 1em 0;
      overflow: auto;
    }
    pre code {
      padding: 0;
      overflow: visible;
    }
    .sourceCode {
     background-color: transparent;
     overflow: visible;
    }
    hr {
      background-color: #1a1a1a;
      border: none;
      height: 1px;
      margin: 1em 0;
    }
    table {
      margin: 1em 0;
      border-collapse: collapse;
      width: 100%;
      overflow-x: auto;
      display: block;
      font-variant-numeric: lining-nums tabular-nums;
    }
    table caption {
      margin-bottom: 0.75em;
    }
    tbody {
      margin-top: 0.5em;
      border-top: 1px solid #1a1a1a;
      border-bottom: 1px solid #1a1a1a;
    }
    th {
      border-top: 1px solid #1a1a1a;
      padding: 0.25em 0.5em 0.25em 0.5em;
    }
    td {
      padding: 0.125em 0.5em 0.25em 0.5em;
    }
    header {
      margin-bottom: 4em;
      text-align: center;
    }
    #TOC li {
      list-style: none;
    }
    #TOC a:not(:hover) {
      text-decoration: none;
    }
    code{white-space: pre-wrap;}
    span.smallcaps{font-variant: small-caps;}
    span.underline{text-decoration: underline;}
    div.column{display: inline-block; vertical-align: top; width: 50%;}
    div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
    ul.task-list{list-style: none;}
    pre > code.sourceCode { white-space: pre; position: relative; }
    pre > code.sourceCode > span { display: inline-block; line-height: 1.25; }
    pre > code.sourceCode > span:empty { height: 1.2em; }
    .sourceCode { overflow: visible; }
    code.sourceCode > span { color: inherit; text-decoration: inherit; }
    div.sourceCode { margin: 1em 0; }
    pre.sourceCode { margin: 0; }
    @media screen {
    div.sourceCode { overflow: auto; }
    }
    @media print {
    pre > code.sourceCode { white-space: pre-wrap; }
    pre > code.sourceCode > span { text-indent: -5em; padding-left: 5em; }
    }
    pre.numberSource code
      { counter-reset: source-line 0; }
    pre.numberSource code > span
      { position: relative; left: -4em; counter-increment: source-line; }
    pre.numberSource code > span > a:first-child::before
      { content: counter(source-line);
        position: relative; left: -1em; text-align: right; vertical-align: baseline;
        border: none; display: inline-block;
        -webkit-touch-callout: none; -webkit-user-select: none;
        -khtml-user-select: none; -moz-user-select: none;
        -ms-user-select: none; user-select: none;
        padding: 0 4px; width: 4em;
        color: #aaaaaa;
      }
    pre.numberSource { margin-left: 3em; border-left: 1px solid #aaaaaa;  padding-left: 4px; }
    div.sourceCode
      {   }
    @media screen {
    pre > code.sourceCode > span > a:first-child::before { text-decoration: underline; }
    }
    code span.al { color: #ff0000; font-weight: bold; } /* Alert */
    code span.an { color: #60a0b0; font-weight: bold; font-style: italic; } /* Annotation */
    code span.at { color: #7d9029; } /* Attribute */
    code span.bn { color: #40a070; } /* BaseN */
    code span.bu { } /* BuiltIn */
    code span.cf { color: #007020; font-weight: bold; } /* ControlFlow */
    code span.ch { color: #4070a0; } /* Char */
    code span.cn { color: #880000; } /* Constant */
    code span.co { color: #60a0b0; font-style: italic; } /* Comment */
    code span.cv { color: #60a0b0; font-weight: bold; font-style: italic; } /* CommentVar */
    code span.do { color: #ba2121; font-style: italic; } /* Documentation */
    code span.dt { color: #902000; } /* DataType */
    code span.dv { color: #40a070; } /* DecVal */
    code span.er { color: #ff0000; font-weight: bold; } /* Error */
    code span.ex { } /* Extension */
    code span.fl { color: #40a070; } /* Float */
    code span.fu { color: #06287e; } /* Function */
    code span.im { } /* Import */
    code span.in { color: #60a0b0; font-weight: bold; font-style: italic; } /* Information */
    code span.kw { color: #007020; font-weight: bold; } /* Keyword */
    code span.op { color: #666666; } /* Operator */
    code span.ot { color: #007020; } /* Other */
    code span.pp { color: #bc7a00; } /* Preprocessor */
    code span.sc { color: #4070a0; } /* SpecialChar */
    code span.ss { color: #bb6688; } /* SpecialString */
    code span.st { color: #4070a0; } /* String */
    code span.va { color: #19177c; } /* Variable */
    code span.vs { color: #4070a0; } /* VerbatimString */
    code span.wa { color: #60a0b0; font-weight: bold; font-style: italic; } /* Warning */
    .display.math{display: block; text-align: center; margin: 0.5rem auto;}
  </style>
  <!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js"></script>
  <![endif]-->
</head>
<body>
<header id="title-block-header">
<h1 class="title">Apply a Style Until a Condition is Met with <span class="citation" data-cites="while">@while</span></h1>
</header>
<h1 id="description">–description–</h1>
<p>The <code>@while</code> directive is an option with similar functionality to the JavaScript <code>while</code> loop. It creates CSS rules until a condition is met.</p>
<p>The <code>@for</code> challenge gave an example to create a simple grid system. This can also work with <code>@while</code>.</p>
<pre class="scss"><code>$x: 1;
@while $x &lt; 13 {
  .col-#{$x} { width: 100%/12 * $x;}
  $x: $x + 1;
}</code></pre>
<p>First, define a variable <code>$x</code> and set it to 1. Next, use the <code>@while</code> directive to create the grid system <em>while</em> <code>$x</code> is less than 13. After setting the CSS rule for <code>width</code>, <code>$x</code> is incremented by 1 to avoid an infinite loop.</p>
<h1 id="instructions">–instructions–</h1>
<p>Use <code>@while</code> to create a series of classes with different <code>font-sizes</code>.</p>
<p>There should be 5 different classes from <code>text-1</code> to <code>text-5</code>. Then set <code>font-size</code> to <code>15px</code> multiplied by the current index number. Make sure to avoid an infinite loop!</p>
<h1 id="hints">–hints–</h1>
<p>Your code should use the <code>@while</code> directive.</p>
<div class="sourceCode" id="cb2"><pre class="sourceCode js"><code class="sourceCode javascript"><span id="cb2-1"><a href="#cb2-1" aria-hidden="true" tabindex="-1"></a><span class="fu">assert</span>(code<span class="op">.</span><span class="fu">match</span>(<span class="ss">/@while /g</span>))<span class="op">;</span></span></code></pre></div>
<p>Your code should use an index variable which starts at an index of 1.</p>
<div class="sourceCode" id="cb3"><pre class="sourceCode js"><code class="sourceCode javascript"><span id="cb3-1"><a href="#cb3-1" aria-hidden="true" tabindex="-1"></a><span class="fu">assert</span>(code<span class="op">.</span><span class="fu">match</span>(<span class="ss">/</span><span class="sc">\$</span><span class="ss">.</span><span class="sc">*</span><span class="ss">:</span><span class="sc">\s*?</span><span class="ss">1;/gi</span>))<span class="op">;</span></span></code></pre></div>
<p>Your code should increment the counter variable.</p>
<div class="sourceCode" id="cb4"><pre class="sourceCode js"><code class="sourceCode javascript"><span id="cb4-1"><a href="#cb4-1" aria-hidden="true" tabindex="-1"></a><span class="fu">assert</span>(code<span class="op">.</span><span class="fu">match</span>(<span class="ss">/</span><span class="sc">\$(</span><span class="ss">.</span><span class="sc">*)\s*?</span><span class="ss">:</span><span class="sc">\s*\$\1\s*\+\s*</span><span class="ss">1</span><span class="sc">\s*</span><span class="ss">;/gi</span>))<span class="op">;</span></span></code></pre></div>
<p>Your <code>.text-1</code> class should have a <code>font-size</code> of 15px.</p>
<div class="sourceCode" id="cb5"><pre class="sourceCode js"><code class="sourceCode javascript"><span id="cb5-1"><a href="#cb5-1" aria-hidden="true" tabindex="-1"></a><span class="fu">assert</span>(<span class="fu">$</span>(<span class="st">&#39;.text-1&#39;</span>)<span class="op">.</span><span class="fu">css</span>(<span class="st">&#39;font-size&#39;</span>) <span class="op">==</span> <span class="st">&#39;15px&#39;</span>)<span class="op">;</span></span></code></pre></div>
<p>Your <code>.text-2</code> class should have a <code>font-size</code> of 30px.</p>
<div class="sourceCode" id="cb6"><pre class="sourceCode js"><code class="sourceCode javascript"><span id="cb6-1"><a href="#cb6-1" aria-hidden="true" tabindex="-1"></a><span class="fu">assert</span>(<span class="fu">$</span>(<span class="st">&#39;.text-2&#39;</span>)<span class="op">.</span><span class="fu">css</span>(<span class="st">&#39;font-size&#39;</span>) <span class="op">==</span> <span class="st">&#39;30px&#39;</span>)<span class="op">;</span></span></code></pre></div>
<p>Your <code>.text-3</code> class should have a <code>font-size</code> of 45px.</p>
<div class="sourceCode" id="cb7"><pre class="sourceCode js"><code class="sourceCode javascript"><span id="cb7-1"><a href="#cb7-1" aria-hidden="true" tabindex="-1"></a><span class="fu">assert</span>(<span class="fu">$</span>(<span class="st">&#39;.text-3&#39;</span>)<span class="op">.</span><span class="fu">css</span>(<span class="st">&#39;font-size&#39;</span>) <span class="op">==</span> <span class="st">&#39;45px&#39;</span>)<span class="op">;</span></span></code></pre></div>
<p>Your <code>.text-4</code> class should have a <code>font-size</code> of 60px.</p>
<div class="sourceCode" id="cb8"><pre class="sourceCode js"><code class="sourceCode javascript"><span id="cb8-1"><a href="#cb8-1" aria-hidden="true" tabindex="-1"></a><span class="fu">assert</span>(<span class="fu">$</span>(<span class="st">&#39;.text-4&#39;</span>)<span class="op">.</span><span class="fu">css</span>(<span class="st">&#39;font-size&#39;</span>) <span class="op">==</span> <span class="st">&#39;60px&#39;</span>)<span class="op">;</span></span></code></pre></div>
<p>Your <code>.text-5</code> class should have a <code>font-size</code> of 75px.</p>
<div class="sourceCode" id="cb9"><pre class="sourceCode js"><code class="sourceCode javascript"><span id="cb9-1"><a href="#cb9-1" aria-hidden="true" tabindex="-1"></a><span class="fu">assert</span>(<span class="fu">$</span>(<span class="st">&#39;.text-5&#39;</span>)<span class="op">.</span><span class="fu">css</span>(<span class="st">&#39;font-size&#39;</span>) <span class="op">==</span> <span class="st">&#39;75px&#39;</span>)<span class="op">;</span></span></code></pre></div>
<h1 id="seed">–seed–</h1>
<h2 id="seed-contents">–seed-contents–</h2>
<div class="sourceCode" id="cb10"><pre class="sourceCode html"><code class="sourceCode html"><span id="cb10-1"><a href="#cb10-1" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;style</span><span class="ot"> type=</span><span class="st">&#39;text/scss&#39;</span><span class="kw">&gt;</span></span>
<span id="cb10-2"><a href="#cb10-2" aria-hidden="true" tabindex="-1"></a></span>
<span id="cb10-3"><a href="#cb10-3" aria-hidden="true" tabindex="-1"></a></span>
<span id="cb10-4"><a href="#cb10-4" aria-hidden="true" tabindex="-1"></a></span>
<span id="cb10-5"><a href="#cb10-5" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;/style&gt;</span></span>
<span id="cb10-6"><a href="#cb10-6" aria-hidden="true" tabindex="-1"></a></span>
<span id="cb10-7"><a href="#cb10-7" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-1&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span>
<span id="cb10-8"><a href="#cb10-8" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-2&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span>
<span id="cb10-9"><a href="#cb10-9" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-3&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span>
<span id="cb10-10"><a href="#cb10-10" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-4&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span>
<span id="cb10-11"><a href="#cb10-11" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-5&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span></code></pre></div>
<h1 id="solutions">–solutions–</h1>
<div class="sourceCode" id="cb11"><pre class="sourceCode html"><code class="sourceCode html"><span id="cb11-1"><a href="#cb11-1" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;style</span><span class="ot"> type=</span><span class="st">&#39;text/scss&#39;</span><span class="kw">&gt;</span></span>
<span id="cb11-2"><a href="#cb11-2" aria-hidden="true" tabindex="-1"></a>  $x<span class="in">: 1;</span></span>
<span id="cb11-3"><a href="#cb11-3" aria-hidden="true" tabindex="-1"></a>  <span class="im">@while</span> $x &lt; <span class="dv">6</span> {</span>
<span id="cb11-4"><a href="#cb11-4" aria-hidden="true" tabindex="-1"></a>    <span class="fu">.text-</span>#{$x}{</span>
<span id="cb11-5"><a href="#cb11-5" aria-hidden="true" tabindex="-1"></a>      <span class="kw">font-size</span>: <span class="dv">15</span><span class="dt">px</span> * $x<span class="op">;</span></span>
<span id="cb11-6"><a href="#cb11-6" aria-hidden="true" tabindex="-1"></a>    }</span>
<span id="cb11-7"><a href="#cb11-7" aria-hidden="true" tabindex="-1"></a>    $x: $x + <span class="dv">1</span><span class="op">;</span></span>
<span id="cb11-8"><a href="#cb11-8" aria-hidden="true" tabindex="-1"></a>  }</span>
<span id="cb11-9"><a href="#cb11-9" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;/style&gt;</span></span>
<span id="cb11-10"><a href="#cb11-10" aria-hidden="true" tabindex="-1"></a></span>
<span id="cb11-11"><a href="#cb11-11" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-1&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span>
<span id="cb11-12"><a href="#cb11-12" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-2&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span>
<span id="cb11-13"><a href="#cb11-13" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-3&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span>
<span id="cb11-14"><a href="#cb11-14" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-4&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span>
<span id="cb11-15"><a href="#cb11-15" aria-hidden="true" tabindex="-1"></a><span class="kw">&lt;p</span><span class="ot"> class=</span><span class="st">&quot;text-5&quot;</span><span class="kw">&gt;</span>Hello<span class="kw">&lt;/p&gt;</span></span></code></pre></div>
</body>
</html>
