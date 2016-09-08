# <sup>Hipst</sup>e<sup>r</sup>clipse.org

*You either die an innovator, or live long enough to see yourself become the legacy.*

<sup>Hipst</sup>e<sup>r</sup>clipse is:

1. A listing of eclipse projects which are easy <sup>for hipsters</sup> to use and contribute to.
2. A <sup>hipster-friendly</sup> forum for discussing Eclipse - aimed at users and developers.

Eclipse.org has a lot of promises it needs to keep (bugzilla, gerrit, mailing lists), which makes it hard to chase the newest shiniest thing.  Whether those promises are an asset or a liability depends on whether the shininess holds up.

<sup>Hipst</sup>e<sup>r</sup>clipse is a place to pursue the new and shiny.

## Discussion board

The forums at eclipse.org have gotten rusty.  Head to [discuss.hipsterclipse.org](discuss.hipsterclipse.org) for a fresh start.

TODO: buy domain, setup discourse

## Project listing

The following is a list of eclipse-based projects which are easy *for hipsters* to use and contribute to. This means

1. The project's bug tracker must support UI discussion (images and video).
2. The project must accept plain commits (GitHub pull requests :thumbsup:, Gerrit `Change-Id` :thumbsdown:).
3. Project documentation (for users and developers) must be *within* the code repository (GitHub pages :thumbsup:, MediaWiki :thumbsdown:).

Hosting on [GitHub](https://github.com/) and [GitLab](https://about.gitlab.com/) are both excellent choices.  To add a project to this list, just submit a PR.

### Eclipse Plugins

**[Markdown Editor Plugin](https://github.com/winterstein/Eclipse-Markdown-Editor-Plugin)** - Syntax highlighting for markdown.

**[GitHub Flavored Markdown Viewer](https://github.com/satyagraha/gfm_viewer)** - View markdown as it will appear on GitHub.

### Build tools

**[Goomph](https://github.com/diffplug/goomph)** - A gradle plugin which can
- provision an eclipse IDE as part of the build process
- grab dependencies from p2 and maven
- generate OSGi manifests using bnd

**[Spotless](https://github.com/diffplug/spotless)** - A gradle plugin which uses the eclipse code formatter to check and enforce code style.

**[OsgiX](https://github.com/diffplug/osgiX)** - OSGi extension bundles for fixing `Unresolved requirement: Import-Package: sun.misc`

## Comparison so far

The purpose of hipsterclipse.org is to experiment and strengthen eclipse.org.  The following is a comparison of features of the eclipse.org ecosystem to other more hipster-ish ecosystems, to see how they compare.

[This is a forum thread](https://discuss.atom.io/t/proposal-real-es6-js-with-coffeescript-syntax/21396) where the Atom developers are discussing coffeescript syntax.  Although the discussion is about syntax, you'll see that it naturally segues into "how will we do highlighting?", and they toss around some visual mockups.  They can easily and naturally discuss visual concepts.

[Here's a VSCode bug report](https://github.com/Microsoft/vscode/issues/11689) on GitHub.  The UI is jumpy, so the user just uploaded a gif of the jumpy UI, right inline with their text.  How many sentences of monospaced prose in Bugzilla would be required to communicate what this gif communicates?
