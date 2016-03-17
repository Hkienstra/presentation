<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="generator" content="pandoc">
  <title></title>
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, minimal-ui">
  <link rel="stylesheet" href="reveal.js/css/reveal.css">
  <style type="text/css">code{white-space: pre;}</style>
  <link rel="stylesheet" href="reveal.js/css/theme/solarized.css" id="theme">
  <!-- Printing and PDF exports -->
  <script>
    var link = document.createElement( 'link' );
    link.rel = 'stylesheet';
    link.type = 'text/css';
    link.href = window.location.search.match( /print-pdf/gi ) ? 'reveal.js/css/print/pdf.css' : 'reveal.js/css/print/paper.css';
    document.getElementsByTagName( 'head' )[0].appendChild( link );
  </script>
  <!--[if lt IE 9]>
  <script src="reveal.js/lib/js/html5shiv.js"></script>
  <![endif]-->
</head>
<body>
  <div class="reveal">
    <div class="slides">


<section class="slide level2">

<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"> <meta name="generator" content="pandoc"> <meta name="author" content="Assignment 1">
<title>
Game Theory 2
</title>
<meta name="apple-mobile-web-app-capable" content="yes"> <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent"> <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, minimal-ui"> <link rel="stylesheet" href="reveal.js/css/reveal.css">
<style type="text/css">code{white-space: pre;}</style>
<link rel="stylesheet" href="reveal.js/css/theme/solarized.css" id="theme"> <!-- Printing and PDF exports -->
<script>
    var link = document.createElement( 'link' );
    link.rel = 'stylesheet';
    link.type = 'text/css';
    link.href = window.location.search.match( /print-pdf/gi ) ? 'reveal.js/css/print/pdf.css' : 'reveal.js/css/print/paper.css';
    document.getElementsByTagName( 'head' )[0].appendChild( link );
  </script>
<!--[if lt IE 9]>
  <script src="reveal.js/lib/js/html5shiv.js"></script>
  <![endif]-->
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
</head>
<body>
<div class="reveal">
<pre><code>&lt;div class=&quot;slides&quot;&gt;</code></pre>
<section>
<h1 class="title">
Game Theory 2
</h1>
<h2 class="author">
Assignment 1
</h2>
<h3 class="date">
Hidde Kienstra (902873), Tilburg University
</h3>
</section>
<section id="TOC">
<ul>
<li>
<a href="#/section">1.1</a>
</li>
<li>
<a href="#/section-1">1.2</a>
</li>
<li>
<a href="#/section-2">1.3</a>
</li>
</ul>
</section>
<section>
<section id="section" class="titleslide slide level1">
<h1>
1.1
</h1>
</section>
<section id="a" class="slide level2">
<h1>
a)
</h1>
<p>
A has 1 type. Types of T are different firm values (x) distributed over [0.1].
</p>
<p>
<span class="math inline">(A_A)</span> bids Y to take over T, Y distributed over [0, <span class="math inline">()</span>].
</p>
<p>
<span class="math inline">(A_T)</span>= reject or accept Y
</p>
<p>
T will only accept Y if <span class="math display">[YX]</span>
</p>
</section>
<section class="slide level2">
<p>
A beliefs X is drawn from CDF <span class="math inline">(F(X)=X(2-X))</span>, T knows own X
</p>
<p>
Strategy A: Bid <span class="math display">[Y [0, {}]]</span>
</p>
<p>
Strategy T: to accept or reject Y <span class="math inline">()</span> T only accepts if: <span class="math display">[YX]</span>
</p>
<p>
<em>Pay offs:</em> <span class="math display">[U_A(Y, Accept)=2X-Y]</span> <span class="math display">[U_A(Y, Reject)=0]</span> <span class="math display">[U_T(Y, Accept)=Y]</span> <span class="math display">[U_T(Y, Reject)=X]</span>
</p>
</section>
<section id="b" class="slide level2">
<h1>
b)
</h1>
<p>
<span class="math display">[E(X)= ^{}_{-} x *f(x) , dx ]</span>
</p>
<p>
<span class="math display">[F(X)=X(2-X)=X^2+2X]</span>
</p>
<p>
<span class="math display">[f(X)=F'=-2x+2]</span>
</p>
<p>
<span class="math display">[E(X)=_{0}^{1} x(-2x+2) dx ]</span>
</p>
</section>
<section class="slide level2">
<p>
<span class="math display">[=_{0}^{1} -2x^2+2 dx= ]</span>
</p>
<p>
<span class="math display">[=X<sup>3+X</sup>2]</span>
</p>
<p>
<span class="math display">[=*1+1^2=]</span>
</p>
</section>
<section id="c" class="slide level2">
<h1>
c)
</h1>
<p>
Firm value is distributed over <span class="math display">[[0.1]]</span>
</p>
<p>
T will only accept Y if: <span class="math display">[YX]</span> A can bid below or higher than 1, if bid is equal or higher than 1 T will always accept (max firm value=1)
</p>
<p>
<span class="math display">[E(X|XY)]</span> is the expected X of firm that accepts Y.
</p>
<p>
<span class="math display">[E(X|XY)=]</span>
</p>
</section>
<section class="slide level2">
<p>
<span class="math display">[f(x)=-2x+2]</span>
</p>
<p>
<span class="math display">[=_{0}^{Y} x(-2x+2) dx= ]</span>
</p>
<p>
<span class="math display">[=_{0}^{Y} (-2x^2+2) dx= ]</span>
</p>
<p>
<span class="math display">[=[X<sup>3+X</sup>2]^{X=Y}_{X=0}]</span>
</p>
<p>
<span class="math display">[=Y<sup>3+Y</sup>2]</span>
</p>
<p>
<span class="math display">[F(Y)=Y(2-Y)]</span>
</p>
<p>
<span class="math display">[E(X|XY)= ]</span>
</p>
</section>
<section class="slide level2">
<p>
The expected value of a firm if it accepts is <span class="math display">[= E(X|XY)= ]</span> if <span class="math inline">(Y1)</span>, if <span class="math inline">(Y1)</span> all types will accept, expected value of all types is <span class="math display">[]</span>
</p>
<p>
Pay off A if <span class="math inline">(Y1:)</span> <span class="math display">[= 2x-Y=2( )-Y]</span>
</p>
</section>
<section class="slide level2">
<p>
which is <span class="math inline">(0)</span> on interval [0,1].
</p>
<p>
Payoff A if <span class="math inline">(Y1)</span> <span class="math display">[=2*-Y0]</span>
</p>
<p>
Nash equilibrium is for A to bid 0.
</p>
</section>
<section id="d" class="slide level2">
<h1>
d)
</h1>
<p>
A can generate profit from buying T, because it values it higher than T's own management does. However T only accepts bids above own value, on average as you lower bid the probability that target firm has good value decreases, creating an adverse selection problem.
</p>
</section>
</section>
<section>
<section id="section-1" class="titleslide slide level1">
<h1>
1.2
</h1>
</section>
<section id="a-1" class="slide level2">
<h1>
a)
</h1>
<p>
<span class="math display">[_1'(L) q_1(L) ]</span>
</p>
<p>
<span class="math display">[_1'(H) q_1(H)= ]</span>
</p>
<p>
<span class="math display">[_1'(L) q_2(L) ]</span>
</p>
<p>
<span class="math display">[_2'(H) q_2(H)= ]</span>
</p>
</section>
<section id="b-1" class="slide level2">
<h1>
b)
</h1>
<p>
A strategy for i is how much to produce given that j is expected to certain Q, determined wheter it has low cost or high cost.
</p>
</section>
<section id="c-1" class="slide level2">
<h1>
c)
</h1>
<p>
Assuming symmetry of firm 1 &amp; 2 <span class="math inline">(q_1(L)=q_2(L))</span>
</p>
<p>
and
</p>
<p>
<span class="math inline">(q_1(H)=q_2(H))</span><br /> <span class="math display">[q(L)=]</span> <span class="math display">[q(H)=]</span>
</p>
</section>
</section>
<section>
<section id="section-2" class="titleslide slide level1">
<h1>
1.3
</h1>
</section>
<section id="a-2" class="slide level2">
<h1>
a)
</h1>
<figure>
<img src="Schermafbeelding.png" />
</figure>
</section>
<section id="b-2" class="slide level2">
<h1>
b)
</h1>
<p>
With k=0.5 the game is a prisoners dilemma with the pure strategy Nash equilibrium (Fight, Fight).
</p>
<p>
With k=2 the game is a type of coordination game which is called chicken game. This game has two pure strategy Nash equilibria which are (Fight,Accomodate) and (Accomodate,Fight).
</p>
</section>
<section id="c-2" class="slide level2">
<h1>
c)
</h1>
<p>
Type: <span class="math display">[_1=(k=0.5,k=2)]</span> <span class="math display">[_2=(k=0.5p,k=2(1-p))]</span> Action: <span class="math display">[A={Accomodate,Fight}]</span>
</p>
</section>
</section>
<pre><code>&lt;/div&gt;</code></pre>
</div>
<script src="reveal.js/lib/js/head.min.js"></script>
<script src="reveal.js/js/reveal.js"></script>
<script>

      // Full list of configuration options available at:
      // https://github.com/hakimel/reveal.js#configuration
      Reveal.initialize({

        // Optional reveal.js plugins
        dependencies: [
          { src: 'reveal.js/lib/js/classList.js', condition: function() { return !document.body.classList; } },
          { src: 'reveal.js/plugin/zoom-js/zoom.js', async: true },
          { src: 'reveal.js/plugin/notes/notes.js', async: true }
        ]
      });
    </script>
<pre><code>&lt;/body&gt;</code></pre>
</html>
</section>
    </div>
  </div>

  <script src="reveal.js/lib/js/head.min.js"></script>
  <script src="reveal.js/js/reveal.js"></script>

  <script>

      // Full list of configuration options available at:
      // https://github.com/hakimel/reveal.js#configuration
      Reveal.initialize({

        // Optional reveal.js plugins
        dependencies: [
          { src: 'reveal.js/lib/js/classList.js', condition: function() { return !document.body.classList; } },
          { src: 'reveal.js/plugin/zoom-js/zoom.js', async: true },
          { src: 'reveal.js/plugin/notes/notes.js', async: true }
        ]
      });
    </script>
    </body>
</html>
