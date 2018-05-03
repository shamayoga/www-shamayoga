---
title: Shamayoga Teacher Training - Past Student Testimonials
description:
layout: page
hero_image:
---

    {% for testimonial in site.data.testimonials %}
       <h3>{{ testimonial.student }}</h3>
       <p>{{ testimonial.testimony }}</p>
    {% endfor %}