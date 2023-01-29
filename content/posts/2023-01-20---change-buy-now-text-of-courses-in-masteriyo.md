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
socialImage: "https://images.pexels.com/photos/289737/pexels-photo-289737.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
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
