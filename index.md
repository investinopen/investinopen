---
layout: default
title: "Home"
---
<h2>Our Statement</h2>
<p>We imagine a world in which communities of researchers, scholars, and knowledge workers across the globe are fully enabled to share, discover, and work together. It is clear that the needs of today’s diverse scholarly communities are not being met by the existing largely uncoordinated scholarly infrastructure, which is dominated by vendor products that take ownership of the scholarly process and data. We intend to create a new open infrastructure system that will enable us to work in a more integrated, collaborative and strategic way. It will support global connections and consistency where it is appropriate, and local and contextual requirements where that is needed. <b><a href="/docs/statement0.2">Read more ></a></b></p>
<columns>
  <left>
    <components>
      <component>
        <h2>Join the Census</h2>
        <p>The Census of Scholarly Communication Infrastructure is now open. We invite projects and programs, for profit and nonprofit corporations, and hosted initiatives of all kinds to contribute to this growing body of information. <b><a href="/census">Complete the census ></a></b></p>
      </component>
      <component>
        <h2>Recent & Upcoming Events</h2>
        <h3>IOI Launch Webinar</h3>
        <p><a href="/2019/05/28/ioi-launch-webinar.html">View a recording</a> of the 28 May webinar to hear about the Invest in Open Infrastructure project from members of the community and learn how you can get involved.</p>
      </component>
    </components>
  </left>
  <right>
    <components>
      <component>
        {% for item in site.posts limit:1 %}
          <h2>{{ item.title }}</h2>
          {{ item.excerpt }} <b><a href="{{ item.url }}">Read more ></a></b>
        {% endfor %}
      </component>
    </components>
  </right>
</columns>
