# How to add your card

1. Open an Issue “Card <username>” using the template.
2. Make a fork and a `card-<username>` branch from a fresh `main`.
3. File `cards/<username>.json`: fields `name`, `profile`, `project` — full URLs, with `https://`; `stack` — technologies separated by a comma and a space.
4. One commit with the message `feat: card <username>`; fixes — `fix: …`.
5. A Pull Request to `main` of the gallery, with `Closes #<Issue number>` in the description.

Edit only your own file: other people's cards and shared files go in a separate Issue.

## AI assistance

You may use an agent. In the PR description, say what the AI did and what you checked yourself; in the commit, add the line `Assisted-by: <agent> (<what it did>)`. Answer review comments yourself.
