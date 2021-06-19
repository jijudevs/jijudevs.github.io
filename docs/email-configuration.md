---
layout: default
title: Email Configuration
nav_order: 2
---

# Email Configuration
{: .no_toc }

Email configuration to connect mail.jiju.co with external mailers.
{: .fs-6 .fw-300 }

## Full details to configure mail clients

|**POP3**|**Details**|
|--|--|
|Server Hostname|mail.jiju.co|
|Port|110|
|Port|995 (SSL)|
|SSL|STARTTLS|

|**IMAP**|**Details**|
|--|--|
|Server Hostname|mail.jiju.co|
|Port|143|
|Port|993 (SSL)|
|SSL|STARTTLS|

|**SMTP**|**Details**|
|--|--|
|Server Hostname|mail.jiju.co|
|Port|25|
|Port|587 (SSL)|
|Port|465 (SSL)|
|SSL|STARTTLS|


#### Editor

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
