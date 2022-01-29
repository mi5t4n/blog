---
title: Enable order split from admin dashboard in dokan plugin
date: "2019-05-08T23:46:37.121Z"
template: "post"
draft: false
slug: "enable-order-split-from-admin-dashboard-in-dokan-plugin"
category: "WordPress"
tags:
  - "Dokan"
description: "Dokan is a multi-vendor plugin developed by the weDevs. It works along side with the WooCommerce to allow the multi-vendor capability to the WooCommerce website."
socialImage: "https://miro.medium.com/max/700/0*u7N8y7HZmCnhpmJV"
---

![](https://miro.medium.com/max/700/0*u7N8y7HZmCnhpmJV)
*<p align="center">
Dokan Photo by [Shahadat Shemul](https://unsplash.com/@shemul) on [Unsplash](https://unsplash.com)</p>*

[Dokan](https://wedevs.com/dokan) is a multi-vendor plugin developed by the [weDevs](https://wedevs.com/). It works along side with the WooCommerce to allow the multi-vendor capability to the WooCommerce website.

In a multi-vendor website based on Dokan plugin, when an order is created containing products from multiple vendors. The order is split by creating sub-order for each vendor. When a customer creates order from front-end, the order is split perfectly. But when the order is created from the administrator dashboard, the order is not split. Use the following code snipped to enable the order split from the dashboard.

`gist:mi5t4n/03d9c578707d8c8dfa9a251a1e2d0ae4#dokan-order-split-from-backend.php`