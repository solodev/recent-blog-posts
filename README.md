# recent-blog-posts
Displaying recent posts helps your visitors notice the content you publish and Bootstrap's box and column system, you can build an attractive recent posts section easily.

## Tutorial
For detailed instruction's, view Solodev's [Displaying Recent Posts on Your Website](https://www.solodev.com/blog/web-design/displaying-recent-posts-on-your-website.stml?preview=1190)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/e02jp31g/).

## HTML
The tutorial contains the following basic HTML markup.

```
  <section class="news pt-0">
        <div class="container mt-md-5">
            <h2 class="mx-4 my-0 text-center">Recent News</h2>
            <ul class="row d-lg-flex list-unstyled image-block justify-content-center px-lg-0 mx-lg-0">
              <li class="col-lg-4 col-md-5 image-block full-width p-3">
                <div class="image-block-inner">
                  <a class="mh-100" href="#">
                  <img src="images/news-1.jpg" alt="LunarXP Wins Space Innovator of the Year Award" class="img-responsive w-100"></a>
                  <span class="hp-posts-cat">Awards</span>
                  <h4 class="mt-3"><a href="#">LunarXP Wins Space Innovator of the Year Award</a></h4>
                <!--  <p></p> -->
                  <a href="#" class="read-more">Read more &gt;</a>
                </div><!-- .image-block-inner -->
              </li>
              <li class="col-lg-4 col-md-5 image-block full-width p-3">
                <div class="image-block-inner">
                  <a class="mh-100" href="#">
                  <img src="images/news-2.jpg" alt="New Spending Bill Expands Funding for Space Exploration" class="img-responsive w-100"></a>
                  <span class="hp-posts-cat">Mentions</span>
                  <h4 class="mt-3"><a href="#">New Spending Bill Expands Funding for Space Exploration</a></h4>
          <!--  <p></p> -->                
          <a href="#" class="read-more">Read more &gt;</a>
                </div><!-- .image-block-inner -->
              </li>
              <li class="col-lg-4 col-md-5 image-block full-width p-3">
                <div class="image-block-inner">
                  <a class="mh-100" href="#">
                  <img src="images/news-3.jpg" alt="LunarXP Sets Target for First Mars Landing in 2030" class="img-responsive w-100"></a>
                  <span class="hp-posts-cat">Missions</span>
                  <h4 class="mt-3"><a href="#">LunarXP Sets Target for First Mars Landing in 2030</a></h4>
                <!--  <p></p> -->
                  <a href="#" class="read-more">Read more &gt;</a>
                </div><!-- .image-block-inner -->
              </li>
            </ul>
          </div>
      </section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
<!-- Custom Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@600&display=swap" rel="stylesheet">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>  
```