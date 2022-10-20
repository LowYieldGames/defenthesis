---
layout: post
title:  "Changelog v0.0.0"
subtitle: 
excerpt_separator: "<!--more-->"
categories: 
- defenthesis
image: '/img/posts/2022-10-19-Changelogv001/Towers+gizmos_2.png'
tags:
comments: true
id: 2022-10-19-Changelogv000
---

Excerpt goes here. 

<!--more-->
<br>

### ADDED
- (new features)
- gifs showing new features w/ short description

### CHANGED
- (sideways, not fixed)
- gifs showing difference between old and new w/ short description

### FIXED
- (was buggy, now it's not)
- gifs showing buggy version vs. non-buggy version

### REMOVED
- no gifs needed, or gif showing the problem if it is applicable

### UP NEXT

---

## THOUGHTS
- Discussion about the how and why things were changed, added, or removed
- Lots of technical depth if needed

## RESOURCES
- Links to cool resources that I find

## MUSIC
Link to song

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    var disqus_config = function () {
    this.page.url = "{{ site.url }}{{ page.url }}";  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = "{{ page.id }}"; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://https-lowyieldgames-github-io-defenthesis.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();    
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}