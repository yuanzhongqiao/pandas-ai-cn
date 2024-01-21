# PandasAI  跟你的数据聊聊天 🐼

[![Release](https://img.shields.io/pypi/v/pandasai?label=Release&style=flat-square)](https://pypi.org/project/pandasai/)
[![CI](https://github.com/gventuri/pandas-ai/actions/workflows/ci.yml/badge.svg)](https://github.com/gventuri/pandas-ai/actions/workflows/ci.yml/badge.svg)
[![CD](https://github.com/gventuri/pandas-ai/actions/workflows/cd.yml/badge.svg)](https://github.com/gventuri/pandas-ai/actions/workflows/cd.yml/badge.svg)
[![Coverage](https://codecov.io/gh/gventuri/pandas-ai/branch/main/graph/badge.svg)](https://codecov.io/gh/gventuri/pandas-ai)
[![Documentation Status](https://readthedocs.org/projects/pandas-ai/badge/?version=latest)](https://pandas-ai.readthedocs.io/en/latest/?badge=latest)
[![Discord](https://dcbadge.vercel.app/api/server/kF7FqH2FwS?style=flat&compact=true)](https://discord.gg/kF7FqH2FwS)
[![Downloads](https://static.pepy.tech/badge/pandasai)](https://pepy.tech/project/pandasai) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open in Colab](https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1ZnO-njhL7TBOYPZaqvMvGtsjckZKrv2E?usp=sharing)

PandasAI 是 一个拥有chaGPT能力的的Python 库，结合 [pandas](https://github.com/pandas-dev/pandas), 和你的数据聊聊天，那几个数比较大？

<!-- Add images/pandas-ai.png -->

![PandasAI](images/pandas-ai.png?raw=true)

 

<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-pandasai-" class="anchor" aria-hidden="true" tabindex="-1" href="#pandasai-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">熊猫人工智能🐼</font></font></h1>
<p dir="auto"><a href="https://pypi.org/project/pandasai/" rel="nofollow"><img src="https://camo.githubusercontent.com/d768e74f543b372c07fd64ba058dcb6679d5d72c440a16f2b32419fd6c7db806/68747470733a2f2f696d672e736869656c64732e696f2f707970692f762f70616e64617361693f6c6162656c3d52656c65617365267374796c653d666c61742d737175617265" alt="发布" data-canonical-src="https://img.shields.io/pypi/v/pandasai?label=Release&amp;style=flat-square" style="max-width: 100%;"></a>
<a href="https://github.com/gventuri/pandas-ai/actions/workflows/ci.yml/badge.svg"><img src="https://github.com/gventuri/pandas-ai/actions/workflows/ci.yml/badge.svg" alt="CI" style="max-width: 100%;"></a>
<a href="https://github.com/gventuri/pandas-ai/actions/workflows/cd.yml/badge.svg"><img src="https://github.com/gventuri/pandas-ai/actions/workflows/cd.yml/badge.svg" alt="光盘" style="max-width: 100%;"></a>
<a href="https://codecov.io/gh/gventuri/pandas-ai" rel="nofollow"><img src="https://camo.githubusercontent.com/658b9b0b32c1d6db544150ae23d5345653cbcae2496f528d2eecabcc35389aeb/68747470733a2f2f636f6465636f762e696f2f67682f6776656e747572692f70616e6461732d61692f6272616e63682f6d61696e2f67726170682f62616467652e737667" alt="覆盖范围" data-canonical-src="https://codecov.io/gh/gventuri/pandas-ai/branch/main/graph/badge.svg" style="max-width: 100%;"></a>
<a href="https://pandas-ai.readthedocs.io/en/latest/?badge=latest" rel="nofollow"><img src="https://camo.githubusercontent.com/5155a96ff7373da019747bb3d5972b5f645c377c034d8a35d7219af83adcfb82/68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f70616e6461732d61692f62616467652f3f76657273696f6e3d6c6174657374" alt="文件状态" data-canonical-src="https://readthedocs.org/projects/pandas-ai/badge/?version=latest" style="max-width: 100%;"></a>
<a href="https://discord.gg/kF7FqH2FwS" rel="nofollow"><img src="https://camo.githubusercontent.com/1a93ace8b0d2d3f9db3920f6c854f04afede7722052d2ee88ef39b94c9be7d32/68747470733a2f2f646362616467652e76657263656c2e6170702f6170692f7365727665722f6b4637467148324677533f7374796c653d666c617426636f6d706163743d74727565" alt="不和谐" data-canonical-src="https://dcbadge.vercel.app/api/server/kF7FqH2FwS?style=flat&amp;compact=true" style="max-width: 100%;"></a>
<a href="https://pepy.tech/project/pandasai" rel="nofollow"><img src="https://camo.githubusercontent.com/5ea7f4c91371fc08d7674413ed26cee2cae4c9d3ee2544062249faec0ef6b5ec/68747470733a2f2f7374617469632e706570792e746563682f62616467652f70616e6461736169" alt="下载" data-canonical-src="https://static.pepy.tech/badge/pandasai" style="max-width: 100%;"></a> <a href="https://opensource.org/licenses/MIT" rel="nofollow"><img src="https://camo.githubusercontent.com/a4426cbe5c21edb002526331c7a8fbfa089e84a550567b02a0d829a98b136ad0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d79656c6c6f772e737667" alt="许可证：麻省理工学院" data-canonical-src="https://img.shields.io/badge/License-MIT-yellow.svg" style="max-width: 100%;"></a>
<a href="https://colab.research.google.com/drive/1ZnO-njhL7TBOYPZaqvMvGtsjckZKrv2E?usp=sharing" rel="nofollow"><img src="https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PandasAI 是一个 Python 库，它为流行的数据分析和操作工具</font></font><a href="https://github.com/pandas-dev/pandas"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pandas</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">添加了生成式 AI 功能。</font><font style="vertical-align: inherit;">它被设计为与 pandas 结合使用，而不是它的替代品。</font></font></p>

<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/gventuri/pandas-ai/blob/main/images/pandas-ai.png?raw=true"><img src="/gventuri/pandas-ai/raw/main/images/pandas-ai.png?raw=true" alt="熊猫人工智能" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--quick-install" class="anchor" aria-hidden="true" tabindex="-1" href="#-quick-install"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔧 快速安装</font></font></h2>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install pandasai</pre><div class="zeroclipboard-container">
 
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content--demo" class="anchor" aria-hidden="true" tabindex="-1" href="#-demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔍 演示</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在浏览器中尝试 PandasAI：</font></font></p>
<p dir="auto"><a href="https://colab.research.google.com/drive/1ZnO-njhL7TBOYPZaqvMvGtsjckZKrv2E?usp=sharing" rel="nofollow"><img src="https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="在 Colab 中打开" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--documentation" class="anchor" aria-hidden="true" tabindex="-1" href="#-documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📖 文档</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PandasAI 的文档可以</font></font><a href="https://pandas-ai.readthedocs.io/en/latest/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--usage" class="anchor" aria-hidden="true" tabindex="-1" href="#-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">💻 用法</font></font></h2>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://ourworldindata.org/grapher/gross-domestic-product?tab=table" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免责声明：GDP 数据从此来源</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">收集</font><font style="vertical-align: inherit;">，由世界发展指标 - 世界银行 (2022.05.26) 发布，并收集于国民账户数据 - 世界银行/经济合作与发展组织。</font><font style="vertical-align: inherit;">它与2020年有关。幸福指数摘自</font></font><a href="https://ftnnews.com/images/stories/documents/2020/WHR20.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">《世界幸福报告》</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">另一个有用的</font></font><a href="https://data.world/makeovermonday/2020w19-world-happiness-report-2020" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PandasAI 旨在与 pandas 结合使用。</font><font style="vertical-align: inherit;">它使 pandas 具有对话性，允许您用自然语言向数据提出问题。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-queries" class="anchor" aria-hidden="true" tabindex="-1" href="#queries"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查询</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，您可以要求 PandasAI 查找 DataFrame 中某列值大于 5 的所有行，并且它将返回仅包含这些行的 DataFrame：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">pandas</span> <span class="pl-k">as</span> <span class="pl-s1">pd</span>
<span class="pl-k">from</span> <span class="pl-s1">pandasai</span> <span class="pl-k">import</span> <span class="pl-v">SmartDataframe</span>

<span class="pl-c"># Sample DataFrame</span>
<span class="pl-s1">df</span> <span class="pl-c1">=</span> <span class="pl-s1">pd</span>.<span class="pl-v">DataFrame</span>({
    <span class="pl-s">"country"</span>: [<span class="pl-s">"United States"</span>, <span class="pl-s">"United Kingdom"</span>, <span class="pl-s">"France"</span>, <span class="pl-s">"Germany"</span>, <span class="pl-s">"Italy"</span>, <span class="pl-s">"Spain"</span>, <span class="pl-s">"Canada"</span>, <span class="pl-s">"Australia"</span>, <span class="pl-s">"Japan"</span>, <span class="pl-s">"China"</span>],
    <span class="pl-s">"gdp"</span>: [<span class="pl-c1">19294482071552</span>, <span class="pl-c1">2891615567872</span>, <span class="pl-c1">2411255037952</span>, <span class="pl-c1">3435817336832</span>, <span class="pl-c1">1745433788416</span>, <span class="pl-c1">1181205135360</span>, <span class="pl-c1">1607402389504</span>, <span class="pl-c1">1490967855104</span>, <span class="pl-c1">4380756541440</span>, <span class="pl-c1">14631844184064</span>],
    <span class="pl-s">"happiness_index"</span>: [<span class="pl-c1">6.94</span>, <span class="pl-c1">7.16</span>, <span class="pl-c1">6.66</span>, <span class="pl-c1">7.07</span>, <span class="pl-c1">6.38</span>, <span class="pl-c1">6.4</span>, <span class="pl-c1">7.23</span>, <span class="pl-c1">7.22</span>, <span class="pl-c1">5.87</span>, <span class="pl-c1">5.12</span>]
})

<span class="pl-c"># Instantiate a LLM</span>
<span class="pl-k">from</span> <span class="pl-s1">pandasai</span>.<span class="pl-s1">llm</span> <span class="pl-k">import</span> <span class="pl-v">OpenAI</span>
<span class="pl-s1">llm</span> <span class="pl-c1">=</span> <span class="pl-v">OpenAI</span>(<span class="pl-s1">api_token</span><span class="pl-c1">=</span><span class="pl-s">"YOUR_API_TOKEN"</span>)

<span class="pl-s1">df</span> <span class="pl-c1">=</span> <span class="pl-v">SmartDataframe</span>(<span class="pl-s1">df</span>, <span class="pl-s1">config</span><span class="pl-c1">=</span>{<span class="pl-s">"llm"</span>: <span class="pl-s1">llm</span>})
<span class="pl-s1">df</span>.<span class="pl-en">chat</span>(<span class="pl-s">'Which are the 5 happiest countries?'</span>)</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上面的代码将返回以下内容：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>6            Canada
7         Australia
1    United Kingdom
3           Germany
0     United States
Name: country, dtype: object
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="6            Canada
7         Australia
1    United Kingdom
3           Germany
0     United States
Name: country, dtype: object" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当然，您也可以要求 PandasAI 执行更复杂的查询。</font><font style="vertical-align: inherit;">例如，您可以要求 PandasAI 计算 2 个最不幸福国家的 GDP 总和：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">df</span>.<span class="pl-en">chat</span>(<span class="pl-s">'What is the sum of the GDPs of the 2 unhappiest countries?'</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="df.chat('What is the sum of the GDPs of the 2 unhappiest countries?')" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上面的代码将返回以下内容：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>19012600725504
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="19012600725504" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-charts" class="anchor" aria-hidden="true" tabindex="-1" href="#charts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图表</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以要求 PandasAI 绘制图表：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">df</span>.<span class="pl-en">chat</span>(
    <span class="pl-s">"Plot the histogram of countries showing for each the gdp, using different colors for each bar"</span>,
)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="df.chat(
    &quot;Plot the histogram of countries showing for each the gdp, using different colors for each bar&quot;,
)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/gventuri/pandas-ai/blob/main/images/histogram-chart.png?raw=true"><img src="/gventuri/pandas-ai/raw/main/images/histogram-chart.png?raw=true" alt="图表" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过在构造函数中将</font></font><code>save_charts</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数设置为 来</font><font style="vertical-align: inherit;">保存 PandasAI 生成的任何图表</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">例如，</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">图表保存在</font><font style="vertical-align: inherit;">.</font></font><code>True</code><font style="vertical-align: inherit;"></font><code>PandasAI</code><font style="vertical-align: inherit;"></font><code>PandasAI(llm, save_charts=True)</code><font style="vertical-align: inherit;"></font><code>./pandasai/exports/charts</code><font style="vertical-align: inherit;"></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-multiple-dataframes" class="anchor" aria-hidden="true" tabindex="-1" href="#multiple-dataframes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多个数据框</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此外，您还可以将多个数据帧传递给 PandasAI 并提出与它们相关的问题。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">pandas</span> <span class="pl-k">as</span> <span class="pl-s1">pd</span>
<span class="pl-k">from</span> <span class="pl-s1">pandasai</span> <span class="pl-k">import</span> <span class="pl-v">SmartDatalake</span>
<span class="pl-k">from</span> <span class="pl-s1">pandasai</span>.<span class="pl-s1">llm</span> <span class="pl-k">import</span> <span class="pl-v">OpenAI</span>

<span class="pl-s1">employees_data</span> <span class="pl-c1">=</span> {
    <span class="pl-s">'EmployeeID'</span>: [<span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">4</span>, <span class="pl-c1">5</span>],
    <span class="pl-s">'Name'</span>: [<span class="pl-s">'John'</span>, <span class="pl-s">'Emma'</span>, <span class="pl-s">'Liam'</span>, <span class="pl-s">'Olivia'</span>, <span class="pl-s">'William'</span>],
    <span class="pl-s">'Department'</span>: [<span class="pl-s">'HR'</span>, <span class="pl-s">'Sales'</span>, <span class="pl-s">'IT'</span>, <span class="pl-s">'Marketing'</span>, <span class="pl-s">'Finance'</span>]
}

<span class="pl-s1">salaries_data</span> <span class="pl-c1">=</span> {
    <span class="pl-s">'EmployeeID'</span>: [<span class="pl-c1">1</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">4</span>, <span class="pl-c1">5</span>],
    <span class="pl-s">'Salary'</span>: [<span class="pl-c1">5000</span>, <span class="pl-c1">6000</span>, <span class="pl-c1">4500</span>, <span class="pl-c1">7000</span>, <span class="pl-c1">5500</span>]
}

<span class="pl-s1">employees_df</span> <span class="pl-c1">=</span> <span class="pl-s1">pd</span>.<span class="pl-v">DataFrame</span>(<span class="pl-s1">employees_data</span>)
<span class="pl-s1">salaries_df</span> <span class="pl-c1">=</span> <span class="pl-s1">pd</span>.<span class="pl-v">DataFrame</span>(<span class="pl-s1">salaries_data</span>)


<span class="pl-s1">llm</span> <span class="pl-c1">=</span> <span class="pl-v">OpenAI</span>()
<span class="pl-s1">dl</span> <span class="pl-c1">=</span> <span class="pl-v">SmartDatalake</span>([<span class="pl-s1">employees_df</span>, <span class="pl-s1">salaries_df</span>], <span class="pl-s1">config</span><span class="pl-c1">=</span>{<span class="pl-s">"llm"</span>: <span class="pl-s1">llm</span>})
<span class="pl-s1">dl</span>.<span class="pl-en">chat</span>(<span class="pl-s">"Who gets paid the most?"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import pandas as pd
from pandasai import SmartDatalake
from pandasai.llm import OpenAI

employees_data = {
    'EmployeeID': [1, 2, 3, 4, 5],
    'Name': ['John', 'Emma', 'Liam', 'Olivia', 'William'],
    'Department': ['HR', 'Sales', 'IT', 'Marketing', 'Finance']
}

salaries_data = {
    'EmployeeID': [1, 2, 3, 4, 5],
    'Salary': [5000, 6000, 4500, 7000, 5500]
}

employees_df = pd.DataFrame(employees_data)
salaries_df = pd.DataFrame(salaries_data)


llm = OpenAI()
dl = SmartDatalake([employees_df, salaries_df], config={&quot;llm&quot;: llm})
dl.chat(&quot;Who gets paid the most?&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上面的代码将返回以下内容：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Oh, Olivia gets paid the most.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Oh, Olivia gets paid the most." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/gventuri/pandas-ai/blob/main/examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录中找到更多示例</font><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-️-shortcuts" class="anchor" aria-hidden="true" tabindex="-1" href="#️-shortcuts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚡️ 快捷方式</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PandasAI 还提供了许多快捷方式（测试版），以便更轻松地向您的数据提出问题。</font><font style="vertical-align: inherit;">例如，您可以要求 PandasAI </font></font><code>clean_data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>impute_missing_values</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>generate_features</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>plot_histogram</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等等。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"># Clean data</span>
<span class="pl-s1">df</span>.<span class="pl-en">clean_data</span>()

<span class="pl-c"># Impute missing values</span>
<span class="pl-s1">df</span>.<span class="pl-en">impute_missing_values</span>()

<span class="pl-c"># Generate features</span>
<span class="pl-s1">df</span>.<span class="pl-en">generate_features</span>()

<span class="pl-c"># Plot histogram</span>
<span class="pl-s1">df</span>.<span class="pl-en">plot_histogram</span>(<span class="pl-s1">column</span><span class="pl-c1">=</span><span class="pl-s">"gdp"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Clean data
df.clean_data()

# Impute missing values
df.impute_missing_values()

# Generate features
df.generate_features()

# Plot histogram
df.plot_histogram(column=&quot;gdp&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://pandas-ai.readthedocs.io/en/latest/shortcuts/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解有关快捷方式的更多信息</font><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--privacy--security" class="anchor" aria-hidden="true" tabindex="-1" href="#-privacy--security"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔒 隐私与安全</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了生成要运行的 Python 代码，我们获取数据帧头部，对其进行随机化（对敏感数据使用随机生成，对非敏感数据使用混洗）并仅发送头部。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另外，如果您想进一步加强您的隐私，您可以实例化 PandasAI，</font></font><code>enforce_privacy = True</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它不会将标题（而只是列名称）发送给 LLM。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#-contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤝 贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎贡献！</font><font style="vertical-align: inherit;">请查看下面的待办事项，并随时提出拉取请求。</font><font style="vertical-align: inherit;">有关更多信息，请参阅</font></font><a href="/gventuri/pandas-ai/blob/main/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装虚拟环境后，请记得安装</font></font><code>pre-commit</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以符合我们的标准：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pre-commit install</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pre-commit install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributors" class="anchor" aria-hidden="true" tabindex="-1" href="#contributors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献者</font></font></h2>
<p dir="auto"><a href="https://github.com/gventuri/pandas-ai/graphs/contributors"><img src="https://camo.githubusercontent.com/a38825e4b005235a59199a928d43263ab869ca75c4c125daef1ca3f6d056ed79/68747470733a2f2f636f6e747269622e726f636b732f696d6167653f7265706f3d6776656e747572692f70616e6461732d6169" alt="贡献者" data-canonical-src="https://contrib.rocks/image?repo=gventuri/pandas-ai" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--license" class="anchor" aria-hidden="true" tabindex="-1" href="#-license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📜 许可证</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PandasAI 根据 MIT 许可证获得许可。</font><font style="vertical-align: inherit;">有关更多详细信息，请参阅许可证文件。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-acknowledgements" class="anchor" aria-hidden="true" tabindex="-1" href="#acknowledgements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目基于独立贡献者的</font></font><a href="https://github.com/pandas-dev/pandas"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pandas</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库，但与 pandas 项目没有任何关联。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目旨在用作数据探索和分析的工具，而不是用于生产目的。</font><font style="vertical-align: inherit;">请负责任地使用它。</font></font></li>
</ul>
</article></div>
