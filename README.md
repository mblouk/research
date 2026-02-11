# Research webpage

This resarch web page is based on a clean, single column, monospace [resume template](https://jekyll-themes.com/ankitsultana/researcher) built for jekyll. Please check the [demo](https://ankitsultana.com/researcher/) and the corresponding [Github repo](https://github.com/ankitsultana/researcher) for more details.


### Customization

* You can edit the `.md` files as you see fit. You can also add some other markdown file, say `foo.md` in the root directory of the repository. It will then be accessible like so `{{ url of your website }}/foo`.

* To edit the `links` mentioned on the navigation bar, you can edit `_config.yml`. For example:

```
nav:
 - name: "About"
   link: "/research/"
 - name: "Projects"
   link: "projects"
 - name: "Resume"
   link: "resume"
 - name: "Contact"
   link: "contact"
```

* You can change the accent (color of hyperlinks) by editing the `accent` variable in `_sass/vars.scss`

* To add a profile picture, make sure to give the image tag the class `profile-picture`. In other words,do it like so:

```html
<img class="profile-picture" src="m.jpg">
```

* You can remove/customize the footer as you like by setting the
appropriate variables in `_config.yml`

### License

[GNU GPL v3](https://github.com/bk2dcradle/researcher/blob/gh-pages/LICENSE)
