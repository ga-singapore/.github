# Singapore website repositories

This is a **proposal**, not a list of live GitHub repositories. The website projects below would sit alongside cohort repositories if the Singapore organisation owners approve their scope and access model. Existing course and cohort guidance remains unchanged.

| Proposed repository | What it would contain |
| --- | --- |
| `web-hub` | Start here: website index, onboarding for maintainers, and release and recovery instructions. |
| `web-main` | The Singapore homepage, marketing pages, and the Swag front end. |
| `web-ai-futures` | AI Futures website and its published materials. |
| `web-chatbot-vibecode` | The chatbot and vibe coding course website. |
| `web-causecraft` | CauseCraft website and its published card resources. |
| `web-number-cards` | Number Cards artwork and tools, including the scanner and Swag service. |
| `web-decision-grade` | Decision Grade workshop website and interactive exercises. |
| `web-roleshock` | RoleShock website and role cards. |
| `web-portfolio-analytics` | The portfolio analytics demonstration website. |
| Restricted workshop websites | Separate repositories for authorised courseware and exercises, not for learner records or feedback. |

## How changes would work

Start with the hub and open only the repo for the website you need. Work on a branch, test the site, and open a pull request in that repository. After cutover, only GitHub-hosted Actions in `ga-singapore` should publish these sites. Repository access does not confer production access.

The initial version of each approved website would be copied from a reviewed snapshot of its current source, with an independent commit history. Secrets, deployment credentials and private user or workshop records do not belong in these repositories. Singapore organisation owners should approve which projects belong here and who can access them before any source is copied.
