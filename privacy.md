<h1>Privacy Policy</h1>

{% include core/privacy/01-intro.html %}

{% include core/privacy/02-general.html %}

{% include core/privacy/03-website.html %}

{% if include.affiliate == nil %}
{% include core/privacy/04-advertisement.html %}
{% endif %}

{% include core/privacy/05-other.html %}
