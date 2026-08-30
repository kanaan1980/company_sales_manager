# Codex instructions

## Project
Company Sales Manager is an internal Django application for an electrical-appliance and mobile/technology sales company.

## Rules
- Read PLAN.md before making architectural changes.
- Use Django ORM and Decimal for money.
- Keep business logic testable and avoid putting complex rules in templates.
- Use Django Admin for administration.
- Keep desktop and mobile experiences on the same backend and data model.
- Use Django Templates and Tailwind CSS; do not introduce a separate SPA unless explicitly requested.
- Keep secrets in environment variables. Never commit API keys.
- Use SQLite initially.
- Use Resend only through configuration/environment variables; use terminal email backend locally.
- Add migrations and tests with model/business-rule changes.
- Prefer small, reviewable commits.
- Do not remove existing functionality without explicit instruction.
