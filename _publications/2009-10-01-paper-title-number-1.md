---
title: "Apontamentos Criptografia"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Estes apontamentos são relativos à cadeira de Criptografia.'
date: 2024-09-15
venue: 'Apontamentos Criptografia'
slidesurl: 'https://v1dal9.github.io/mcs_github.io/files/slides1.pdf'
paperurl: 'https://v1dal9.github.io/mcs_github.io/files/paper1.pdf'
paperurl2: 'https://v1dal9.github.io/mcs_github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
{% include base_path %}

{% if post.id %}
  {% assign title = post.title | markdownify | remove: "<p>" | remove: "</p>" %}
{% else %}
  {% assign title = post.title %}
{% endif %}

<div class="{{ include.type | default: "list" }}__item">
  <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
    <div>
        <p>
            <a href=" https://v1dal9.github.io/mcs_github.io/files/paper1.pdf ">Introdução à Criptografia</a>
        </p>
        <p>
            The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. 
        <p>
    </div>
    <div>
        <p>
            <a href=" https://v1dal9.github.io/mcs_github.io/files/paper1.pdf ">Introdução à criptografia 2</a>
        </p>
        <p>
            The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader.
        </p>
    </div>
  </article>
</div>

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.