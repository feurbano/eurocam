# EuroCaM

This repository is used to process and validate camera trap datasets received for the EuroCaM COVID-19 study.

## Specifications

Specifications of the EuroCaM Template are defined in [specs](specs). These use the [whip](https://github.com/inbo/whip) syntax.

## Repo structure

The structure for each dataset in [datasets](datasets) is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/). Files and directories indicated with `GENERATED` should not be edited manually.

```
├── data
│   ├── raw                  : Source data (filled out Excel template)
│   └── processed            : Data as tab-delimited text files GENERATED
│
└── notebooks
    └── validation.ipynb     : Script to process and validate the data
```

## Contributors

[List of contributors](https://github.com/feurbano/eurocam/graphs/contributors)

## License

[MIT License](LICENSE) for the code and documentation in this repository. The included data is released under another license.
