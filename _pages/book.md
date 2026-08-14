---
permalink: /book/
title: "ToM4AI book"
author_profile: true
redirect_from: 
  - /book.html
---

Our book on Theory of Mind for Artificial Intelligence is coming soon.

If you would like to be among the first to hear about the launch, publication updates, and related announcements, subscribe below.

## Subscribe for book updates

{% if site.book_news.form_action and site.book_news.form_action != "" %}
<div id="book-subscribe-success" style="display:none; padding: 0.8rem 1rem; margin-bottom: 1rem; border-left: 4px solid #2d6a4f; background: #edf7f1;">
  Thanks for signing up. You are on the list for updates about the ToM4AI book. We will be in touch with launch news and related announcements.
</div>

<form action="{{ site.book_news.form_action }}" method="POST" class="form">
  <label for="book-news-email">Email address</label>
  <input id="book-news-email" name="email" type="email" placeholder="name@example.com" required>

  <label class="checkbox" for="book-news-consent">
    <input id="book-news-consent" name="consent" type="checkbox" required>
    I consent to receive email updates about the ToM4AI book, including launch announcements and related news. I understand my email will be used only for this purpose and will not be shared with third parties.
  </label>

  <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off">
  <input type="hidden" name="_subject" value="New ToM4AI book subscription">
  <input type="hidden" name="source" value="book page">
  <input type="hidden" name="_next" value="{{ site.url }}{{ site.baseurl }}{{ site.book_news.success_redirect | default: '/book/?subscribed=1' }}">

  <input type="submit" value="Subscribe for updates" class="btn btn--primary">
</form>

<p><small>Privacy policy: we use your email only to send updates about the ToM4AI book and related announcements. We do not sell or share your email with third parties.</small></p>

<script>
  (function () {
    var params = new URLSearchParams(window.location.search);
    if (params.get("subscribed") === "1") {
      var success = document.getElementById("book-subscribe-success");
      if (success) {
        success.style.display = "block";
      }
    }
  })();
</script>
{% else %}
To enable signup collection:

1. Create a free form endpoint in Formspree.
2. Set `book_news.form_action` in `_config.yml`.
3. Rebuild the site.

After this is set, visitors will be able to subscribe directly on this page.
{% endif %}
