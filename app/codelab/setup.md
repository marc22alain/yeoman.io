---
layout: default
markdown: 1
social_text: "Let's Scaffold A Web App With @Yeoman!"
social_url: http://yeoman.io/codelab.html
sidebar: sidebars/codelab.html
---

# Step 1: Set up your dev environment

<p class="mast-holder">
  <img src="/assets/img/yeoman-004.png">
</p>

Most of your interactions with Yeoman will be through the command line. Run commands in the Terminal app if you’re on Mac, your shell in Linux, or `cmd.exe` if you are on Windows.

## Install prerequisites

Before installing Yeoman, you will need the following:

* Node.js v0.10.x+
* npm (which comes bundled with Node) v1.4.3+
* git

You can check if you have Node and npm installed by typing:

```sh
$ node --version && npm --version
```

If you need to upgrade or install Node, the easiest way is to use an installer for your platform. Download the *.msi* for Windows or *.pkg* for Mac from the [NodeJS website](http://nodejs.org/download/).

You can check if you have Git installed by typing:

```sh
$ git --version
```
If you don't have Git, grab the installers from the [git website](http://git-scm.com/).

## Install the Yeoman toolset

Once you’ve got Node installed, install the Yeoman toolset:

```sh
$ npm install --global yo bower grunt-cli
```

<div class="note important">

  <h2>Errors?</h2>

  <p>If you see permission or access errors, such as permission (`EPERM`) or access errors (`EACCESS`), do not use <code>sudo</code> as a work-around. <br>
  Consult [this page](https://github.com/sindresorhus/guides/blob/master/npm-global-without-sudo-linux.md) for a more robust solution to the permissions errors.</p>


</div>

## Confirm installation

It is a good idea to check that everything is installed as expected by running commonly used Yeoman commands like `yo`, `bower`, and `grunt` with the `--version` flag as follows:

```sh
$ yo --version && bower --version && grunt --version
```

Running the above should output three separate version numbers:

* Yeoman
* Bower
* Grunt CLI (the command-line interface for Grunt)

<div class="note important">

  <h2>Versions of the CLI tools that this codelab works with</h2>

  <p>Technology changes quickly! This tutorial has been tested with <strong>Yeoman 1.3.2</strong>, <strong>Bower 1.3.12</strong>, and <strong>grunt-cli v0.1.13</strong>. If you are running into issues with a newer version, we would like to hear about it. Please open up an issue on our <a href="https://github.com/yeoman/yeoman.io/issues">tracker</a>.</p>

</div>

<p class="codelab-paging">
  <a href="../codelab.html#toc">&laquo; Return to overview</a>
  or
  <a href="install-generators.html">Go to the next step &raquo;</a>
</p>
