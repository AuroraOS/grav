---
title: sone
taxonomy:
    category:
        - docs
visible: true
---

<div class="bd-content">
          <div class="content">
  <p>
    There are several ways to <strong>get started</strong> with Bulma. You can either:
  </p>
  <ol>
    <li>
      use <strong>npm</strong> to install the Bulma package
    </li>
    <li>
      use the cdnjs <strong>CDN</strong> to link to the Bulma stylesheet
    </li>
    <li>
      use the <strong>GitHub repository</strong> to get the latest development version
    </li>
  </ol>
</div>

<article class="media is-large">
  <div class="media-left">
    <p class="title is-5">1</p>
  </div>
  <div class="media-content">
    <p class="title is-5">
      Use <strong>NPM</strong> <em>(recommended)</em>:
    </p>
    <figure class="highlight"><pre><code class="language-bash" data-lang="bash">npm install bulma</code></pre><button class="button is-small bd-copy">Copy</button></figure>
  </div>
</article>

<article class="media is-large">
  <div class="media-left">
    <p class="title is-5">2</p>
  </div>
  <div class="media-content">
    <p class="title is-5">
      Use the <a href="https://cdnjs.com/" target="_blank">cdnjs</a> <strong>CDN</strong>
      <br>
      <a href="https://cdnjs.com/libraries/bulma">https://cdnjs.com/libraries/bulma</a>
    </p>
  </div>
</article>

<article class="media is-large">
  <div class="media-left">
    <p class="title is-5">3</p>
  </div>
  <div class="media-content">
    <p class="title is-5">
      Download from the <strong>repository</strong>
      <br>
      <a href="https://github.com/jgthms/bulma/tree/master/css">https://github.com/jgthms/bulma/tree/master/css</a>
    </p>
  </div>
</article>

<hr>

<div class="message is-info">
  <div class="message-header">
    Font Awesome icons
  </div>
  <div class="message-body">
    <p>If you want to use icons with Bulma, don't forget to include <a href="https://fontawesome.com">Font Awesome 5</a>:</p>
    <figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;script </span><span class="na">defer</span> <span class="na">src=</span><span class="s">"https://use.fontawesome.com/releases/v5.3.1/js/all.js"</span><span class="nt">&gt;&lt;/script&gt;</span></code></pre><button class="button is-small bd-copy">Copy</button></figure>
  </div>
</div>

<hr class="hr" style="margin-bottom: 0;">

<h3 id="code-requirements" class="title is-4 is-spaced bd-anchor-title">
  <span class="bd-anchor-name">
    Code requirements
  </span>
  <a class="bd-anchor-link" href="#code-requirements">
    #
  </a>
</h3>


<div class="content">
  <p>
    For Bulma to work correctly, you need to make your webpage <strong>responsive</strong>.
  </p>
</div>

<article class="media is-large">
  <div class="media-left">
    <p class="title is-5">1</p>
  </div>
  <div class="media-content">
    <p class="title is-5">
      Use the <strong>HTML5 doctype</strong>
    </p>
    <figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="cp">&lt;!DOCTYPE html&gt;</span></code></pre><button class="button is-small bd-copy">Copy</button></figure>
  </div>
</article>

<article class="media is-large">
  <div class="media-left">
    <p class="title is-5">2</p>
  </div>
  <div class="media-content">
    <p class="title is-5">
      Add the responsive <strong>viewport</strong> meta tag
    </p>
    <figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;meta</span> <span class="na">name=</span><span class="s">"viewport"</span> <span class="na">content=</span><span class="s">"width=device-width, initial-scale=1"</span><span class="nt">&gt;</span></code></pre><button class="button is-small bd-copy">Copy</button></figure>
  </div>
</article>

<hr class="hr" style="margin-bottom: 0;">

<h3 id="starter-template" class="title is-4 is-spaced bd-anchor-title">
  <span class="bd-anchor-name">
    Starter template
  </span>
  <a class="bd-anchor-link" href="#starter-template">
    #
  </a>
</h3>


<div class="content">
  <p>
    If you want to get started <strong>right away</strong>, you can use this <strong>HTML starter template</strong>. Just copy/paste this code in a file and save it on your computer.
  </p>
</div>

<div class="bd-example highlight-full">
  <figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="cp">&lt;!DOCTYPE html&gt;</span>
<span class="nt">&lt;html&gt;</span>
  <span class="nt">&lt;head&gt;</span>
    <span class="nt">&lt;meta</span> <span class="na">charset=</span><span class="s">"utf-8"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;meta</span> <span class="na">name=</span><span class="s">"viewport"</span> <span class="na">content=</span><span class="s">"width=device-width, initial-scale=1"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;title&gt;</span>Hello Bulma!<span class="nt">&lt;/title&gt;</span>
    <span class="nt">&lt;link</span> <span class="na">rel=</span><span class="s">"stylesheet"</span> <span class="na">href=</span><span class="s">"https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.2/css/bulma.min.css"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;script </span><span class="na">defer</span> <span class="na">src=</span><span class="s">"https://use.fontawesome.com/releases/v5.3.1/js/all.js"</span><span class="nt">&gt;&lt;/script&gt;</span>
  <span class="nt">&lt;/head&gt;</span>
  <span class="nt">&lt;body&gt;</span>
  <span class="nt">&lt;section</span> <span class="na">class=</span><span class="s">"section"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"container"</span><span class="nt">&gt;</span>
      <span class="nt">&lt;h1</span> <span class="na">class=</span><span class="s">"title"</span><span class="nt">&gt;</span>
        Hello World
      <span class="nt">&lt;/h1&gt;</span>
      <span class="nt">&lt;p</span> <span class="na">class=</span><span class="s">"subtitle"</span><span class="nt">&gt;</span>
        My first website with <span class="nt">&lt;strong&gt;</span>Bulma<span class="nt">&lt;/strong&gt;</span>!
      <span class="nt">&lt;/p&gt;</span>
    <span class="nt">&lt;/div&gt;</span>
  <span class="nt">&lt;/section&gt;</span>
  <span class="nt">&lt;/body&gt;</span>
<span class="nt">&lt;/html&gt;</span></code></pre><button class="button is-small bd-copy">Copy</button></figure>
</div>

<hr class="hr" style="margin-bottom: 0;">

<h3 id="bulma-start" class="title is-4 is-spaced bd-anchor-title">
  <span class="bd-anchor-name">
    bulma-start
  </span>
  <a class="bd-anchor-link" href="#bulma-start">
    #
  </a>
</h3>


<div class="content">
  <p>
    <code><a href="https://bulma.io/bulma-start/">bulma-start</a></code> is a tiny npm package that includes the <code>npm</code> dependencies you need to build your own website with Bulma.
  </p>
  <p>
    <a class="button is-link" href="https://bulma.io/bulma-start/">Check it out</a>
  </p>
</div>

        </div>