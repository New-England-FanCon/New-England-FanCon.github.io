---
permalink: /guests


feature_row:
  - image_path: /assets/images/placeholderguy.gif
    alt: "placeholder silhouette image with question mark"
    title: "Coming soon!"
    excerpt: 'Special guests will be announced shortly! Check back soon for all the latest updates.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/placeholderguy.gif
    alt: "placeholder silhouette image with question mark"
    title: "Coming soon!"
    excerpt: 'Special guests will be announced shortly! Check back soon for all the latest updates.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

<style>
.initial-content {
  padding: 0 1em;
}

h3 {
  margin: 1em 0;
}
</style>

<p>Check back soon for celebrity guest announcements! Sign up for our mailing list and follow us on socials to be the first in the know!</p>

{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}
