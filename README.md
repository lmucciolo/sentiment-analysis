# Uncovering Informational Value in 8-K Disclosures Using NLP

By leveraging a state-of-the-art NLP model, we aim to determine whether nuanced language cues in 8-K disclosures contain incremental information for stock return prediction beyond what traditional financial factors capture.


## Repository Layout

* `data`: contains necessary data files and data download files
* `utils`: contains main modeling script
* `proposal`: contains all documents related to the project proposal
* `deliverables`: contains all documents related to project delivery (presentation and paper)
* `resources`: contains resources for using git and the command line interface

Note: In order to access the financial data (ff_daily_factors, ff_monthly_factors) you will need a [WRDS](https://wrds-www.wharton.upenn.edu/) account.

## Contributing

This project uses uv to manage dependencies.

### Setup

1. Install [uv](https://docs.astral.sh/uv/getting-started/installation/)
2. Run `uv sync` to sync your local `.venv` with the requirements in `pyprojects.toml`
3. Run `uv add <dependency>` to add any project dependency

Read more about uv [here](https://docs.astral.sh/uv/guides/projects/#uvlock).

### Workflow

1. Run `uv sync` to ensure you are working in the proper environment
2. If using command line, run `git pull` to pull in most recent repo changes
3. If any edits are made, run `git add <file name>` to stage/track changes
4. To commit changes, run `git commit -m "commit message here"`
5. To push commits to repo, run `git push origin`


## Development

This project was created by University of Chicago MBA and MSCAPP students as a class project for Machine Learning in Finance (BUSN35137), taught by Professor [Leland Bybee](https://lelandbybee.com/).

Team members:

    Daniel Buckman
    
    Santiago Etchepare
  
    Michael Logan
  
    Livia Mucciolo
