# README presentation and language selection

The root `README.md` is English. Explicit links select Chinese (`README.zh-CN.md`),
Japanese (`README.ja.md`) and Korean (`README.ko.md`). `README.en.md` keeps the
same English content so existing links continue to work.

Each version starts with a one-line prompt. It points to the main branch's
`SKILL.md` and asks the Agent to install Xbrain and organize the user's
authorized design references. GitHub provides the normal code-block copy control.

The Agent marks are static images with accessible alt text. Each mark uses a
static `picture` element to select its light or dark variant. There are no Agent
launch links, custom copy controls or redirect pages. The marks do not claim
that an Agent was tested end to end.

[GitHub's README documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
describes automatic README discovery by location: `.github`, root, then `docs`.
It does not document browser-language-based selection between translated README
files. We use the English root README and explicit language links accordingly.

[GitHub's markup pipeline](https://github.com/github/markup) removes scripts,
inline styles and other unsupported HTML. A README cannot run custom JavaScript
to select a translation or launch an app. This presentation needs neither.
