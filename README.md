<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenHuFu：开源数据联合系统</font></font></h1><a id="user-content-openhufu-an-open-sourced-data-federation-system" class="anchor" aria-label="永久链接：OpenHuFu：开源数据联合系统" href="#openhufu-an-open-sourced-data-federation-system"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://codecov.io/gh/BUAA-BDA/OpenHuFu" rel="nofollow"><img src="https://camo.githubusercontent.com/13eb6248a2ab0659c2bb77a4702f6c6092eeb5a3314cd7a0d8143abb0b1bf169/68747470733a2f2f636f6465636f762e696f2f67682f425541412d4244412f4f70656e487546752f6272616e63682f6d61696e2f67726170682f62616467652e7376673f746f6b656e3d514a424547474e4c3250" alt="代码科夫" data-canonical-src="https://codecov.io/gh/BUAA-BDA/OpenHuFu/branch/main/graph/badge.svg?token=QJBEGGNL2P" style="max-width: 100%;"></a>
<a href="https://www.apache.org/licenses/LICENSE-2.0.html" rel="nofollow"><img src="https://camo.githubusercontent.com/3e787ad45f0862131e82fe26cfdf93deb2c5fbdd320f047942fa916088cc716e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d417061636865253230322d3445423142412e737667" alt="执照" data-canonical-src="https://img.shields.io/badge/license-Apache%202-4EB1BA.svg" style="max-width: 100%;"></a>
<a href="https://github.com/BUAA-BDA/OpenHuFu"><img src="https://camo.githubusercontent.com/0c36022f704c82269f4db46d757999f2a01b9ed6ee52e372535246ef257f5a59/68747470733a2f2f746f6b65692e72732f62312f6769746875622f425541412d4244412f4f70656e487546753f63617465676f72793d6c696e6573" alt="总行数" data-canonical-src="https://tokei.rs/b1/github/BUAA-BDA/OpenHuFu?category=lines" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据隔离已成为扩大大数据查询处理规模的障碍，因为出于安全考虑，数据所有者之间共享原始数据通常是禁止的。</font><font style="vertical-align: inherit;">一个有前景的解决方案是利用安全多方计算 (SMC) 和差异隐私等技术，在多个数据所有者的联合上执行安全查询和分析，最近的数据联合和联邦学习工作就证明了这一点。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenHuFu 是一个开源系统，用于在数据联合上进行高效、安全的查询处理。</font><font style="vertical-align: inherit;">它为研究人员提供了灵活性，使他们能够快速实现使用 SMC 技术处理联合查询的算法，例如秘密共享、乱码电路和不经意的传输。</font><font style="vertical-align: inherit;">借助它，我们可以快速进行实验评估，并获得设计算法在基准数据集上的性能。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源代码编译 OpenHuFu</font></font></h2><a id="user-content-compile-openhufu-from-source-code" class="anchor" aria-label="永久链接：从源代码编译 OpenHuFu" href="#compile-openhufu-from-source-code"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">先决条件：</font></font></h3><a id="user-content-prerequisites" class="anchor" aria-label="永久链接：先决条件：" href="#prerequisites"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux 或 MacOS</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">爪哇11</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Maven（版本至少为 3.5.2）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C++（生成TPC-H数据）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python3（生成空间数据）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Git &amp; Git LFS（Git 大文件存储）</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建 OpenHuFu</font></font></h3><a id="user-content-build-openhufu" class="anchor" aria-label="永久链接：构建 OpenHuFu" href="#build-openhufu"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行以下命令：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆 OpenHuFu 存储库：</font></font></li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/BUAA-BDA/OpenHuFu.git</pre><div class="zeroclipboard-container">
    
  </div></div>
<ol start="2" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 Git LFS（大文件存储）下载大文件</font></font></li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> OpenHuFu
git lfs install --skip-smudge
git lfs pull </pre><div class="zeroclipboard-container">
   
  </div></div>
<ol start="3" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建造：</font></font></li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> OpenHuFu
bash scripts/build/package.sh</pre><div class="zeroclipboard-container">
   
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenHuFu 现已安装在</font></font><code>release</code></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></h3><a id="user-content-notes" class="anchor" aria-label="永久链接：注释" href="#notes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用 MacsOS，则需要将其添加到</font></font><code>settings.xml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（maven 设置文件）：</font></font></p>
<div class="highlight highlight-text-xml notranslate position-relative overflow-auto" dir="auto"><pre>&lt;<span class="pl-ent">profiles</span>&gt;
    &lt;<span class="pl-ent">profile</span>&gt;
      &lt;<span class="pl-ent">id</span>&gt;macos&lt;/<span class="pl-ent">id</span>&gt;
      &lt;<span class="pl-ent">properties</span>&gt;
        &lt;<span class="pl-ent">os</span>.detected.classifier&gt;osx-x86_64&lt;/<span class="pl-ent">os</span>.detected.classifier&gt;
      &lt;/<span class="pl-ent">properties</span>&gt;
    &lt;/<span class="pl-ent">profile</span>&gt;
&lt;/<span class="pl-ent">profiles</span>&gt;
&lt;<span class="pl-ent">activeProfiles</span>&gt;
    &lt;<span class="pl-ent">activeProfile</span>&gt;macos&lt;/<span class="pl-ent">activeProfile</span>&gt;
&lt;/<span class="pl-ent">activeProfiles</span>&gt;</pre><div class="zeroclipboard-container">
    
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据生成</font></font></h2><a id="user-content-data-generation" class="anchor" aria-label="永久链接：数据生成" href="#data-generation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关系数据：</font></font><a href="https://www.tpc.org/tpch/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TCP-H</font></font></a></h3><a id="user-content-relational-data-tcp-h" class="anchor" aria-label="永久链接：关系数据：TCP-H" href="#relational-data-tcp-h"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用它：</font></font></h4><a id="user-content-how-to-use-it" class="anchor" aria-label="永久链接： 如何使用它：" href="#how-to-use-it"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash scripts/test/extract_tpc_h.sh

<span class="pl-c1">cd</span> dataset/TPC-H<span class="pl-cce">\ </span>V3.0.1/dbgen
cp makefile.suite makefile
<span class="pl-c"><span class="pl-c">#</span> If you use MacOS, you need to replace '#include &lt;malloc.h&gt;' with #include &lt;sys/malloc.h&gt; in dbgen</span>
make

<span class="pl-c"><span class="pl-c">#</span> Go to the root folder</span>
<span class="pl-c1">cd</span> ../../..
<span class="pl-c"><span class="pl-c">#</span> x is the number of database，y is the volume of each database(MB)</span>
bash scripts/test/generateData.sh x y</pre><div class="zeroclipboard-container">
   
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">空间数据</font></font></h3><a id="user-content-spatial-data" class="anchor" aria-label="永久链接：空间数据" href="#spatial-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">空间样本数据</font></font><code>dataset/newyork-taxi-sample.data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：：</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用它</font></font></h4><a id="user-content-how-to-use-it-1" class="anchor" aria-label="永久链接：如何使用它" href="#how-to-use-it-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成空间数据：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip3 install numpy
python3 scripts/test/genSyntheticData.py databaseNum dataSize [distribution name] [params]</pre><div class="zeroclipboard-container">
  
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们支持的发行版及其参数如下：</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分配</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数1</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数2</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大学</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">低（默认 = -1e7）</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高（默认 = 1e7）</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">也不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mu（默认 = 0）</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">西格玛（默认 = 1e5）</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">经验值</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mu（默认 = 5e6）</font></font></td>
<td align="center"></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（如有需要，可以修改</font></font><code>scripts/test/genSyntheticData.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></h3><a id="user-content-notes-1" class="anchor" aria-label="永久链接：注释" href="#notes-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个表由两个CSV和SCM格式的文&ZeroWidthSpace;&ZeroWidthSpace;件定义，文件名作为表的实际名称。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
CSV文件包含列名和表的数据，而SCM文件包含列名和列类型。</font><font style="vertical-align: inherit;">分隔符用于分隔不同的列字段，可以在所有者的配置文件中指定。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置文件</font></font></h2><a id="user-content-configuration-file" class="anchor" aria-label="永久链接：配置文件" href="#configuration-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">业主方</font></font></h3><a id="user-content-ownerside" class="anchor" aria-label="永久链接： 业主方" href="#ownerside"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户端</font></font></h3><a id="user-content-userside" class="anchor" aria-label="永久链接：用户端" href="#userside"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发流程</font></font></h2><a id="user-content-development-procedure" class="anchor" aria-label="永久链接：开发流程" href="#development-procedure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发您的算法</font></font></li>
</ol>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总计的：</font></font></li>
</ul>
<div class="highlight highlight-source-java notranslate position-relative overflow-auto" dir="auto"><pre>  <span class="pl-k">class</span> <span class="pl-s1">extends</span> <span class="pl-s1">com</span>.<span class="pl-s1">hufudb</span>.<span class="pl-s1">openhufu</span>.<span class="pl-s1">owner</span>.<span class="pl-s1">implementor</span>.<span class="pl-s1">aggregate</span>.<span class="pl-s1">OwnerAggregateFunction</span>
  <span class="pl-c">/** </span>
<span class="pl-c">   *  The class must contains a constructor function with parameters:</span>
<span class="pl-c">   *  (OpenHuFuPlan.Expression agg, Rpc rpc, ExecutorService threadPool, OpenHuFuPlan.TaskInfo taskInfo)</span>
<span class="pl-c">   */</span> </pre><div class="zeroclipboard-container">
    
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加入：</font></font></li>
</ul>
<div class="highlight highlight-source-java notranslate position-relative overflow-auto" dir="auto"><pre>  <span class="pl-k">class</span> <span class="pl-s1">implements</span> <span class="pl-s1">com</span>.<span class="pl-s1">hufudb</span>.<span class="pl-s1">openhufu</span>.<span class="pl-s1">owner</span>.<span class="pl-s1">implementor</span>.<span class="pl-s1">join</span>.<span class="pl-s1">OwnerJoin</span></pre><div class="zeroclipboard-container">
    
  </div></div>
<ol start="2" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置查询的算法（owner.yaml 中的示例）：</font></font></li>
</ol>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">openhufu</span>:
    <span class="pl-ent">implementor</span>:
      <span class="pl-ent">aggregate</span>:
        <span class="pl-ent">sum</span>: <span class="pl-s">com.hufudb.openhufu.owner.implementor.aggregate.sum.SecretSharingSum</span>
        <span class="pl-ent">count</span>: <span class="pl-c1">null</span>
        <span class="pl-ent">max</span>: <span class="pl-c1">null</span>
        <span class="pl-ent">min</span>: <span class="pl-c1">null</span>
        <span class="pl-ent">avg</span>: <span class="pl-c1">null</span>
      <span class="pl-ent">join</span>: <span class="pl-s">com.hufudb.openhufu.owner.implementor.join.HashJoin</span></pre><div class="zeroclipboard-container">
    
  </div></div>
<ol start="3" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建 OpenHuFu</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照部分中的说明</font></font><code>Build OpenHuFu</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建项目。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 OpenHuFu</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们为文件夹中的 3 个所有者提供示例配置</font></font><code>release/config</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
您可以使用该配置在单台机器上运行我们的演示，也可以修改配置文件以在多台机器上部署 OpenHuFu。</font></font><br></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，由于配置文件使用相对路径，因此我们需要</font></font><code>cd release</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在运行命令之前进行配置。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在单机上运行演示：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash owner_all.sh</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在多台机器上运行 OpenHuFu：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash owner.sh start ./config/owner{i}.json</pre><div class="zeroclipboard-container">
   
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">停止 OpeHuFu：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash owner.sh stop</pre><div class="zeroclipboard-container">
     
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行基准测试</font></font></p>
</li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>bash benchmark.sh</pre><div class="zeroclipboard-container">
    
  </div></div>
<ol start="5" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评估沟通成本</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 OpenHuFu 上运行基准测试之前，您可以按照说明评估查询的通信成本：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控端口</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> run the shell script as root</span>
<span class="pl-c"><span class="pl-c">#</span> 8888 is the port number </span>
sudo bash scripts/test/network_mmonitor/start.sh 8888</pre><div class="zeroclipboard-container">
    
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计算通信成本</font></font></li>
</ul>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> run the shell script as root</span>
sudo bash scripts/test/network_mmonitor/monitor.sh</pre><div class="zeroclipboard-container">
     
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据查询语言</font></font></h2><a id="user-content-data-query-language" class="anchor" aria-label="永久链接：数据查询语言" href="#data-query-language"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">计划</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数调用</font></font></li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的查询类型</font></font></h2><a id="user-content-supported-query-types" class="anchor" aria-label="永久链接：支持的查询类型" href="#supported-query-types"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">筛选</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">投影</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加入
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等值连接</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">西塔加入</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">交叉产品</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聚合（包括分组依据）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有限的窗口聚合</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">清楚的</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">种类</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">限制</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常用表表达式</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">空间查询：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围查询</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围计数</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">knn查询</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">距离连接</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">knn 加入</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评估指标</font></font></h2><a id="user-content-evaluation-metrics" class="anchor" aria-label="永久链接：评估指标" href="#evaluation-metrics"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">沟通成本</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行时间
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总查询时间</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地查询时间</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加密时间</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解密时间</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相关工作</font></font></h2><a id="user-content-related-work" class="anchor" aria-label="永久链接：相关工作" href="#related-work"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现 OpenHuFu 对您的研究有帮助，请考虑引用我们的论文和 bibtex，如下所示：</font></font></strong></p>
<ol dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hu-Fu：通过数据联合进行高效、安全的空间查询。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">童永欣、潘绪辰、曾宇翔、石叶轩、薛春波、周子木、张晓飞、陈雷、徐毅、徐科、吕伟峰。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">过程。</font><font style="vertical-align: inherit;">VLDB 捐赠。</font><font style="vertical-align: inherit;">15（6）：1159-1172（2022）。</font><font style="vertical-align: inherit;">[</font></font><a href="https://www.vldb.org/pvldb/vol15/p1159-tong.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纸张</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [</font></font><a href="http://yongxintong.group/static/paper/2018/VLDB2018_A%20Unified%20Approach%20to%20Route%20Planning%20for%20Shared%20Mobility_Slides.pptx" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">幻灯片</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/journals/pvldb/TongPZSXZZCXXL22.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></li>
</ol>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面列出了我们小组的其他有用的相关工作：</font></font></strong></p>
<ol dir="auto">
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DM-PFL：搭通用联邦学习的便车实现高效的稳健个性化。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张文浩，周子慕，王燕生，童永欣。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDD 2023. [</font></font><a href="https://dl.acm.org/doi/10.1145/3580305.3599311" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/conf/kdd/ZhangZWT23.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大规模空间数据联合的高效近似范围聚合。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">施叶轩，童永欣，曾宇翔，周子木，丁柏林，陈雷。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 传输。</font><font style="vertical-align: inherit;">知道。</font><font style="vertical-align: inherit;">数据工程 </font><font style="vertical-align: inherit;">35（1）：418-430（2023）。</font><font style="vertical-align: inherit;">[</font></font><a href="https://hufudb.com/static/paper/2022/TKDE2022_Efficient%20Approximate%20Range%20Aggregation%20over%20Large-scale%20Spatial%20Data%20Federation.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/journals/tkde/ShiTZZDC23.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hu-Fu：用于安全空间查询的数据联合系统。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">潘旭辰、童永欣、薛春波、周子慕、杜军平、曾宇翔、史叶轩、张晓飞、陈雷、徐毅、徐科、吕伟峰。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">过程。</font><font style="vertical-align: inherit;">VLDB 捐赠。</font><font style="vertical-align: inherit;">15（12）：3582-3585（2022）。</font><font style="vertical-align: inherit;">[</font></font><a href="https://www.vldb.org/pvldb/vol15/p3582-tong.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/journals/pvldb/PanTXZDZSZCXXL22.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联邦学习中的数据源选择：子模块优化方法。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张瑞生，王燕生，周子木，任子耀，童永欣，徐科。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DASFAA 2022。 [</font></font><a href="https://doi.org/10.1007/978-3-031-00126-0_43" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/conf/dasfaa/ZhangWZRTX22.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Fed-LTD：通过联合学习调度迈向跨平台乘车服务。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">王燕生，童永欣，周子木，任子耀，徐毅，吴国斌，吕伟峰。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">KDD 2022。 [</font></font><a href="https://doi.org/10.1145/3534678.3539047" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/conf/kdd/WangTZRXWL22.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过垂直数据联合进行高效、安全的 Skyline 查询。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张媛媛，史叶轩，周子慕，薛春波，徐毅，徐科，杜俊平。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 传输。</font><font style="vertical-align: inherit;">知道。</font><font style="vertical-align: inherit;">数据工程 </font><font style="vertical-align: inherit;">（2022）。</font><font style="vertical-align: inherit;">[</font></font><a href="https://doi.org/10.1109/TKDE.2022.3222415" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://ieeexplore.ieee.org/document/9950625" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联合主题发现：语义一致的方法。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">施叶轩，童永欣，苏志扬，蒋迪，周子木，张文斌。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 英特尔。</font><font style="vertical-align: inherit;">系统。</font><font style="vertical-align: inherit;">36（5）：96-103（2021）。</font><font style="vertical-align: inherit;">[</font></font><a href="https://doi.org/10.1109/MIS.2020.3033459" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/journals/expert/ShiTSJZZ21.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工业联合主题建模。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蒋迪、童永欣、宋元峰、吴雪阳、赵伟伟、彭金华、连荣中、徐谦、杨强。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM 翻译。</font><font style="vertical-align: inherit;">英特尔。</font><font style="vertical-align: inherit;">系统。</font><font style="vertical-align: inherit;">技术。</font><font style="vertical-align: inherit;">12(1): 2:1-2:22 (2021)。</font><font style="vertical-align: inherit;">[</font></font><a href="https://doi.org/10.1145/3418283" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/journals/tist/JiangTSWZPLXY21.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">符合 GDPR 的语音识别生态系统，具有迁移、联合和进化学习功能。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蒋迪、谭丛辉、彭金华、陈朝涛、吴雪阳、赵伟伟、宋远峰、童永欣、刘畅、徐谦、杨强、邓力。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM 翻译。</font><font style="vertical-align: inherit;">英特尔。</font><font style="vertical-align: inherit;">系统。</font><font style="vertical-align: inherit;">技术。</font><font style="vertical-align: inherit;">12（3）：30：1-30：19（2021）。</font><font style="vertical-align: inherit;">[</font></font><a href="https://doi.org/10.1145/3447687" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/journals/tist/JiangTPCWZSTLXY21.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跨筒仓联合学习排序的有效方法。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">王彦生，童永欣，史定远，徐科。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ICDE 2021。 [</font></font><a href="https://doi.org/10.1109/ICDE51399.2021.00102" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [</font></font><a href="https://hufudb.com/static/paper/2021/ICDE2021_An%20Efficient%20Approach%20for%20Cross-Silo%20Federated%20Learning%20to%20Rank.pptx" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">幻灯片</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/conf/icde/WangTS021.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">众包视角下的联邦学习。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">童永新，王彦生，施定元。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE 数据工程。</font><font style="vertical-align: inherit;">公牛。</font><font style="vertical-align: inherit;">43（3）：26-36（2020）。</font><font style="vertical-align: inherit;">[</font></font><a href="http://sites.computer.org/debull/A20sept/p26.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/journals/debu/TongWS20.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联合潜在狄利克雷分配：基于本地差分隐私的框架。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">王彦生，童永新，施定远。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AAAI 2020. [</font></font><a href="https://ojs.aaai.org/index.php/AAAI/article/view/6096" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/conf/aaai/WangTS20.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于自动语音识别的联合声学模型优化。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">谭从辉、蒋迪、莫华晓、彭金华、童永欣、赵伟伟、陈超涛、连荣中、宋元峰、徐谦。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DASFAA 2020. [</font></font><a href="https://doi.org/10.1007/978-3-030-59419-0_54" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/conf/dasfaa/TanJMPTZCLSX20.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">横向联邦学习的高效、公平的数据评估。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">魏舒月，童永欣，周子木，宋天舒。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联邦学习 2020。 [</font></font><a href="https://doi.org/10.1007/978-3-030-63076-8_10" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/series/lncs/WeiTZS20.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联邦学习的利润分配。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">宋天舒，童永欣，魏舒悦。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEEE BigData 2019。 [</font></font><a href="https://doi.org/10.1109/BigData47090.2019.9006327" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [</font></font><a href="https://hufudb.com/static/paper/2019/BigData2019_Profit%20Allocation%20for%20Federated%20Learning_Slides.pptx" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">幻灯片</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/conf/bigdataconf/SongTW19.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
<li>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联合机器学习：概念和应用。</font></font></strong>
<em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">杨强，刘阳，陈天健，童永新。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACM 翻译。</font><font style="vertical-align: inherit;">英特尔。</font><font style="vertical-align: inherit;">系统。</font><font style="vertical-align: inherit;">技术。</font><font style="vertical-align: inherit;">10（2）：12：1-12：19（2019）。</font><font style="vertical-align: inherit;">[</font></font><a href="https://doi.org/10.1145/3298981" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] [ </font></font><a href="https://dblp.org/rec/journals/tist/YangLCT19.html?view=bibtex" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bibtex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ]</font></font></p>
</li>
</ol>
</article></div>
