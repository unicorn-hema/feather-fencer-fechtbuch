# Feather Fencer Fechtbuch

Liechtenauer's teachings in a modern HEMA context.

A public personal HEMA wiki built with Markdown, MkDocs Material, and GitHub Pages.

Intended site: https://unicorn-hema.github.io/feather-fencer-fechtbuch/

## Local preview

Use Python 3.12 in a virtual environment:

```sh
python -m venv .venv
# Windows PowerShell: .venv/Scripts/Activate.ps1
# macOS/Linux: source .venv/bin/activate
python -m pip install -r requirements.txt
python -m mkdocs serve
```

Validate with `python -m mkdocs build --strict`.

## Editing

Edit Markdown under `docs/`. Add new pages to `nav` in `mkdocs.yml`.
Final articles must be in English; clearly marked WiP notes may be in Czech.
All repository contents and history are public.

## Deployment

1. Create public repository `unicorn-hema/feather-fencer-fechtbuch`, default branch `main`.
2. In Settings → Pages → Build and deployment, select GitHub Actions.
3. Push these files to main. The Build and deploy wiki workflow validates and deploys the site.
4. Confirm the workflow succeeds and open the site address above.

Pull requests run the strict build without deploying. No personal access token
is needed in repository secrets. The workflow uses GitHub's temporary token.

Workflow reference: https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages
