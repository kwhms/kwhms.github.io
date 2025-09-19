# ✨ Kelly's Writing Portfolio

## 📚 Early Reader Fiction
{% for item in site.fiction_early_reader_gal %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

## ⚡ Flash Fiction
{% for item in site.flash_fiction_reedsy %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

## 🧠 Nonfiction Blog
{% for item in site.nonfiction_blog %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

## ✍️ Writing Prompts
{% for item in site.prompts_freewrite %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
