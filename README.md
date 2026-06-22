# xpto-web

Angular 22 frontend

## Requirements

- Node.js 22+
- Angular CLI 22

## Running locally

```bash
npm install
ng serve
```

App available at `http://localhost:4200`

## Branch naming convention

| Prefix      | Purpose                                    |
|-------------|--------------------------------------------|
| `feat/`     | New features                               |
| `fix/`      | Bug fixes                                  |
| `chore/`    | Maintenance, dependencies, configuration   |
| `docs/`     | Documentation only                         |
| `hotfix/`   | Urgent fix applied directly to main via PR |

## Workflow

- `develop` → staging (auto-deploy)
- `main` → production (requires manual approval)
- All merges via Pull Request
