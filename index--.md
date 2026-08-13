<div align="center">
  <img src="{{ '/assets/img/logo.svg' | relative_url }}" 
       alt="Eu Programando" 
       width="500">
</div>
# 👋 Bem-vindo ao Eu Programando

Aqui compartilho meus projetos, ideias e tutoriais sobre programação!

## 🧠 Meus Repositórios Públicos

<ul>
{% for repo in site.github.public_repositories %}
  {% unless repo.name == "ricardoszanata.github.io" %}
    <li>
      <a href="{{ repo.html_url }}" target="_blank">{{ repo.name }}</a>
      {% if repo.description %} — {{ repo.description }}{% endif %}
    </li>
  {% endunless %}
{% endfor %}
</ul>
