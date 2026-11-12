# Awesome QREtools

QREtools is a tool to write survey questions and instruments, and to export them as
DDI-Lifecycle 4.0. This list gives the public parts of the QREtools ecosystem.

## The tool

- [qretools.com](https://qretools.com/) - The QREtools editor runs in the browser. It saves questions
  and instruments to a workspace on GitHub.
- [qretools on npm](https://www.npmjs.com/package/qretools) - This package is the command-line
  tool. It checks a workspace, builds its DDI, and writes an instrument as a QSF file that
  [Qualtrics](https://www.qualtrics.com/support/survey-platform/survey-module/survey-tools/import-and-export-surveys/)
  imports.
- [JHUCities/qretools](https://github.com/JHUCities/qretools) - This repository holds the source
  code of QREtools, under the MIT License.

## Start here

- [qretools-template](https://github.com/JHUCities/qretools-template) - This template starts a new
  workspace. Its README gives the steps to set up the workspace and to release it.
- [qretools-tutorial](https://github.com/JHUCities/qretools-tutorial) - This template holds short
  lessons. Each lesson is a question or an instrument with a gap that you fill in.

## Example workspaces

- [qretools-gss](https://github.com/JHUCities/qretools-gss) - This workspace holds the
  demographic questions and the work questions of the GSS Replicating Core, and an
  instrument. GitHub Pages publishes its [DDI](https://jhucities.github.io/qretools-gss/ddi.json).
- [qretools-big-5](https://github.com/JHUCities/qretools-big-5) - This workspace holds the 50
  questions of the IPIP Big-Five Factor Markers, and an instrument that calculates the five scores.

## Standards

- [DDI-Lifecycle 4.0](https://ddialliance.org/ddi-lifecycle) - QREtools exports questions and
  instruments in this standard.
- [DDI agency registry](https://registry.ddialliance.org/) - This registry records the DDI
  agency codes. Each workspace names one of these codes in its settings.
- [VTL](https://sdmx.org/about-sdmx/about-vtl/) - The conditions in an instrument use
  this expression language.

## Add an item

Read [CONTRIBUTING.md](CONTRIBUTING.md) before you add an item.

## License

The contributors give this list to the public domain under CC0 1.0. See
[LICENSE](LICENSE).
