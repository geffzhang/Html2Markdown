# HTML2Markdown

Converts HTML to [Markdown](http://daringfireball.net/projects/markdown/syntax)

[![NuGet version](https://badge.fury.io/nu/Html2Markdown.svg)](http://badge.fury.io/nu/Html2Markdown) [![Build Status](https://ci.appveyor.com/api/projects/status/cbi6sknslvu3rq6n?svg=true)](https://ci.appveyor.com/project/baynezy/html2markdown) 

## Support

This project will currently convert the following HTML tags:-

- a
- strong
- b
- em
- i
- br
- code
- h1
- h2
- h3
- h4
- h5
- h6
- blockquote
- img
- hr
- p
- pre
- ul
- ol

## Installing via NuGet

    Install-Package Html2Markdown

## Usage
    var converter = new Converter();
    var result = converter.Convert(html);

## Contributing

### Pull Requests

After forking the repository please create a pull request before creating the fix. This way we can talk about how the fix will be implemented. This will greatly increase your chance of your patch getting merged into the code base.
