---
title: Modify the Masteriyo courses' "Buy Now" text.
date: "2023-01-30T23:46:37.121Z"
template: "post"
draft: false
slug: "modify-the-masteriyo-courses-buy-now-text"
category: "WordPress, Masteriyo"
tags:
  - "Masteriyo, LMS, Learning Management System"
description: "For each course and course page on Masteriyo, there is a \"Buy Now\" text link. You can modify the wording in the excerpt below to whatever you choose."
socialImage: "https://miro.medium.com/max/700/0*u7N8y7HZmCnhpmJV"
---
[Masteriyo](https://wordpress.org/plugins/learning-management-system/) is a contemporary LMS that relies on react for quick responses. For each course and course page on Masteriyo, there is a "Buy Now" text link. You can modify the wording in the excerpt below to whatever you choose.

```php
add_filter( 'masteriyo_course_add_to_cart_text', function( $text ) {
	return __( 'Buy Right Now', 'textdomain' );
});

add_filter( 'masteriyo_single_course_add_to_cart_text', function( $text ) {
	return __( 'Buy Right Now', 'textdomain' );
});

```
