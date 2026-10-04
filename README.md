# GitHubinator*
*_With regards to [Dr. Heinz Doofenshmirtz](http://en.wikipedia.org/wiki/Dr._Heinz_Doofenshmirtz)_

This will allow you to select text in a Sublime Text file, and see the highlighted lines on GitHub's remote repo, if one exists.

![Screenshot](http://i.imgur.com/lcJ78.png)


## Installation

```
  1. Open the Command Palette (⇧⌘P) and run Package Control: Add Repository.
  2. Paste `https://github.com/chdsbd/GitHubinator`.
  3. Run `Package Control: Install Package` and pick GitHubinator. If the upstream copy is installed, remove it first.
```

## Configuration

The defaults should work for most setups, but if you have a different remote name, use GitHub Enterprise or default branch, you can configure remote, host, and default branch in the `Githubinator.sublime-settings` file:

    {
      "default_remote": "origin",
      "default_host": "github.com",
      "default_branch": "master"
    }

## Usage

Select some text.
Activate the context menu and select "GitHubinator" or by keypress (&#8984;\\ by default, configurable in .sublime-keymap file).
