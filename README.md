How to start up locally

```
$ jekyll serve
```

If Gemfile has been changed
```

```

To install and run themes listed in Gemfile
```
$ bundle install
$ bundle exec jekyll serve
```

## Adding drafts

Include them in ```__drafts``` directory.



## Custom layouts
Located in ```__layouts``` directory

Add ```.html``` files here to overwrite current layout.

## Variables

Variables ```_config.yml``` can be accessed with ```{{}}``` and ``` site.<var_name>```. Front matter variables can be accessed by ```<layout_name>.<var_name>```Content can be added simply by ```{{content}}```.
