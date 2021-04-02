![Logo](docs/img/logo.png "Logo")

Accessibility Audit
---

> Command Line Interface for Automated Accessibility Auditing of Websites

Introduction
---

A CLI tool that tests websites for Accessibility Issues and generates reports that can be assigned to developers.

- [X] Support for Continuous Integration Testing
- [X] Save Reports in CSV, HTML, Jira, JSON, Markdown & XML Formats
- [X] Supports Page Automation using Actions
- [X] Supports Testing Websites behind HTTP Authentication
- [X] Reports provide Resource Links for Developers to Learn More about Accessibility

Developer Overview
---

### Commands

* [`a11y-audit`](docs/cmd-options.md) - Detailed Examples of `a11y-audit` Usage
* [`a11y-audit auth`](docs/cmd-auth.md) - Generate HTTP Authentication Tokens
* [`a11y-audit help`](docs/cmd-help.md) - Get Help when you need it

#### Additional Information

* [Automate with Actions](docs/actions.md) - Submit Forms, Click Links & Other Fun Things
* [Troubleshooting](docs/troubleshooting.md) - Some of the Known Issues & how to resolve them

Install
---

#### Requirements

- [X] [Node v10+](https://nodejs.org/en/download/)

#### `git clone`

```bash
cd ~
git clone https://github.com/bell-apps/accessibility-audit.git
cd accessibility-audit
npm install -g
a11y-audit help
```

Report Samples
---

I've worked extensively to make the most helpful reports possible. Whether you are running a test on a single ite, or need to batch multiple tests into a single reports, I wanted to make our reports as developer friendly as possible.

Since this is a CLI tool, the default output is in a terminal window.

_Built using [pa11y](https://github.com/pa11y/pa11y).
