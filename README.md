
When using the core files, the demo images, posts, and pages are all included with the download. After following the instructions below, you can then go and change the content of the pages and posts.

1. [Download](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/archive/master.zip) or Clone the repository.
2. Update the following configuration settings in your `_config.yml` file:

    * `baseurl`
    * `url`
    * `title`
    * `email` (after setting this setting to a working email address, fill out the form on the contact page and send it - then check your email and verify the address and the form will send you messages when used)
    * `description`
    * `author`
    * `twitter_username` (Optional)
    * `facebook_username` (Optional)
    * `github_username` (Optional)
    * `linkedin_username` (Optional)
    * `instagram_username` (Optional)

3. Build your site: `bundle exec jekyll serve`

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/issues) here on GitHub!

## About

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

* <https://startbootstrap.com>
* <https://twitter.com/SBootstrap>

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**.

* <http://davidmiller.io>
* <https://twitter.com/davidmillerhere>
* <https://github.com/davidtmiller>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2021 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/blob/master/LICENSE) license.

---

For anyone interested, to adjust the contact form to work with Formspree free tier [here](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/issues/167#issuecomment-846540715).  
- Copy Ciraben's [contact.html](https://github.com/ciraben/startbootstrap-clean-blog-jekyll/blob/contact-fix/contact.html)  
- Register a Formspree account
- Verify my email with Formspree
- Make a new form in Formspree
- Copy the URL of the new form
- In the contact form's HTML tag, replace the URL in action="https://formspree.io/{{ site.email }} with the copied URL
- Add name="message" to the textarea tag attribute of the message field.
