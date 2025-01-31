# Wasm4Learn documentation

## Overview

**Language**

[![Made with Markdown](https://img.shields.io/badge/Made%20with-Markdown-blue)](https://squidfunk.github.io/mkdocs-material/)

**Continuous Integration**

![Release workflow](https://github.com/IFB-ElixirFr/Wasm4Learn-doc/actions/workflows/release.yml/badge.svg)

**Questions**

[:speech_balloon: Ask a question](https://github.com/IFB-ElixirFr/Wasm4Learn-doc/issues/new)
[:book: Report a problem or an idea](https://github.com/IFB-ElixirFr/Wasm4Learn-doc/issues/new)

**Contribution**

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)

## Project layout

```bash
    mkdocs.yml         # The configuration file.
    docs/
        Deployement/   # deployement steps for each repository
            ...
        Components/    # Component usable in the (md) files
            ...
        index.md       # The documentation homepage.
        ...            # Other markdown pages, images and other files.
```

## For collaborators and developers

This part is for collaborators and developers.

### Modify content

When you are in the repository, add and/or modify your markdown tutorials in the docs directory. The arborescence of the website menu is to setup in the mkdocs.yml file.

### Mkdocs

To work locally with this project, you'll have to follow the steps below:

1. Fork, clone or download this project
2. Create and activate conda env

```bash
cd Wasm4Learn-doc
conda env create -f env_docs.yml
conda activate docs_was4learn
```

3. Preview your project

```bash
mkdocs serve
```

Note : *The site can be accessed under http://localhost:8000/*

4. Add content

Add/update markdown files in docs folder

5. Test

```bash
mkdocs build
```

7. Deploy

**Only if previous command is Ok !**

```bash
mkdocs gh-deploy --force
```

If you add an extension to (Material) MKdocs that requires the installation of a new package.
Don't forget to export the conda environment (env_docs.yml) using the command line below.

```bash
conda env export --no-builds env_docs.yml
```

> **Reminder :**
> Don't forget to commit and push your changed md files in the main branch 


Read more at:

- MkDocs [documentation](https://www.mkdocs.org/)
- Mkdocs Material [documentation](https://squidfunk.github.io/mkdocs-material/)

## Citation

If you use our guide, please cite us :

IFB-ElixirFr, Wasm4learn documentation, https://github.com/IFB-ElixirFr/Wasm4Learn-doc

A DOI with Zenodo is comming.

## Contributors

* [Thomas Denecker](https://github.com/thomasdenecker) <a itemprop="sameAs" content="https://orcid.org/0000-0003-1421-7641" href="https://orcid.org/0000-0003-1421-7641" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>
* [Imane Messak](https://gitlab.com/imanemessak) <a itemprop="sameAs" content="https://orcid.org/0000-0002-1654-6652" href="https://orcid.org/0000-0002-1654-6652" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

## Contributing
Please, see the [CONTRIBUTING](CONTRIBUTING.md) file.

## Contributor Code of Conduct
Please note that this project is released with a [Contributor Code of Conduct](https://www.contributor-covenant.org/). By participating in this project you agree to abide by its terms. See [CODE_OF_CONDUCT](code_of_conduct.md) file.

## License

Our guide is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/legalcode).

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

## Acknowledgement

- All contributors

## Ressources

### mkdocs

- Official documentation : https://www.mkdocs.org/
- Material (best extension !) : https://squidfunk.github.io/mkdocs-material/
- Multi language structure : https://github.com/squidfunk/mkdocs-material/discussions/2346

