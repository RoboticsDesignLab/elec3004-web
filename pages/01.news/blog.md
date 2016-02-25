---
title: news
blog_url: news
menu: News

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true

feed:
    description: ELEC3004 News
    limit: 10

pagination: true
---
