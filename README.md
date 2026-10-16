# Guardrails

Check what an AI model says before your users see it, and get told when quality drops.

> **Status: in development.** I'm building this in public. Follow along here or on the project page:
> **https://jacksonkojoosei.com/projects/guardrails**

## What it does

Send a prompt and the model's answer, get back pass or fail against your rules, your JSON schema and your test cases. Run the same suite after every model or prompt change and see whether things got better or worse. It shares its evaluation engine with DocuRead.

## Why

Teams ship AI features with no way to tell when a new model or prompt makes the answers worse until users complain.

## Planned features

- [ ] Schema and rule checks on model output
- [ ] Regression suites with scores over time
- [ ] Alerts when a change lowers accuracy
- [ ] Latency and cost per run

## Stack

TypeScript, Node.js, PostgreSQL, Claude API

## Author

Built by **[Jackson Kojo Osei](https://jacksonkojoosei.com)**, CTO in Accra, Ghana.
[LinkedIn](https://www.linkedin.com/in/jackson-kojo-osei-740846189) · [All projects](https://jacksonkojoosei.com/projects)

## License

MIT
