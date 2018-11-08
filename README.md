# Utterson

Utterson is a port of Hyde (the Jekyll theme) for Pelican.

## What's in a name?

This theme was named Utterson to follow the Jekyll-Hyde convention. Gabriel John Utterson is the main protagonist and a loyal friend of Jekyll in the [Strange Case of Dr Jekyll and Mr Hyde](https://en.wikipedia.org/wiki/Strange_Case_of_Dr_Jekyll_and_Mr_Hyde).

## Live preview

You can see how this theme looks like at [https://www.vinayakmehta.com](https://www.vinayakmehta.com).

## Screenshot

![screenshot](/screenshot.png)

## Usage

To use Utterson, clone this repo and add the absolute/relative path to the cloned folder in the `THEME` variable of your `pelicanconf.py`.

<pre>
THEME = '/path/to/utterson'
</pre>

Utterson supports all Hyde features in addition to its own.

You can define the following variables in your `pelicanconf.py` to use the corresponding features.

<table><table>
  <tr>
    <th>Variable</th>
    <th>Feature</th>
  </tr>
  <tr>
    <td><kbd>TITLE</kbd></td>
    <td>Adds sidebar title.</td>
  </tr>
  <tr>
    <td><kbd>TAGLINE</kbd></td>
    <td>Adds website title.</td>
  </tr>
  <tr>
    <td><kbd>DESCRIPTION</kbd></td>
    <td>Adds sidebar description.</td>
  </tr>
  <tr>
    <td><kbd>MENUITEMS</kbd></td>
    <td>Adds sidebar menu items. For example:
        <pre>MENUITEMS = [
    ('About' , '/about' ),
    ('Archives' , '/archives.html')]</pre>
    </td>
  </tr>
  <tr>
    <td><kbd>SOCIAL</kbd></td>
    <td>Adds sidebar social links using <a href="https://fontawesome.com/" target="_blank">Font Awesome</a> (follows tuple order). The brand name is appended to Font Awesome's <kbd>fa-</kbd>. For example: <kbd>github</kbd> will become <kbd>fa-github</kbd>.
        <pre>SOCIAL = (
    ('github' , '&lt;github_url&gt;'),
    ('twitter' , '&lt;twitter_url&gt;'),)</pre>
    </td>
  </tr>
  <tr>
    <td><kbd>GITHUB_URL</kbd></td>
    <td>Adds GitHub Corner to website.</td>
  </tr>
  <tr>
    <td><kbd>TWITTER_USERNAME</kbd></td>
    <td>Adds a Tweet button on an article's page.</td>
  </tr>
  <tr>
    <td><kbd>DISQUS_SITENAME</kbd></td>
    <td>Adds Disqus comments on an article's page.</td>
  </tr>
</table>

## Supported Plugins

- [GitHub Corners](https://github.com/tholman/github-corners)
- [Related posts](https://github.com/getpelican/pelican-plugins/tree/master/related_posts)
- [Minute read](https://github.com/getpelican/pelican-plugins/tree/master/post_stats) (in 0.2.0)
- [Representative image](https://github.com/getpelican/pelican-plugins/tree/master/representative_image) (in 0.2.0)

## Contributing

Please open an issue to discuss the bug/feature before submitting a PR.

[Be cordial or be on your way.](https://www.kennethreitz.org/essays/be-cordial-or-be-on-your-way) –Kenneth Reitz

## Versioning

Utterson uses [Semantic Versioning](https://semver.org/). For the available versions, see the tags on this repository.

## License

This project is licensed under the MIT License, see the [LICENSE](https://github.com/vinayak-mehta/utterson/blob/master/LICENSE) file for details.
