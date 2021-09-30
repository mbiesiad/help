# Welcome to Zooniverse's help docs

The documentation is built by MkDocs. For full documentation visit [mkdocs.org](https://mkdocs.org).

## Editing

It's perfectly acceptable to just edit Markdown files on GitHub and submitting
pull requests directly from there. If you feel unsure if your syntax is
correct, it's pretty easy to run the site locally though, see below.

## Running locally

With Docker, it's a matter of simply `docker-compose up`.

Without Docker, you'll have to install the Python dependencies. Run `pip
install -r requirements.txt` and then start the local server with `mkdocs
serve`.

In both cases afterwards the site will be served from [localhost:8000](htto://localhost:8000).

## Deploying

Jenkins deploys changes automatically when merging to master.
