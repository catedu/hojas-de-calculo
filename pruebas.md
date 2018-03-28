# Página de pruebas

{% filter title %}
may the force be with you
{% endfilter %}

{% filter replace("force", "forth") %}
may the force be with you
{% endfilter %}

{% for collaborator in book.collaborators %}
* {{ collaborator.name }}
{% endfor %}

{% include "FOOTER.md" %}