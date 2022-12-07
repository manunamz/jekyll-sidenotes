# Jekyll::SideNotes

`jekyll-sidenotes` is similar to markdown footnotes, but adds notes that render to either the left or right of the main content. The style is inspired by [tufte-css](https://edwardtufte.github.io/tufte-css/).

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jekyll-sidenotes'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install jekyll-sidenotes

## Syntax

```markdown
This is what a left-sidenote[<left] and a right-sidenote[>right] look like.

[<left]: the syntax looks similar to...
[>right]: ...regular markdown footnotes.
```

On medium to small sized screens, you can click on sidenote superscripts to show or hide their content.

Note:

- Sidenotes increment together, but separately from footnotes2. So, for example, it’s possible for there to be a ‘1’ for both a standard markdown footnote and a sidenote.
- Sidenotes require an “\n” after each definition to parse properly. A warning will display if there are missing newlines (regardless of sidenotes).

## Influences

For clean’n’simple sidenote css implementation:
[tufte css](https://github.com/edwardtufte/tufte-css)

How to implement tufte css in jekyll.
[simply jekyll](https://github.com/raghudotcc/simply-jekyll)

For sidenote implementation comparisons.
[gwern.net](https://github.com/gwern/gwern.net)
