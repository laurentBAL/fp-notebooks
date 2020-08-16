---
keywords: fastai
description: Fastpages Notebook Blog Post
title: Découverte de l'environnement Jupyter
toc: true
badges: true
comments: true
categories: [jupyter, formation]
image: https://respawner.fr/blog/public/Divers/.python_t.jpg
nb_path: _notebooks/2020-03-07-Formation_Python_Fonctions.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2020-03-07-Formation_Python_Fonctions.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Concr&#234;tement,-comment-&#231;a-marche-?">Concr&#234;tement, comment &#231;a marche ?<a class="anchor-link" href="#Concr&#234;tement,-comment-&#231;a-marche-?"> </a></h2><p>Il y a deux type de cellules :</p>
<ul>
<li>les cellules contenant du texte (<em>Markdown</em>, <em>Headers</em>)</li>
<li>les cellules contenant des instructions Python : <code>In [ ]</code></li>
</ul>
<p>Vous pouvez à tout moment changer le type d'une cellule grâce à la liste déroulante sur la barre d'outils. Vous pouvez choisir entre :</p>
<ul>
<li>code : la cellule contient alors des instructions Python qui seront interprétées</li>
<li>Markdown : la cellule contient alors du texte qui sera juste affiché</li>
<li>Heading x : la cellule s'affichera comme un titre de section.</li>
</ul>
<p>Pour valider une cellule, appuyez sur la touche <code>shift-enter</code> ou bien cliquez sur le bouton <button> >| </button> de la barre d'icônes.</p>
<p>Regardez ci-dessous votre première ligne de code Python : Simple n'est-ce pas ?</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<details class="description">
      <summary class="btn btn-sm" data-open="Hide Code" data-close="Show Code"></summary>
        <p><div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#collapse</span>
<span class="c1"># Ceci est une cellule Python</span>
<span class="c1"># Le code qu&#39;elle contient peut être exécuté</span>
<span class="c1"># en tapant Shift+Entrée</span>

<span class="nb">print</span><span class="p">(</span><span class="mi">1</span><span class="o">+</span><span class="mi">1</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>
</p>
    </details>
</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Et-la-p&#233;dagogie-dans-tout-&#231;a-?">Et la p&#233;dagogie dans tout &#231;a ?<a class="anchor-link" href="#Et-la-p&#233;dagogie-dans-tout-&#231;a-?"> </a></h2><p>Grâce à l'environnement Jupyter, l'élève a sous les yeux les consignes du professeur ainsi que l'outil lui permettant de les réaliser, le tout dans un environnement familier qu'est le navigateur internet. Prenons un exemple d'activité d'algorithmique.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Coordonn&#233;es-du-milieu-d'un-segment">Coordonn&#233;es du milieu d'un segment<a class="anchor-link" href="#Coordonn&#233;es-du-milieu-d'un-segment"> </a></h1><p>On rappelle la formule : si $I$ est le milieu de $[AB]$, $$I=\left( \dfrac{x_A+x_B}{2};\dfrac{x_A+x_B}{2} \right)$$</p>
<p><em>Oui, je sais que vous le savez mais c'est pour frimer avec l'insertion de formules $\LaTeX$ dans Jupyter !!</em></p>
<p><strong>Revenons aux choses sérieuses...</strong></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Compl&#233;ter-l'algorithme-ci-dessous,-&#233;crit-en-langage-naturel">Compl&#233;ter l'algorithme ci-dessous, &#233;crit en langage naturel<a class="anchor-link" href="#Compl&#233;ter-l'algorithme-ci-dessous,-&#233;crit-en-langage-naturel"> </a></h2><ul>
<li>Pour modifier l'algorithme, double-cliquez sur la cellule puis complétez les blancs.</li>
<li>Pour valider votre travail, tapez <strong><em>Shift+Entree</em></strong></li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Algorithme">Algorithme<a class="anchor-link" href="#Algorithme"> </a></h3>
<pre><code>Définir la fonction milieu qui prend 4 pamamètres : xA, yA, xB, yB
    xI prend la valeur ...
    yI prend la valeur ...
    retourner ...
Fin de la fonction milieu

Appeler la fonction ... avec les paramètres ...
Stocker les résultats dans les variables xI et yI</code></pre>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Codage de l&#39;algorithme en Python</span>
<span class="c1"># Remplacez les ... par ce qui va bien :)</span>

<span class="k">def</span> <span class="nf">milieu</span><span class="p">(</span><span class="n">xA</span><span class="p">,</span><span class="n">yA</span><span class="p">,</span><span class="n">xB</span><span class="p">,</span><span class="n">yB</span><span class="p">):</span>
    <span class="n">xI</span><span class="o">=...</span>
    <span class="n">yI</span><span class="o">=...</span>
    <span class="k">return</span> <span class="o">...</span>

<span class="n">xI</span><span class="p">,</span><span class="n">yI</span><span class="o">=</span><span class="n">milieu</span><span class="p">(</span><span class="o">...</span><span class="p">)</span>
<span class="p">(</span><span class="n">xI</span><span class="p">,</span><span class="n">yI</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Nous avons ainsi créé une <strong><em>fonction</em></strong> python. Cela nous permet d'enrichir le langage python avec nos propres commandes. Maintenant, notre langage préféré sais calculer des milieux !!</p>
<p>Validez les cellules ci-dessous pour vous en convaincre.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">milieu</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">5</span><span class="p">,</span><span class="mi">6</span><span class="p">)</span>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">milieu</span><span class="p">(</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">5</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Tiens c'est bizarre, on dirait que c'est le même milieu. Vérifions avec Python !</p>
<p>Validez la cellule ci-dessous.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">milieu</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">5</span><span class="p">,</span><span class="mi">6</span><span class="p">)</span><span class="o">==</span><span class="n">milieu</span><span class="p">(</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">5</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Remarquez la présence du symbole <strong><em>==</em></strong> pour <strong>tester</strong> l'égalité de deux objets. Il ne faut pas le confondre avec le symbole <strong><em>=</em></strong> qui permet d'<strong>affecter</strong> une valeur à une variable.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Compl&#233;tez-:">Compl&#233;tez :<a class="anchor-link" href="#Compl&#233;tez-:"> </a></h3><p>Soient A(1;...) B(...;...) C(5;...) D(...;...)</p>
<p>Les segments [AC] et [BD] ont même milieu donc le quadrilatère ... est un ...</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Ecrire-une-nouvelle-fonction">Ecrire une nouvelle fonction<a class="anchor-link" href="#Ecrire-une-nouvelle-fonction"> </a></h2><p>En vous aidant de la démarche précédente, complétez la définition d'une fonction <strong><em>estParallelogramme</em></strong> prenant en arguments les coordonnées de 4 points A, B, C et D puis retournant <strong>Vrai</strong> ou <strong>Faux</strong> selon que le quadrilatère ABCD est un parallélogramme ou pas.</p>

<pre><code>Définir la fonction ... qui prend ... pamamètres : ...
    test prend la valeur ...
retourner ...
Fin de la fonction ...

Entrées :
    Saisir ...
Traitement :
    Appeler la fonction ... avec les paramètres ...
    Stocker le résultat dans la variable ...
Sortie :
    Afficher ...</code></pre>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Codez à présent cette fonction dans cette cellule</span>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># On vérifie que cela marche. La cellule doit afficher True</span>
<span class="n">test</span><span class="o">=</span><span class="n">estParallelogramme</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">5</span><span class="p">,</span><span class="mi">6</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">5</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">test</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Application">Application<a class="anchor-link" href="#Application"> </a></h2><p>Utiliser la fonction que l'on vient de définir pour dire si le quadrilatère ABCD est un parallélogramme :</p>
<p>$A\left(-2;2\right)$ $B\left(\dfrac 2 5;-\dfrac 6 5\right)$ $C\left(4;\dfrac 2 5\right)$ $D\left(\dfrac 9 5;3\right)$</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># A vous de jouer</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Oui-mais-je-veux-voir-la-figure-!!">Oui mais je veux voir la figure !!<a class="anchor-link" href="#Oui-mais-je-veux-voir-la-figure-!!"> </a></h2><p>Pas de panique, validez la cellule ci-dessous et vous pourrez facilement afficher des points ou des segments dans Jupyter.</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="o">%</span><span class="k">pylab</span> inline
<span class="c1">## Pour cette section on définit deux fonctions </span>

<span class="k">def</span> <span class="nf">trace_point</span><span class="p">(</span><span class="n">P</span><span class="p">,</span><span class="n">nom</span><span class="o">=</span><span class="s2">&quot;&quot;</span><span class="p">):</span>
    <span class="n">plot</span><span class="p">(</span><span class="n">P</span><span class="p">[</span><span class="mi">0</span><span class="p">],</span><span class="n">P</span><span class="p">[</span><span class="mi">1</span><span class="p">],</span><span class="s2">&quot;ro&quot;</span><span class="p">)</span>
    <span class="n">text</span><span class="p">(</span><span class="n">P</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="o">-</span><span class="p">(</span><span class="n">P</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span><span class="o">-</span><span class="n">P</span><span class="p">[</span><span class="mi">0</span><span class="p">])</span><span class="o">/</span><span class="mi">6</span><span class="p">,</span><span class="n">P</span><span class="p">[</span><span class="mi">1</span><span class="p">],</span> <span class="n">nom</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;r&#39;</span><span class="p">)</span>
<span class="k">def</span> <span class="nf">trace_segment</span><span class="p">(</span><span class="n">P</span><span class="p">,</span><span class="n">Q</span><span class="p">):</span>
    <span class="n">plot</span><span class="p">([</span><span class="n">P</span><span class="p">[</span><span class="mi">0</span><span class="p">],</span><span class="n">Q</span><span class="p">[</span><span class="mi">0</span><span class="p">]],[</span><span class="n">P</span><span class="p">[</span><span class="mi">1</span><span class="p">],</span><span class="n">Q</span><span class="p">[</span><span class="mi">1</span><span class="p">]],</span><span class="s2">&quot;b&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>tadaaaaa...</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># et on définit si on souhaite l&#39;échelle de notre repère</span>
<span class="n">xlim</span><span class="p">(</span><span class="o">-</span><span class="mi">5</span><span class="p">,</span><span class="mi">5</span><span class="p">)</span> <span class="c1"># On met ici l&#39;échelle sur l&#39;axe des abscisses</span>
<span class="n">ylim</span><span class="p">(</span><span class="o">-</span><span class="mi">5</span><span class="p">,</span><span class="mi">5</span><span class="p">)</span> <span class="c1"># et la l&#39;adresse sur l&#39;axe des ordonnées</span>
<span class="n">grid</span><span class="p">()</span>

<span class="n">A</span><span class="o">=</span><span class="p">(</span><span class="o">-</span><span class="mi">2</span><span class="p">,</span><span class="mi">2</span><span class="p">)</span>
<span class="n">B</span><span class="o">=</span><span class="p">(</span><span class="mi">2</span><span class="o">/</span><span class="mi">5</span><span class="p">,</span><span class="o">-</span><span class="mi">6</span><span class="o">/</span><span class="mi">5</span><span class="p">)</span>
<span class="n">C</span><span class="o">=</span><span class="p">(</span><span class="mi">4</span><span class="p">,</span><span class="o">-</span><span class="mi">1</span><span class="o">/</span><span class="mi">5</span><span class="p">)</span>
<span class="n">D</span><span class="o">=</span><span class="p">(</span><span class="mi">8</span><span class="o">/</span><span class="mi">5</span><span class="p">,</span><span class="mi">3</span><span class="p">)</span>
<span class="n">trace_point</span><span class="p">(</span><span class="n">A</span><span class="p">,</span><span class="s2">&quot;A&quot;</span><span class="p">)</span>
<span class="n">trace_point</span><span class="p">(</span><span class="n">B</span><span class="p">,</span><span class="s2">&quot;B&quot;</span><span class="p">)</span>
<span class="n">trace_point</span><span class="p">(</span><span class="n">C</span><span class="p">,</span><span class="s2">&quot;C&quot;</span><span class="p">)</span>
<span class="n">trace_point</span><span class="p">(</span><span class="n">D</span><span class="p">,</span><span class="s2">&quot;D&quot;</span><span class="p">)</span>
<span class="n">trace_segment</span><span class="p">(</span><span class="n">A</span><span class="p">,</span><span class="n">B</span><span class="p">)</span>
<span class="n">trace_segment</span><span class="p">(</span><span class="n">B</span><span class="p">,</span><span class="n">C</span><span class="p">)</span>
<span class="n">trace_segment</span><span class="p">(</span><span class="n">C</span><span class="p">,</span><span class="n">D</span><span class="p">)</span>
<span class="n">trace_segment</span><span class="p">(</span><span class="n">D</span><span class="p">,</span><span class="n">A</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="C'est-g&#233;nial-Python,-je-le-veux-je-le-veux-!!">C'est g&#233;nial Python, je le veux je le veux !!<a class="anchor-link" href="#C'est-g&#233;nial-Python,-je-le-veux-je-le-veux-!!"> </a></h1><p>Python est un langage libre, gratuit et multiplateforme. Il sest disponible sur Window$, Linux, mac, ainsi que sur smartphones et tablettes Apple ou Androhideux.</p>
<p>Pour télécharger Python, vous pouvez vous rendre sur le site officiel <a href="http://python.org">http://python.org</a> et choisir la version 3.6.2, mais cela n'installera que l'environnement très basique <strong><em>IDLE</em></strong>.</p>
<p>Pour avoir Python dans l'environnement Jupyter que l'on vient d'utiliser, je recommande d'installer la distribution clé en main <a href="https://www.anaconda.com/download/">Anaconda</a></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Je-veux-Python-mais-je-ne-veux/peux-rien-installer-sur-mon-ordinateur">Je veux Python mais je ne veux/peux rien installer sur mon ordinateur<a class="anchor-link" href="#Je-veux-Python-mais-je-ne-veux/peux-rien-installer-sur-mon-ordinateur"> </a></h2><p>Pas de panique, il existe des environnements prêts à l'emploi disponible sur internet :</p>
<ul>
<li><a href="https://try.jupyter.org/">https://try.jupyter.org/</a> est un environnement jupyter complet prêt à l'emploi mais attention, les classeurs réalisés sur ce site sont temporaires, c'est à dire détruits à la déconnexion. Il faut donc bien penser à télécharger en local son travail avant de quitter...</li>
<li><a href="https://repl.it/languages/python3">https://repl.it/languages/python3</a> est un environnement entièrement en ligne du type IDLE donc console + éditeur de programme. Cela permet de tester rapidement un petit programme</li>
<li><a href="http://pythontutor.com/">http://pythontutor.com/</a> est un peu différent car il permet une exécution pas à pas des programme avec visualisation en temps réel du contenu des variables ce qui est un formidable outil pédagogique et de débuggage !</li>
</ul>

</div>
</div>
</div>
</div>
 
