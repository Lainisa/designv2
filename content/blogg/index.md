---
views:
    main:
        template: anax/v2/article/default
        data:
            class: blog

    byline: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: anax/v2/blog-list/default
        sort: 2
        data:
            dateFormat: j F Y
            meta:
                type: toc
                orderby: publishTime
                orderorder: desc

    blog-toc:
        region: sidebar-right
        template: anax/v2/blog-toc/default
        sort: 2
        data:
            meta:
                type: copy
                view: blog-list

---
Bildblogg
===========================

En bildblogg som en del av kursmomentet kmom05 ht lp 2018.

Ute är det full vinter i Kläppen, med vita toner och tjock snödimma. Jag behöver lite färg, så därför plockar jag fram mina gamla bilder från torpet i Hedesunda.
