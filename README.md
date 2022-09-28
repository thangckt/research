

A Github Pages template for academic websites. 

Original from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose

Then it was forked by [Stuart Geiger](https://github.com/staeiou) and released with the name [academicpage jekyll](https://github.com/academicpages/academicpages.github.io)

See more info at [https://academicpages.github.io/](https://academicpages.github.io/)



## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.


Some others forks:
- [MichaelRamamonjisoa](https://github.com/MichaelRamamonjisoa/michaelramamonjisoa.github.io)
    what is difference in this repo:
    ```
    ## in file: _includes/head/custom.html  and add 2 files `bootstrap.min.css`, `bootstrap.css` into assets/css/
    <link rel="stylesheet" href="{{ base_path }}/assets/css/bootstrap.css"/>  
    <!-- <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>  -->
    ```

Change font size nav-tabs, nav-side,... in file `bootstraps.css`
```
.nav-tabs > li.active > a {
  color: #3c5a78;
  font-size: 16px;
}
.nav-tabs > li > a {
  color: #575757;
}


.navbar-brand
{
  font-size: 100px;
}

```

But this may not work. Solution: update `bootstrap.css`. just edit file: `_includes/head/custom.html`, do not need download 2 files .css and .js
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/css/bootstrap.min.css"/>  
<script src="https://code.jquery.com/jquery-3.6.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/js/bootstrap.min.js"></script>
```
But the dynamic button may only work with `bootstrap 3`