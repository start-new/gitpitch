# {{ cookiecutter.presentation_title }}

{% if cookiecutter.presentation_subtitle %}

---
## {{ cookiecutter.presentation_subtitle }}
{% endif %}

---
@snap[span-100]
## {{ cookiecutter.author }} {% if cookiecutter.email %}[{{ cookiecutter.email }}]{% endif %}
@snapend
{% if cookiecutter.biography_line %}{{ cookiecutter.biography_line }}{% endif %}

---

