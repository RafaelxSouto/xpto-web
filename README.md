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

- All feature branches merge into `main` via Pull Request
- `main` deploys to both staging and production
