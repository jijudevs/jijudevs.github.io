---
layout: default
title: Home
nav_order: 1
description: "Welcome to jiju.co's official documentation website. This website is made for developers, agents, and other team members."
permalink: /
---

# Get to know more about jiju.co
{: .fs-9 }

Welcome to Jiju Docs., an online platform managed by the sys admin to empower both new developers, agents, and other team members. 
{: .fs-6 .fw-300 }

[Login to jiju.co](https://jiju.co/login){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Visit Agent Area](https://jiju.co/agent-area){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

The following tutorial will cover essential groundwork required to create a @jiju.co email ID and jiju.co agent profiles. Before jumping into the tutorial, let me introduce our control panel.

### CyberPanel

We use CyberPanel, a sophisticated control panel to manage our ecommerce resources, mailers, and other cool stuff. Our control panel is accessible at [mail.jiju.co:8090](https://mail.jiju.co:8090/), and it's only open for developer and admin groups. Credentials will be available upon [request](mailto:admin@jiju.co).

### How to create an email ID

Login to [mail.jiju.co:8090](https://mail.jiju.co:8090/) 

Create an email address by going to Email -> Create Email.

Fill out the form, specifying our main domain name (jiju.co), and choose an email address and password. 

![enter image description here](https://raw.githubusercontent.com/jijudevs/jijudevs.github.io/main/uploads/create-email-ID.gif)


#### Editor

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
