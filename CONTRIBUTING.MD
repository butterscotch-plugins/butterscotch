# Contributing to butterscotch

Thank you from :yellow_heart: for trying to contribute. :sparkles:

#### Table Of Contents

[What should I know before I get started?](#what-should-i-know-before-i-get-started) 
  * [Code of Conduct](#code-of-conduct) 
  * [All Packages](#all-packages) 

[How Can I Contribute?](#how-can-i-contribute) 
  * [Reporting Bugs](#issues-bug) 
  * [Suggestion To Improve](#issues-improve) 
  * [Pull Requests](#pull-requests) 

[Styleguides](#styleguides) 
  * [Git Commit Messages](#git-commit-messages) 
  * [JavaScript Styleguide](#javascript-styleguide) 
  * [CoffeeScript Styleguide](#coffeescript-styleguide) 
  * [Specs Styleguide](#specs-styleguide) 
  * [Documentation Styleguide](#documentation-styleguide) 

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

## All Packages

butterscotch is a collection of individual plugins. All of those plugins makes butterscotch a functional unit.

Here's a list of those plugins in alphabetical order:

* [butterscotch.add-posts](https://github.com/butterscotch-plugins/butterscotch.add-posts) - Responsible for adding new posts to butterscotch bloggin platform
* [butterscotch.admin-context](https://github.com/butterscotch-plugins/butterscotch.admin-context) - Responsisble for adding variables which are sent to views of admin panel
* [butterscotch.admin-dashboard](https://github.com/butterscotch-plugins/butterscotch.admin-dashboard) - Renders the landing page of butterscotch admin panel
* [butterscotch.admin-permissions](https://github.com/butterscotch-plugins/butterscotch.admin-permissions) - Plugins to manage the various permissions which are allocated to an user
* [butterscotch.admin-theme](https://github.com/butterscotch-plugins/butterscotch.admin-theme) - Responsible for creating the methods that are called in admin panels views using `$`
* [butterscotch.admin-ui-user-manager](https://github.com/butterscotch-plugins/butterscotch.admin-ui-user-manager) - Responsible for adding and removing users
* [butterscotch.admin-user-schema](https://github.com/butterscotch-plugins/butterscotch.admin-user-schema) - Responsible for creating the extensible structure of adminUser schema which is used for various tasks like authentication etc.
* [butterscotch.authenticate-admin-ui](https://github.com/butterscotch-plugins/butterscotch.authenticate-admin-ui) - Responsible for managing all the authentication in butterscotch platform.
* [butterscotch.blog-info](https://github.com/butterscotch-plugins/butterscotch.blog-info) - Attaches details regarding blog to the variable views using `adminContext` plugin
* [butterscotch.post-schema](https://github.com/butterscotch-plugins/butterscotch.post-schema) - Responsible for creating the extensible structure of posts schema.
* [butterscotch.widget-maker](https://github.com/butterscotch-plugins/butterscotch.widget-maker) - Responsible for creating widget and creating widget areas.

## How Can I Contribute

 butterscotch uses [ZenHub](https://github.com/integrations/zenhub) to maintain the state of various issues. All the contributors are highly requested to install ZenHub into their browsers.

### Reporting Bugs

Bugs are tracked as GitHub issues. After you've determined which plugin your bug is related to, create an issue on that plugin's repository and provide the following information by filling in the template.

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started butterscotch( or friday-suite), e.g. which command exactly you used in the terminal, or how you started butterscotch otherwise. When listing steps, **don't just say what you did, but explain how you did it**.
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. You can use [this tool](http://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **If you're reporting that butterscotch crashed**, include a crash report with a stack trace from the operating system. On macOS, the crash report will be available in `log/error` directory. Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), or put it in a [gist](https://gist.github.com/) and provide link to that gist.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

### Suggestions To Improve

#### Before Submitting An Enhancement Suggestion

* **Check if there's already [a package](#all-packages) which provides that enhancement.**
* **Determine [which repository the enhancement should be suggested in](#all-packages).**
* **Perform a [cursory search](https://github.com/issues?q=+is%3Aissue+user%3Abutterscotch-plugins)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined [which repository](#all-packages) your enhancement suggestions is related to, create an issue on that repository. If your suggestion does not fall under any current package then create an issue in this repository to add a new package. Also, provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of Atom which the suggestion is related to. You can use [this tool](http://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **Explain why this enhancement would be useful** to most butterscotch users and isn't something that can or should be implemented as a [community package](#all-packages).

### Pull Requests

* Fill in [the required template](PULL_REQUEST_TEMPLATE.md)
* Include screenshots and animated GIFs in your pull request whenever possible.
* Follow the [JavaScript](#javascript-styleguide) styleguide.
* Testing Instruction Coming soon
* Document new code based on the
  [Documentation Styleguide](#documentation-styleguide)
* End files with a newline.
* [Avoid platform-dependent code](http://flight-manual.atom.io/hacking-atom/sections/cross-platform-compatibility/)

### Styleguides

#### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally
* When only changing documentation, include `[ci skip]` in the commit description

* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :penguin: `:penguin:` when fixing something on Linux
    * :apple: `:apple:` when fixing something on macOS
    * :checkered_flag: `:checkered_flag:` when fixing something on Windows
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies
    * :shirt: `:shirt:` when removing linter warnings
* Follow the guidelines listed [here](https://chris.beams.io/posts/git-commit/) 
    * Separate subject from body with a blank line
    * Limit the subject line to 50 characters
    * Capitalize the subject line
    * Do not end the subject line with a period
    * Use the imperative mood in the subject line
    * Wrap the body at 72 characters
    * Use the body to explain what and why vs. how
* Example

```
Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

Put references to solved issues at the bottom,
like this:

Resolves: #123
See also: #456, #789
```

#### Javascript Styleguide

* butterscotch and friday-suite and all the plugins use [Javascript Standard Style Guide](http://standardjs.com)

#### Documentation Styleguide

* Use [Markdown](https://daringfireball.net/projects/markdown).