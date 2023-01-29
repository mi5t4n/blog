---
title: Enable order split from admin dashboard in dokan plugin
date: "2019-05-08T23:46:37.121Z"
template: "post"
draft: false
slug: "enable-order-split-from-admin-dashboard-in-dokan-plugin"
category: "WordPress, Dokan"
tags:
  - "Dokan, E-Commerce, Multi-Vendor"
description: "Split order to sub-orders according to vendors when order is created form backend."
socialImage: "https://miro.medium.com/max/700/0*u7N8y7HZmCnhpmJV"
---

![](https://miro.medium.com/max/700/0*u7N8y7HZmCnhpmJV)
*<p align="center">
Dokan Photo by [Shahadat Shemul](https://unsplash.com/@shemul) on [Unsplash](https://unsplash.com)</p>*

The multi-vendor plugin [Dokan](https://wedevs.com/dokan) was created by the [weDevs](https://wedevs.com/). It works in tandem with WooCommerce to give the WooCommerce website the flexibility to support multiple vendors.

When an order is placed with goods from various merchants on a multi-vendor website powered by the Dokan plugin. To divide the order, separate sub-orders are created for each vendor. The split of the order is perfect when a consumer creates it from the front-end. However, the order is not separated when it is created from the administrator dashboard. To make the order split from the dashboard available, use the following snippet of code.

`gist:mi5t4n/03d9c578707d8c8dfa9a251a1e2d0ae4#dokan-order-split-from-backend.php`
