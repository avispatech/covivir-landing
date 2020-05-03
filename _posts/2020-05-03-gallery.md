{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  ![myimage]({{ myimage.path }})
{% endfor %}

![01](https://covivir.avispa.work/assets/images/01.png)
