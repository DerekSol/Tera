---
keywords: fastai
title: 3.6 Conditionals
author: Derek Sol
categories: [APCSP Week 14]
nb_path: _notebooks/2022-11-29-conditionspresent.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-11-29-conditionspresent.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Focusing-on-Selection">Focusing on Selection<a class="anchor-link" href="#Focusing-on-Selection"> </a></h2><p><strong>Selection</strong>: uses a condition that evaluates if it is <i>true</i> or <i>false</i></p>
<p><img src="https://github.com/DerekSol/Tera/blob/6e3f337611b765e6609eccc558c73ce595ab2d6e/images/selectiondiagram.png" alt=""></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Conditional-Statements">Conditional Statements<a class="anchor-link" href="#Conditional-Statements"> </a></h2><p>Also known as "If-statements"</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><img src="https://github.com/DerekSol/Tera/blob/03db8e5a9938b4f4356407b68056ccdc5e2deacb/images/ifstatement.png" alt=""></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Can be seen as if statements or if blocks</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="mi">4</span>
<span class="n">y</span> <span class="o">=</span> <span class="mi">10</span>
<span class="k">if</span> <span class="n">y</span> <span class="o">&gt;</span> <span class="n">x</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;y is greater than x&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>y is greater than x
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Can also be seen as if else statements or if else blocks</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><img src="https://github.com/DerekSol/Tera/blob/03db8e5a9938b4f4356407b68056ccdc5e2deacb/images/ifelsestatement.png" alt=""></p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="mi">4</span>
<span class="n">y</span> <span class="o">=</span> <span class="mi">10</span>
<span class="k">if</span> <span class="n">y</span> <span class="o">&gt;</span> <span class="n">x</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;y is greater than x&quot;</span><span class="p">)</span>
<span class="k">else</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;y is less than x&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>y is greater than x
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

