# Personal Homepage Using Jekyll hosted using GitHub Pages
View it live [here](mathana96.github.i)

# Using Jekyll to generate a static site

A learning attempt with `Jekyll` using this [tutorial](https://opensource.com/article/17/4/getting-started-jekyll?sc_cid=70160000001273HAAQ)

# Issues Faced and Resolve
* It was a pain to get `rbevn` installed properly. Following the `rbevnv` [docs](https://github.com/rbenv/rbenv) did not exactly work as `echo $PATH` revealed that `git init` did not set up my shims path. `ruby -v` remained the system version despite `rbenv global 2.4.1`.  Using the this [tutorial](https://gorails.com/setup/osx/10.11-el-capitan), things are looking good.
* `cannot load such file -- bundler`. Solved by `brew install bundler` 
