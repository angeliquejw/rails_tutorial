---
layout: rails_installation
---

## Installation

The steps you need to take to get your computer set up with Ruby and Rails depend on the operating system you're using. Scroll down until you see the operating system that matches your computer. 

{% steps %}
{% list %}
### Mac OSX
  You must have at least **Mac OS X Lion (10.7)**

  To check your operating system: 

1.  Click the apple icon at the top left of your menu

1.  Select "About This Mac"

  When you've confirmed that your computer will work follow the [installation instructions for Mac OS X]({{site.baseurl}}/installation/mac_os/)
{% endlist %}
{% endsteps %}

{% steps %}
{% list %}
### Windows 10 

{% endlist %}
{% endsteps %}

{% steps %}
{% list %}
### Windows 8.1 

{% endlist %}
{% endsteps %}

{% steps %}
{% list %}
### Windows 7
You must have at least Windows 7 Version 6.1 (Build 7601: Service Pack 1)

To check your operating system: 

{% endlist %}
{% endsteps %} 
  
{% steps %}
{% list %}
### Ubuntu 13.04 

{% endlist %}
{% endsteps %} 

### Guides
{% for guide in site.installation %}
  <div class="guide">
    <a href="{{ site.baseurl }}{{guide.url}}" target="_self">
      {{ guide.title }}
    </a>
  </div>
{% endfor %}
