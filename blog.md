---
layout: page
title: Blog
permalink: /blog/
id: blog
---

<div id="posts">
  <div class="container">
    <div class="row">
      <div class="col-md-9">

        {% for post in site.posts %}
        <div class="post">
          <a href="{{ post.url }}" class="pic">
            <img src="/images/{{ post.image }}" class="img-responsive" alt="blogpost" />
          </a>

          <div class="title">
            <a href="{{ post.url }}">{{ post.title }}</a>
          </div>
          <div class="author">
            <img src="/images/testimonials/{{ post.avatar }}" class="avatar" alt="author" />
            {{ post.author }}, {{ post.date | date: "%b %-d, %Y" }}
          </div>
          <p class="intro">
            {{ post.excerpt }}
          </p>
          <a href="{{ post.url }}" class="continue-reading">Continue reading this post</a>
        </div>
        {% endfor %}

        <div class="pages">
          <ul class="pagination">
              <li><a href="#">&laquo;</a></li>
              <li class="active"><a href="#">1</a></li>
              <li><a href="#">2</a></li>
              <li><a href="#">3</a></li>
              <li><a href="#">4</a></li>
              <li><a href="#">&raquo;</a></li>
          </ul>
        </div>
      </div>
      <div class="col-md-3 sidebar">
        <div class="search">
          <form>
            <span class="icomoon-search"></span>
            <input type="text" name="q" placeholder="Search on blog..." />
          </form>
        </div>
        <div class="updates">
          <strong>
            Free blog updates
            <i class="fa fa-rss"></i>
          </strong>
          <p>
            Never miss an update. 
            Sign up  to receieve an email whenever we post something in the blog.
          </p>
        </div>
        <div class="follow-tw">
          <img src="/images/twitterfollow.png" alt="follow-tw" />
        </div>
        <div class="best-hits">
          <strong>Check out our best hits:</strong>
          <a href="#">How to start a business</a>
          <a href="#">How to sell online</a>
          <a href="#">Climate change when needed</a>
          <a href="#">Web development upstart</a>
          <a href="#">Learn Rails in 30 days</a>
        </div>
      </div>
    </div>
  </div>
</div>