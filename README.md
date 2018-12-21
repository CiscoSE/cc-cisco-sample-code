# Cisco Sample Code | Cookiecutter Project Template

*Language-agnostic Cookiecutter template for Cisco Sample Code projects.*

Every project needs a start.  This [Cookiecutter](https://github.com/audreyr/cookiecutter) project template makes it easy for you to start a *Cisco Sample Code* project using the [Cisco Sample Code License](./LICENSE) with minimal (but engaging!) project documentation.

## Motivation

Every time you start a new project:  You've got to go hunt down the license file. Create a README from scratch or go and find your last best version to remember everything you put in it.  GitHub wants you to have a have a Contributing guide, a Code of Conduct, etc.  ...moreover, where are you supposed to put all of these files again?

Wouldn't it be easier to just:

```bash
$ cookiecutter cc-cisco-sample-code
full_name [John Doe]:
email [jdoe@cisco.com]:
project_name [Cisco Sample Code Project]:
project_slug [cisco-sample-code-project]:
project_short_description [Cisco Sample Code project essential docs]:

$ tree -a cisco-sample-code-project/
cisco-sample-code-project/
├── .github
│   ├── ISSUE_TEMPLATE
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── PULL_REQUEST_TEMPLATE.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── HEADER
├── LICENSE
└── README.md

2 directories, 8 files
```

I thought so too.

## Using the Project Template

### The First Time

```bash
$ cookiecutter https://github.com/CiscoSE/cc-cisco-sample-code
```

...or using abbreviated syntax:

```bash
$ cookiecutter gh:CiscoSE/cc-cisco-sample-code
```

### Thereafter

```bash
$ cookiecutter cc-cisco-sample-code
```

## Installation

You don't have to know Python syntax or write Python code to create and use Cookiecutter templates, but you do need Python and the Cookiecutter tool installed on your workstation.

If you have a working Python development environment, installation is simple:

```bash
$ pip install cookiecutter
```

If you need a bit more help than that, see [Installation](https://cookiecutter.readthedocs.io/en/latest/installation.html) in the Cookiecutter docs.


## Credits

The following excellent resources were influencial in the creation of this project:

- [Cookiecutter](https://github.com/audreyr/cookiecutter) by Audrey Roy Greenfeld ([@audreyr](https://github.com/audreyr))
- [GitHub: About READMEs](https://help.github.com/articles/about-readmes/)
- [A Beginners Guide to writing a Kickass README](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- Kenneth Reitz ([@kennethreitz](https://github.com/kennethreitz))'s Projects - [Requests](https://github.com/requests/requests), [Responder](https://github.com/kennethreitz/responder), [Tablib](https://github.com/kennethreitz/tablib), etc.

## Who is this for?

This project template is for use by **Cisco Systems Engineers** who are creating example and demonstration code *(aka. Cisco Sample Code)* and sharing it with Cisco's customers and partners for use with Cisco products and services.  **The Cisco Sample Code License is for use in Cisco Repositories Only.**  It is not an Open Source license. The license should only be used by Cisco and/or its affiliates to post and share Cisco Sample Code.
