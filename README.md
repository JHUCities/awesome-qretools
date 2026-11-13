# Awesome QREtools

QREtools is a tool that writes survey questions and instruments, and exports them as
DDI-Lifecycle 4.0. This list gives the public parts of the QREtools ecosystem.

## The tool

- [qretools.com](https://qretools.com/) - The QREtools editor runs in the browser. It saves questions
  and instruments to a workspace on GitHub.
- [qretools on npm](https://www.npmjs.com/package/qretools) - This package is the command-line
  tool. It checks a workspace, builds its DDI, writes an instrument as a QSF file for
  [Qualtrics](https://www.qualtrics.com/support/survey-platform/survey-module/survey-tools/import-and-export-surveys/),
  and makes a dataset from survey answers.
- [JHUCities/qretools](https://github.com/JHUCities/qretools) - This repository holds the source
  code of QREtools, under the MIT License.
- [qretools-harness](https://github.com/JHUCities/qretools-harness) - This program asks a
  language model the questions of an instrument. The model answers as one or more
  respondents, and the harness makes a dataset with QREtools.

## Start here

- [qretools-template](https://github.com/JHUCities/qretools-template) - This template starts a new
  workspace. Its README gives the steps to set up the workspace and to release it.
- [qretools-tutorial](https://github.com/JHUCities/qretools-tutorial) - This template holds short
  lessons. Each lesson is a question or an instrument with a gap that you fill in.
- [qretools-skill](https://github.com/JHUCities/qretools-skill) - This agent skill tells an
  AI agent how to do survey research with QREtools: make datasets, check their provenance,
  and compare real answers with the answers of a language model.

## Example workspaces

- [qretools-gss](https://github.com/JHUCities/qretools-gss) - This workspace holds the
  demographic questions and the work questions of the GSS Replicating Core, and an
  instrument. GitHub Pages publishes its [DDI](https://jhucities.github.io/qretools-gss/ddi.json),
  and its `maps` folder connects the columns of GSS data and of Qualtrics exports to the DDI variables.
- [qretools-big-5](https://github.com/JHUCities/qretools-big-5) - This workspace holds the 50
  questions of the IPIP Big-Five Factor Markers, and an instrument that calculates the five scores.

## Standards

- [DDI-Lifecycle 4.0](https://ddialliance.org/ddi-lifecycle) - QREtools exports its metadata in
  this standard.
- [DDI agency registry](https://registry.ddialliance.org/) - This register gives out DDI agency
  codes. Each workspace publishes its DDI under one of these codes.
- [VTL](https://sdmx.org/about-sdmx/about-vtl/) - The conditions in an instrument use
  this expression language.

## Add an item

Read [CONTRIBUTING.md](CONTRIBUTING.md) before you add an item.

## License

The contributors give this list to the public domain under CC0 1.0. See
[LICENSE](LICENSE).
