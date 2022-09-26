

A Github Pages template for academic websites. 

Original from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose

Then it was forked by [Stuart Geiger](https://github.com/staeiou) and released with the name [academicpage jekyll](https://github.com/academicpages/academicpages.github.io)

See more info at [https://academicpages.github.io/](https://academicpages.github.io/)


Some others forks:
- [MichaelRamamonjisoa](https://github.com/MichaelRamamonjisoa/michaelramamonjisoa.github.io)



## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
