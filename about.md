---
layout: page
description:
permalink: /about/
---

<section class="previews">
  <div>

      <figure class="absolute-bg preview__img" style="background-image: url('/images/kpb2.jpg');"></figure>

  </div>

  <div>
    <header>
    </header>

    <div class="tab">
      <ul itemscope itemtype="http://schema.org/Blog">

          <li class="preview" itemprop="blogPost" itemscope itemtype="http://schema.org/BlogPosting">
            <div class="preview__link">
              <h2 class="preview__header" itemprop="name">Test</h2>
              <p class="preview__excerpt" itemprop="description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quo ducimus sit voluptatibus! Odio voluptas unde et doloribus, delectus ratione tempore. Alias quaerat nihil similique accusantium!</p>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Modi, aut culpa cum! Inventore at dolores tenetur quidem dolorem. Perferendis sequi exercitationem in cumque ex. Repellendus dolorem totam sed voluptas, aperiam, officia odio animi unde necessitatibus veniam doloribus sunt commodi sit.</p>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cumque quasi autem accusamus, laudantium placeat, nostrum soluta voluptatem, enim omnis nemo dolorum eveniet dignissimos? Dolorum ducimus nisi nulla exercitationem facere corporis facilis, sit ea, rem nobis!</p>
            </div>
          </li>
      </ul>

      {% if paginator.total_pages > 1 %}
        <div class="pagination">
          {% if paginator.previous_page %}
            <a href="{{ paginator.previous_page_path | prepend: site.baseurl }}">Previous</a>
          {% endif %}

          {% if paginator.next_page %}
            <a href="{{ paginator.next_page_path | prepend: site.baseurl }}">Next</a>
          {% endif %}
        </div>
      {% endif %}

      {% include archive-link.html %}
    </div>


  </div>

</section>
