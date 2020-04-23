---
keywords: fastai
description: Cours NSI Terminale - Thème 1.
title: Structures de données linéaires 
toc: true 
badges: true
comments: false
categories: [python, NSI, Terminale, Structure_donnees, TP]
nb_path: _notebooks/2020-04-14-nsi_t_listes_piles_files.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2020-04-14-nsi_t_listes_piles_files.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Les-piles">Les piles<a class="anchor-link" href="#Les-piles"> </a></h2><p>On va commencer ce TP par la manipulation des piles, plus faciles à appréhender, et on terminera par la manuipulation des listes chaînées. Rappelons tout d'abord la notion de <strong>piles</strong> répondant à la règle <strong>LIFO</strong> : dernier entré, premier sorti.</p>
<p><img src="/images/copied_from_nb/pile1.png" alt="pile"></p>
<h3 id="Description-de-la-structure">Description de la structure<a class="anchor-link" href="#Description-de-la-structure"> </a></h3><p>Pour stocker les données dans notre pile, nous utiliserons un tableau python (objet list).
Le dernier élément du tableau sera le sommet de la pile. Seul cet élément sera visible.</p>
<p><strong>Exemple</strong> : Si la pile est représentée en mémoire par le tableau <code>[2, 3, 5, 8]</code>, le sommet de la pile sera <code>8</code>. Si je dépile le 8, la pile deviendra <code>[2, 3, 5]</code> et le sommet de la pile sera 5. Une fois tous les éléments dépilés, la pile sera vide et représentée par <code>[]</code>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="A-vous-de-jouer">A vous de jouer<a class="anchor-link" href="#A-vous-de-jouer"> </a></h3><p>Vous allez devoir implémenter les fonctions</p>
<ul>
<li><code>p_valeur(p)</code><ul>
<li>prend en paramètre une pile <code>p</code></li>
<li>renvoie le sommet de la pile ou <code>None</code> si la pile est vide</li>
</ul>
</li>
<li><code>p_depile(p)</code><ul>
<li>prend en paramètre une pile <code>p</code></li>
<li>dépile le dernier élément saisi</li>
<li>renvoie la valeur dépilée ou <code>None</code> si la pile est vide</li>
</ul>
</li>
<li><code>p_empile(p, v)</code><ul>
<li>prend en paramètre une pile <code>p</code> et une valeur <code>v</code></li>
<li>empile la valeur <code>v</code></li>
<li>ne renvoie rien</li>
</ul>
</li>
</ul>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">p_valeur</span><span class="p">(</span><span class="n">p</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre une pile p</span>
<span class="sd">    - renvoie le sommet de la pile</span>
<span class="sd">    Exemple : </span>
<span class="sd">    &gt;&gt;&gt; p_valeur([2, 3, 5])</span>
<span class="sd">    &gt;&gt;&gt; 5</span>
<span class="sd">    &gt;&gt;&gt; p_valeur([])</span>
<span class="sd">    &gt;&gt;&gt; None</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">assert</span> <span class="n">p_valeur</span><span class="p">([])</span> <span class="ow">is</span> <span class="kc">None</span>
<span class="k">assert</span> <span class="n">p_valeur</span><span class="p">([</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">])</span> <span class="o">==</span> <span class="mi">5</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">p_depile</span><span class="p">(</span><span class="n">p</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre une pile p</span>
<span class="sd">    - dépile le dernier élément saisi</span>
<span class="sd">    - renvoie le sommet de la pile</span>
<span class="sd">    Exemple : </span>
<span class="sd">    &gt;&gt;&gt; p_valeur([2, 3, 5])</span>
<span class="sd">    &gt;&gt;&gt; 5</span>
<span class="sd">    &gt;&gt;&gt; p_valeur([])</span>
<span class="sd">    &gt;&gt;&gt; None</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">p</span><span class="o">=</span><span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">]</span>
<span class="k">assert</span> <span class="n">p_depile</span><span class="p">(</span><span class="n">p</span><span class="p">)</span> <span class="o">==</span> <span class="mi">5</span>
<span class="k">assert</span> <span class="n">p</span> <span class="o">==</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">]</span>
<span class="k">assert</span> <span class="n">p_depile</span><span class="p">([])</span> <span class="ow">is</span> <span class="kc">None</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">p_empile</span><span class="p">(</span><span class="n">p</span><span class="p">,</span> <span class="n">v</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre une pile p et une valeur v</span>
<span class="sd">    - empile la valeur v</span>
<span class="sd">    Exemple : </span>
<span class="sd">    &gt;&gt;&gt; p = [2, 3]</span>
<span class="sd">    &gt;&gt;&gt; p_empile(p, 5)</span>
<span class="sd">    &gt;&gt;&gt; p</span>
<span class="sd">    &gt;&gt;&gt; [2, 3, 5]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">p</span> <span class="o">=</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">]</span>
<span class="n">p_empile</span><span class="p">(</span><span class="n">p</span><span class="p">,</span> <span class="mi">5</span><span class="p">)</span>
<span class="k">assert</span> <span class="n">p</span> <span class="o">==</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Les-files">Les files<a class="anchor-link" href="#Les-files"> </a></h2><p>Rappelons la notion de <strong>files</strong> répondant à la règle <strong>FIFO</strong> : premier entré, premier sorti.</p>
<p><img src="/images/copied_from_nb/file1.png" alt="file"></p>
<h3 id="Description-de-la-structure">Description de la structure<a class="anchor-link" href="#Description-de-la-structure"> </a></h3><p>Pour stocker les données dans notre file, nous utiliserons un tableau python (objet list).</p>
<ul>
<li>le dernier élément du tableau sera l'avant de la file. Seul cet élément sera visible</li>
<li>le premier élément du tableau sera l'arrière de la file</li>
</ul>
<p><strong>Exemple</strong> : Si la sile est représentée en mémoire par le tableau <code>[2, 3, 5, 8]</code>, l'avant de la file sera <code>8</code> et l'arrière de la file sera 2. Si on ajoute 1 à l'arrière de la file, celle-ci contiendra <code>[1, 2, 3, 5, 8]</code>. Une fois tous les éléments dépilés, la file sera vide et représentée par <code>[]</code>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="A-vous-de-jouer">A vous de jouer<a class="anchor-link" href="#A-vous-de-jouer"> </a></h3><p>Vous allez devoir implémenter les fonctions</p>
<ul>
<li><code>f_valeur(f)</code><ul>
<li>prend en paramètre une file <code>f</code></li>
<li>renvoie la valeur à l'avant de la file ou <code>None</code> si la file est vide</li>
</ul>
</li>
<li><code>f_defile(f)</code><ul>
<li>prend en paramètre une file <code>f</code></li>
<li>défile l'élément situé à l'avant de la file</li>
<li>renvoie la valeur défilée ou <code>None</code> si la file est vide</li>
</ul>
</li>
<li><code>f_emfile(f, v)</code><ul>
<li>prend en paramètre une file <code>f</code> et une valeur <code>v</code></li>
<li>emfile la valeur <code>v</code> à l'arrière de la file</li>
<li>ne renvoie rien</li>
</ul>
</li>
</ul>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">f_valeur</span><span class="p">(</span><span class="n">f</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre une file f</span>
<span class="sd">    - renvoie la valeur à l&#39;avant de la file ou None si la file est vide</span>
<span class="sd">    Exemple : </span>
<span class="sd">    &gt;&gt;&gt; f_valeur([2, 3, 5])</span>
<span class="sd">    &gt;&gt;&gt; 5</span>
<span class="sd">    &gt;&gt;&gt; f_valeur([])</span>
<span class="sd">    &gt;&gt;&gt; None</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">assert</span> <span class="n">f_valeur</span><span class="p">([])</span> <span class="ow">is</span> <span class="kc">None</span>
<span class="k">assert</span> <span class="n">f_valeur</span><span class="p">([</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">])</span> <span class="o">==</span> <span class="mi">5</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">f_defile</span><span class="p">(</span><span class="n">f</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre une file f</span>
<span class="sd">    - défile l&#39;élément situé à l&#39;avant de la file</span>
<span class="sd">    - renvoie la valeur défilée ou None si la file est vide</span>
<span class="sd">    Exemple : </span>
<span class="sd">    &gt;&gt;&gt; f = [2, 3, 5, 8]</span>
<span class="sd">    &gt;&gt;&gt; f_defile(f)</span>
<span class="sd">    &gt;&gt;&gt; 8</span>
<span class="sd">    &gt;&gt;&gt; f</span>
<span class="sd">    &gt;&gt;&gt; [2, 3, 5]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">f</span> <span class="o">=</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">8</span><span class="p">]</span>
<span class="k">assert</span> <span class="n">f_defile</span><span class="p">(</span><span class="n">f</span><span class="p">)</span> <span class="o">==</span> <span class="mi">8</span>
<span class="k">assert</span> <span class="n">f</span> <span class="o">==</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">f_enfile</span><span class="p">(</span><span class="n">f</span><span class="p">,</span> <span class="n">v</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre une file f et une valeur v</span>
<span class="sd">    - enfile la valeur v à l&#39;arrière de la file</span>
<span class="sd">    Exemple :</span>
<span class="sd">    &gt;&gt;&gt; f = [2, 3, 5, 8]</span>
<span class="sd">    &gt;&gt;&gt; f_enfile(f, 1)</span>
<span class="sd">    &gt;&gt;&gt; f</span>
<span class="sd">    &gt;&gt;&gt; [1, 2, 3, 5, 8]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">f</span> <span class="o">=</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">8</span><span class="p">]</span>
<span class="n">f_enfile</span><span class="p">(</span><span class="n">f</span><span class="p">,</span> <span class="mi">1</span><span class="p">)</span>
<span class="k">assert</span> <span class="n">f</span> <span class="o">==</span> <span class="p">[</span><span class="mi">1</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">8</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Les-listes-cha&#238;n&#233;es">Les listes cha&#238;n&#233;es<a class="anchor-link" href="#Les-listes-cha&#238;n&#233;es"> </a></h2><h3 id="Description-de-la-structure">Description de la structure<a class="anchor-link" href="#Description-de-la-structure"> </a></h3><p>On rappelle que la structure d'une liste chaînée ressemble à ceci :
<img src="/images/copied_from_nb/listechainee.svg" alt="Liste chainée"></p>
<p>L'illustration montre une liste chaînée composée de 4 maillons. Chaque maillon est composé de 2 champs : une valeur et un pointeur vers le maillon suivant.</p>
<p>Pour implémenter une liste chaînée en python nous utiliserons</p>
<ul>
<li>un tableau à 2 éléments décrivant un maillon<ul>
<li>le premier élément du tableau est la valeur du maillon</li>
<li>le second élément est l'indice du maillon suivant (ou None pour le dernier élément)</li>
</ul>
</li>
<li>un tableau constitué de la liste de tous les maillons</li>
</ul>
<p>La liste chaînée donnée en illustration pourra donc être représentée ainsi :</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">maillons</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">2</span><span class="p">],</span> <span class="p">[</span><span class="mi">8</span><span class="p">,</span><span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span><span class="mi">0</span><span class="p">]]</span>
<span class="n">premier</span> <span class="o">=</span> <span class="mi">3</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Vous constaterez que j'ai <em>volontairement</em> inscrit dans le tableau <code>maillons</code> les éléments de la liste dans le désordre car il n'y a aucune raison que l'ordre des éléments corresponde à l'ordre dans le tableau <code>maillons</code> si par exemple on insère en cours de route des éléments au milieu de la liste.</p>
<p>la variable <code>premier</code> contient l'indice du premier élément de la liste, c'est donc le maillon <code>[2,0]</code> correspondant à la valeur 2. L'élément suivant sera le maillon à l'indice 0 dans le tableau donc <code>[3,2]</code> dont la valeur est 3. Ensuite on accède au maillon d'indice 2 donc <code>[5,1]</code> de valeur 5 pour terminer par le maillon <code>[8,None]</code> de valeur 8 marquant la fin de la liste. Au final la liste est donc bien $$2 - 3 - 5 - 8$$
On va supposer dans la suite que la variable <code>maillons</code> est <strong>globale</strong> et contiendra tous les maillons de toutes les listes avec lesquelles nous travaillerons. Une liste sera donc définie uniquement par l'<strong>indice de son premier élément</strong> dans le tableau <code>maillons</code>.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="A-vous-de-jouer">A vous de jouer<a class="anchor-link" href="#A-vous-de-jouer"> </a></h3><p>Vous allez devoir implémenter les fonctions</p>
<ul>
<li><code>l_premier(p)</code> <ul>
<li>prend en paramètre l'indice du premier élément d'une liste <code>p</code></li>
<li>renvoye la valeur du premier élément de la liste </li>
</ul>
</li>
<li><code>l_valeurs(p)</code><ul>
<li>prend en paramètre l'indice du premier élément d'une liste <code>p</code></li>
<li>renvoye un tableau avec toutes les valeurs de la liste</li>
</ul>
</li>
<li><code>l_insere_debut(p, v)</code><ul>
<li>prend en paramètre l'indice du premier élément d'une liste <code>p</code> et la valeur à insérer <code>v</code></li>
<li>renvoye l'indice du premier élément de la nouvelle liste où la valeur <code>v</code> a été insérée au début</li>
</ul>
</li>
<li><code>l_insere_fin(p, v)</code><ul>
<li>prend en paramètre l'indice du premier élément d'une liste <code>p</code> et la valeur à insérer <code>v</code></li>
<li>insère à la fin de la liste la valeur <code>v</code></li>
<li>renvoye <code>p</code> car la liste commence par le même élément</li>
</ul>
</li>
<li><code>l_nouveau(v)</code><ul>
<li>prend en paramètre une valeur <code>v</code></li>
<li>renvoie l'indice du premier élément de cette liste constituée du seul élément <code>v</code></li>
</ul>
</li>
<li><code>l_scinde(p, i)</code><ul>
<li>prend en paramètre une liste <code>p</code> et in indice <code>i</code></li>
<li>scinde la liste <code>p</code> en deux listes dont la première possède <code>i</code> éléments</li>
<li>renvoie l'indice du premier élément de la seconde sous liste (la première commence toujours à <code>p</code>)</li>
</ul>
</li>
<li><code>l_concat(p1, p2)</code><ul>
<li>prend en paramètre deux listes <code>p1</code> et <code>p2</code></li>
<li>concatène (met bout à bout) les deux listes</li>
<li>renvoie <code>p1</code> : début de la liste concaténée.</li>
</ul>
</li>
</ul>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">l_premier</span><span class="p">(</span><span class="n">p</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre l&#39;indice du premier élément d&#39;une liste p</span>
<span class="sd">    - renvoye la valeur du premier élément de la liste</span>
<span class="sd">    Exemple : maillons = [[3, 2], [8,None], [5, 1], [2,0]]</span>
<span class="sd">    &gt;&gt;&gt; l_premier(3)</span>
<span class="sd">    &gt;&gt;&gt; 2</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Testez votre fonction</span>
<span class="n">maillons</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">2</span><span class="p">],</span> <span class="p">[</span><span class="mi">8</span><span class="p">,</span><span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span><span class="mi">0</span><span class="p">]]</span>
<span class="k">assert</span> <span class="n">l_premier</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span> <span class="o">==</span> <span class="mi">2</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">l_valeurs</span><span class="p">(</span><span class="n">p</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;</span>
<span class="sd">    - prend en paramètre l&#39;indice du premier élément d&#39;une liste p</span>
<span class="sd">    - renvoye un tableau avec toutes les valeurs de la liste</span>
<span class="sd">    Exemple : maillons = [[3, 2], [8,None], [5, 1], [2,0]]</span>
<span class="sd">    &gt;&gt;&gt; l_valeurs(3)</span>
<span class="sd">    &gt;&gt;&gt; [2, 3, 5, 8]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Testez votre fonction</span>
<span class="n">maillons</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">2</span><span class="p">],</span> <span class="p">[</span><span class="mi">8</span><span class="p">,</span><span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span><span class="mi">0</span><span class="p">]]</span>
<span class="k">assert</span> <span class="n">l_valeurs</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span> <span class="o">==</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">8</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">l_insere_debut</span><span class="p">(</span><span class="n">p</span><span class="p">,</span> <span class="n">v</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;-prend en paramètre l&#39;indice du premier élément d&#39;une liste p et la valeur à insérer v</span>
<span class="sd">    -renvoye l&#39;indice du premier élément de la nouvelle liste où la valeur v a été insérée au début</span>
<span class="sd">    Exemple : maillons = [[3, 2], [8,None], [5, 1], [2,0]]</span>
<span class="sd">    &gt;&gt;&gt; p = l_insere_debut(-5)</span>
<span class="sd">    &gt;&gt;&gt; l_valeurs(p)</span>
<span class="sd">    &gt;&gt;&gt; [-5, 2, 3, 5, 8]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Testez votre fonction</span>
<span class="n">maillons</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">2</span><span class="p">],</span> <span class="p">[</span><span class="mi">8</span><span class="p">,</span><span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span><span class="mi">0</span><span class="p">]]</span>
<span class="n">p</span> <span class="o">=</span> <span class="n">l_insere_debut</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span><span class="o">-</span><span class="mi">5</span><span class="p">)</span>
<span class="k">assert</span> <span class="n">l_valeurs</span><span class="p">(</span><span class="n">p</span><span class="p">)</span> <span class="o">==</span> <span class="p">[</span><span class="o">-</span><span class="mi">5</span><span class="p">,</span> <span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">8</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">l_insere_fin</span><span class="p">(</span><span class="n">p</span><span class="p">,</span> <span class="n">v</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;-prend en paramètre l&#39;indice du premier élément d&#39;une liste p et la valeur à insérer v</span>
<span class="sd">    - insère à la fin de la liste la valeur v</span>
<span class="sd">    - renvoye p car la liste commence par le même élément</span>
<span class="sd">    Exemple : maillons = [[3, 2], [8,None], [5, 1], [2,0]]</span>
<span class="sd">    &gt;&gt;&gt; p = l_insere_fin(3, 11)</span>
<span class="sd">    &gt;&gt;&gt; l_valeurs(p)</span>
<span class="sd">    &gt;&gt;&gt; [2, 3, 5, 8, 11]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="n">i</span> <span class="o">=</span> <span class="n">p</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Testez votre fonction</span>
<span class="n">maillons</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">2</span><span class="p">],</span> <span class="p">[</span><span class="mi">8</span><span class="p">,</span><span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span><span class="mi">0</span><span class="p">]]</span>
<span class="n">p</span> <span class="o">=</span> <span class="n">l_insere_fin</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span> <span class="mi">11</span><span class="p">)</span>
<span class="k">assert</span> <span class="n">l_valeurs</span><span class="p">(</span><span class="n">p</span><span class="p">)</span> <span class="o">==</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">8</span><span class="p">,</span> <span class="mi">11</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">l_nouveau</span><span class="p">(</span><span class="n">v</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre une valeur v</span>
<span class="sd">    - renvoie l&#39;indice du premier élément de cette liste constituée du seul élément v</span>
<span class="sd">    Exemple : maillons = [[3, 2], [8,None], [5, 1], [2,0]]</span>
<span class="sd">    &gt;&gt;&gt; p = l_nouveau(15)</span>
<span class="sd">    &gt;&gt;&gt; l_valeurs(p)</span>
<span class="sd">    &gt;&gt;&gt; [ 15 ]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Testez votre fonction</span>
<span class="n">maillons</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">2</span><span class="p">],</span> <span class="p">[</span><span class="mi">8</span><span class="p">,</span><span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span><span class="mi">0</span><span class="p">]]</span>
<span class="n">p</span> <span class="o">=</span> <span class="n">l_nouveau</span><span class="p">(</span><span class="mi">15</span><span class="p">)</span>
<span class="k">assert</span> <span class="n">l_valeurs</span><span class="p">(</span><span class="n">p</span><span class="p">)</span> <span class="o">==</span> <span class="p">[</span> <span class="mi">15</span> <span class="p">]</span> 
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">l_scinde</span><span class="p">(</span><span class="n">p</span><span class="p">,</span> <span class="n">i</span><span class="p">):</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre une liste p et in indice i</span>
<span class="sd">    - scinde la liste p en deux listes dont la première possède i éléments</span>
<span class="sd">    - renvoie l&#39;indice du premier élément de la seconde sous liste (la première commence toujours à p)</span>
<span class="sd">    Exemple : maillons = [[3, 2], [8,None], [5, 1], [2,0]]</span>
<span class="sd">    &gt;&gt;&gt; p1 = 3</span>
<span class="sd">    &gt;&gt;&gt; p2 = l_scinde(p1, 2)</span>
<span class="sd">    &gt;&gt;&gt; l_valeurs(p1)</span>
<span class="sd">    &gt;&gt;&gt; [ 2, 3 ]</span>
<span class="sd">    &gt;&gt;&gt; l_valeurs(p2)</span>
<span class="sd">    &gt;&gt;&gt; [ 5, 8 ]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">maillons</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">3</span><span class="p">,</span> <span class="mi">2</span><span class="p">],</span> <span class="p">[</span><span class="mi">8</span><span class="p">,</span><span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span><span class="mi">0</span><span class="p">]]</span>
<span class="n">p1</span> <span class="o">=</span> <span class="mi">3</span>
<span class="n">p2</span> <span class="o">=</span> <span class="n">l_scinde</span><span class="p">(</span><span class="n">p1</span><span class="p">,</span> <span class="mi">2</span><span class="p">)</span>
<span class="k">assert</span> <span class="n">l_valeurs</span><span class="p">(</span><span class="n">p1</span><span class="p">)</span> <span class="o">==</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">]</span>
<span class="k">assert</span> <span class="n">l_valeurs</span><span class="p">(</span><span class="n">p2</span><span class="p">)</span> <span class="o">==</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">8</span><span class="p">]</span>
<span class="n">p2</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">l_concat</span><span class="p">(</span><span class="n">p1</span><span class="p">,</span> <span class="n">p2</span><span class="p">)</span> <span class="p">:</span>
    <span class="sd">&quot;&quot;&quot;- prend en paramètre deux listes p1 et p2</span>
<span class="sd">    - concatène (met bout à bout) les deux listes</span>
<span class="sd">    - renvoie p1 : début de la liste concaténée.</span>
<span class="sd">    Exemple : [[3, None], [8, None], [5, 1], [2, 0]]</span>
<span class="sd">    &gt;&gt;&gt; l_concat(3, 2)</span>
<span class="sd">    &gt;&gt;&gt; l_valeurs(3)</span>
<span class="sd">    &gt;&gt;&gt; [ 2, 3, 5, 8]</span>
<span class="sd">    &quot;&quot;&quot;</span>
    <span class="c1"># YOUR CODE HERE</span>
    <span class="k">raise</span> <span class="ne">NotImplementedError</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">maillons</span> <span class="o">=</span> <span class="p">[[</span><span class="mi">3</span><span class="p">,</span> <span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">8</span><span class="p">,</span> <span class="kc">None</span><span class="p">],</span> <span class="p">[</span><span class="mi">5</span><span class="p">,</span> <span class="mi">1</span><span class="p">],</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">0</span><span class="p">]]</span>
<span class="k">assert</span> <span class="n">l_concat</span><span class="p">(</span><span class="mi">3</span><span class="p">,</span> <span class="mi">2</span><span class="p">)</span> <span class="o">==</span> <span class="mi">3</span>
<span class="k">assert</span> <span class="n">l_valeurs</span><span class="p">(</span><span class="mi">3</span><span class="p">)</span> <span class="o">==</span> <span class="p">[</span><span class="mi">2</span><span class="p">,</span> <span class="mi">3</span><span class="p">,</span> <span class="mi">5</span><span class="p">,</span> <span class="mi">8</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

</div>
 
