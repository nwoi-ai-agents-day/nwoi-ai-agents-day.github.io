# AI Agents in Practice: NWO-I edition

Website for the one-day NWO-I edition of the CWI course *AI Agents in
Practice*, on Monday 7 December 2026. The planned address is
<https://nwoi-ai-agents-day.github.io/nwoi-ai-agents-day/>, from the repo
`nwoi-ai-agents-day/nwoi-ai-agents-day`.

Built with [Jekyll](https://jekyllrb.com). Layouts and styles come from the
course site.

## Run locally

```sh
bundle install
bundle exec jekyll serve --port 4001
```

Then open <http://127.0.0.1:4001/nwoi-ai-agents-day/>.

## Editing content

| What | Where |
| --- | --- |
| Date, time, location, presenter, registration link | `_config.yml` → `event:` |
| Programme times and what each block covers | `_data/programme.yml` |
| Home page | `index.html` |
| Programme page | `programme.html` |
| Before you come | `setup.md` |
| Skills, resources | `skills.md`, `resources.md` |

The register button appears in the header, the home page and the footer once
`event.register_url` is set. Every internal link goes through `relative_url`.
