hexo-tag-plugin-img-center
==========================

Wrote a Hexo tag plugin to center image with subtitles. Lots of code came from Hexo's img tag plugin.

Input/Output examples:
  ```
  {% img_center %}
  <p align="center"><img></p>
  ```
  ```
  {% img_center /img/posts/blogPostImage.png %}
  <p align="center"><img src="/img/posts/blogPostImage.png"></p>
  ```
  ```
  {% img_center class1 /img/posts/blogPostImage.png %}
  <p class="class1" align="center"><img src="/img/posts/blogPostImage.png"></p>
  ```
  ```
  {% img_center class1 /img/posts/blogPostImage.png "img alt text" %}
  <p class="class1" align="center"><img src="/img/posts/blogPostImage.png" alt="img alt text"></p>
  ```
  ```
  {% img_center class1 /img/posts/blogPostImage.png "img alt text" "img subtitle" %}
  <p class="class1" align="center"><img src="/img/posts/blogPostImage.png" alt="img alt text"><br><small><em>[img subtitle]</em></small></p>
  ```
  ```
  {% img_center class1 /img/posts/blogPostImage.png 200 "img alt text" "img subtitle" %}
  <p class="class1" align="center"><img src="/img/posts/blogPostImage.png" width="200" alt="img alt text"><br><small><em>[img subtitle]</em></small></p>
  ```
  ```
  {% img_center class1 /img/posts/blogPostImage.png 200 300 "img alt text" "img subtitle" %}
  <p class="class1" align="center"><img src="/img/posts/blogPostImage.png" width="200" height="300" alt="img alt text"><br><small><em>[img subtitle]</em></small></p>
  ```
  ```
  {% img_center class1 /img/posts/blogPostImage.png 200 300 box-shadow "img alt text" "img subtitle" %}
  <p class="class1" align="center"><img style="box-shadow: 10px 5px 5px gray;" src="/img/posts/blogPostImage.png" width="200" height="300" alt="img alt text"><br><small><em>[img subtitle]</em></small></p>
  ```
