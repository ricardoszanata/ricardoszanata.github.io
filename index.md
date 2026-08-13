<div align="center">

  <img src="{{ '/assets/img/logo.svg' | relative_url }}"
       alt="Eu Programando"
       width="420">

  <p>
    <strong>Blog e portfólio de projetos de programação do Prof. Rick</strong>
  </p>

</div>

---

# 👋 Bem-vindo ao Eu Programando

Aqui compartilho meus **projetos, ideias e tutoriais sobre programação**!

Este espaço reúne meus projetos desenvolvidos ao longo da minha jornada como desenvolvedor e professor, além de conteúdos para quem está começando ou deseja aprimorar seus conhecimentos em programação.

---

## 🧠 Meus Repositórios Públicos

<ul>
{% for repo in site.github.public_repositories %}
  {% unless repo.name == "ricardoszanata.github.io" %}
    <li>
      <a href="{{ repo.html_url }}" target="_blank">
        <strong>{{ repo.name }}</strong>
      </a>

      {% if repo.description %}
        — {{ repo.description }}
      {% endif %}
    </li>
  {% endunless %}
{% endfor %}
</ul>

---

## 💻 O que você encontrará por aqui

- 🐘 PHP e MySQL
- 🌐 Desenvolvimento Web
- 🐍 Python
- ☕ JavaScript
- 🖥️ Delphi / Lazarus
- 📱 Desenvolvimento Mobile
- 🗄️ Banco de Dados
- ⚙️ APIs
- 🤖 Projetos envolvendo tecnologia e IA
- 🎓 Conteúdos e materiais para estudantes

---

## 📚 Conteúdos e Tutoriais

A ideia do **Eu Programando** é também compartilhar tutoriais e projetos desenvolvidos passo a passo.

Aqui você poderá encontrar exemplos práticos, códigos-fonte e explicações para utilizar em seus próprios estudos e projetos.

---

## 👨‍💻 Sobre o Eu Programando

O **Eu Programando** é um espaço dedicado à programação, desenvolvimento de sistemas e compartilhamento de conhecimento.

Meu objetivo é transformar projetos e experiências reais em conteúdos que possam ajudar outros desenvolvedores e estudantes.

---

<div align="center">

### 🚀 Vamos programar?

**Aprender programação é colocar a mão no código.**

</div>