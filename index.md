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

Login to [mail.jiju.co:8090](https://mail.jiju.co:8090/). Create an email address by going to Email -> Create Email. Fill out the form, specifying our main domain name (jiju.co), and choose an email address and password. 

![How to create an email ID](https://raw.githubusercontent.com/jijudevs/jijudevs.github.io/main/uploads/jiju-create-email-ID.gif)

### How to use the mailbox

Visit [jiju.co/mail](https://jiju.co/mail) and login with the rightful credentials.

### How to create an agent profile

Visit [https://jiju.co/wp-admin/user-new.php](https://jiju.co/wp-admin/user-new.php) to create the agent profile. Only admin groups have the permissions to add, edit, and delete users. 

![how to create agent profile on jiju.co](https://raw.githubusercontent.com/jijudevs/jijudevs.github.io/main/uploads/add-new-user.png)

While adding a new agent, make sure to: 
* Fill in the right username and email ID. 
* Set the site language to Simplified Chinese. 
* Set the role as shop manager.
* Set ☑ for **Add the user as an affiliate**.

### Setting short URL and UTM tags.

By default, our agent URL structure is https://jiju.co/agent/tom. But we're to add the tracking parameters, and shorten the URL further.

The tracking URL structure: https://jiju.co/agent/tom/?utm_source=web&utm_medium=marketing&utm_campaign=tom

This is the universal structure, and you can replace "tom" with the agent username. For example, if it's "alice" is one of our agents, the tracking URL would be: https://jiju.co/agent/alice/?utm_source=web&utm_medium=marketing&utm_campaign=alice

Now that we've created the tracking URL. The next step is to prettify the URL and share it with team leaders. We use a plugin called **Redirection** for the same. Which is accessible by visiting [https://jiju.co/wp-admin/tools.php?page=redirection.php](https://jiju.co/wp-admin/tools.php?page=redirection.php)

Once you're the **Redirection** dashboard, you can shorten the URL as follows:

![add redirection](https://raw.githubusercontent.com/jijudevs/jijudevs.github.io/main/uploads/redirection-set-up.png)
Essentially **https://jiju.co/tom** would redirect to **https://jiju.co/agent/tom/?utm_source=web&utm_medium=marketing&utm_campaign=tom**, which contains both the Affiliate WP and Google Analytics tracking parameters.

**Note:** Affiliate WP is a plugin we use to manage the agent profiles. Please refer to [affiliate area overview](https://docs.affiliatewp.com/article/54-creating-the-affiliate-area) to understand the logic behind that plugin.


#### Editor

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
