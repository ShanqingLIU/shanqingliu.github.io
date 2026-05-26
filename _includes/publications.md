<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>

<div class="publications">

{% if site.data.publications.preprint.size > 0 %}

<h3 id="preprint">Preprint</h3>

<ol class="bibliography">

{% for link in site.data.publications.preprint %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title">[p{{ forloop.index }}] {{ link.title }}</div>
      <div class="author">{{ link.authors }}</div>
      {% if link.conference %}
      <div class="periodical"><em>{{ link.conference }}</em></div>
      {% endif %}
    <div class="links">
      {% if link.doi %}
      <a target="_blank" href="{{ link.doi }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">DOI</a>
      {% endif %}
      {% if link.pdf %}
      <a target="_blank" href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.arxiv %}
      <a target="_blank" href="{{ link.arxiv }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">Arxiv</a>
      {% endif %}
      {% if link.hal %}
      <a target="_blank" href="{{ link.hal }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">HAL</a>
      {% endif %}
      {% if link.code %}
      <a target="_blank" href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.others %}
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>

{% endif %}


{% if site.data.publications.journal_published.size > 0 %}

<h3 id="journal">Journal</h3>

<ol class="bibliography">

{% for link in site.data.publications.journal_published %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title">[j{{ forloop.index }}] {{ link.title }}</div>
      <div class="author">{{ link.authors }}</div>
      {% if link.conference %}
      <div class="periodical"><em>{{ link.conference }}</em></div>
      {% endif %}
    <div class="links">
      {% if link.doi %}
      <a target="_blank" href="{{ link.doi }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">DOI</a>
      {% endif %}
      {% if link.pdf %}
      <a target="_blank" href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.arxiv %}
      <a target="_blank" href="{{ link.arxiv }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">Arxiv</a>
      {% endif %}
      {% if link.hal %}
      <a target="_blank" href="{{ link.hal }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">HAL</a>
      {% endif %}
      {% if link.code %}
      <a target="_blank" href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.others %}
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>

{% endif %}


{% if site.data.publications.conference_proceedings.size > 0 %}

<h3 id="conference-proceedings">Proceedings of Conference</h3>

<ol class="bibliography">

{% for link in site.data.publications.conference_proceedings %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title">[c{{ forloop.index }}] {{ link.title }}</div>
      <div class="author">{{ link.authors }}</div>
      {% if link.conference %}
      <div class="periodical"><em>{{ link.conference }}</em></div>
      {% endif %}
    <div class="links">
      {% if link.doi %}
      <a target="_blank" href="{{ link.doi }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">DOI</a>
      {% endif %}
      {% if link.pdf %}
      <a target="_blank" href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.arxiv %}
      <a target="_blank" href="{{ link.arxiv }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">Arxiv</a>
      {% endif %}
      {% if link.hal %}
      <a target="_blank" href="{{ link.hal }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">HAL</a>
      {% endif %}
      {% if link.code %}
      <a target="_blank" href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.others %}
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>

{% endif %}


{% if site.data.publications.phdthesis.size > 0 %}

<h3 id="phd-thesis">Ph.D. thesis</h3>

<ol class="bibliography">

{% for link in site.data.publications.phdthesis %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title">{{ link.title }}</div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><i>{{ link.location }}</i></div>
    <div class="links">
      {% if link.link %}
      <a target="_blank" href="{{ link.link }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">THESES.FR</a>
      {% endif %}
      {% if link.hal %}
      <a target="_blank" href="{{ link.hal }}" class="btn btn-sm z-depth-0" role="button" style="font-size:12px;">HAL</a>
      {% endif %}
      {% if link.others %}
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>

{% endif %}

</div>
