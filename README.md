# devops-ci-app

Учебное Flask-приложение для практической работы 10.

CI: Pylint → pytest → Docker build → smoke-test → GHCR.
Публикация образа выполняется только из `main`; PR проходят проверки без push.

- health endpoint: `/health`;
- образ: `ghcr.io/manfred246/devops-ci-app`;
- workflow: `.github/workflows/ci.yml`.
