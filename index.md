# ✨ Kelly's Writing Portfolio

## 📚 Early Reader Fiction
{% for item in site.early_reader %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

## ⚡ Flash Fiction
{% for item in site.flash_fiction %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

## 🧠 Nonfiction Blog
{% for item in site.nonfiction_blog %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

## ✍️ Writing Prompts
{% for item in site.prompts %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
