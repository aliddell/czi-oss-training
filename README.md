# CZI Open Source Training Materials

This repository contains the training materials for the CZI Imaging Tech team focused on good open-source citizenship.

- [CZI Open Source Training Materials](#czi-open-source-training-materials)
  - [Format and structure 🔖](#format-and-structure-)
  - [Learning personas 🙋🏽‍♀️](#learning-personas-️)
  - [Course outline 🗺](#course-outline-)
  - [Contributing](#contributing)
    - [Pre-commit hooks 🧹](#pre-commit-hooks-)

## Format and structure 🔖

This repository contains several modules intended to drive knowledge and culture around open source at CZI.

* Each module covers specific topics and is intended to be self-contained.
* Each module is broken into chapters, which are prefixed by a number to reflect the order in which they should be read.
* Each chapter indicates the main personas at which the content is aimed (though this is not prescriptive,
  and all stakeholders involved in open source should be able to follow all the content in this repository).
* Files are written in Markdown format.

<!-- TODO: once we have made the relevant decisions we need to add notes on licensing, slides and the such -->

## Learning personas 🙋🏽‍♀️

<!-- TODO: @pavithraes will be adding these -->

## Course outline 🗺

* [01-Introduction to open-source](./01-intro-to-os/README.md): Provides a brief introduction to open-source, its ethos, and its benefits.
  
## Contributing

### Pre-commit hooks 🧹

This repository uses the `prettier` pre-commit hook to standardize our Markdown structure.
To install and run the pre-commit hooks, use these commands from the repository root:

```bash
# install the pre-commit hooks
pre-commit install

# run the pre-commit hooks
pre-commit run --all-files
```

Once installed, the hooks should run automatically on every commit.
