# fbihtax example project

This projects demonstrates [fbihtax](https://github.com/esensar/fbihtax) usage in a repository, combined with [ledger-cli](https://www.ledger-cli.org/) and GitHub Actions.

Add new payments to `payments.journal` file. More information about the file format and the tool used can be found on [ledger-cli](https://www.ledger-cli.org/). On any changes to the file, workflow will be trigerred to generate new AMS form and new issue for tax payment. Besides this, workflow will be automatically run every day to update conversion rates database from USD to BAM conversion in case of foreign currency payments.

This repository can be used as a template to star tracking payments and taxes. All AMS forms are automatically commited to the repository for future reference and for easier yearly tax report generation.
