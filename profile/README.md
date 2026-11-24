# [Schemathesis](https://github.com/schemathesis/schemathesis): Catch API bugs before your users do

Schemathesis tests OpenAPI and GraphQL APIs by generating inputs from your schema, adapting to server responses, and chaining operations into realistic workflows.

```console
uvx schemathesis run https://example.schemathesis.io/openapi.json
```

## What problems does it solve?

- 💥 **500 errors** that crash your API on edge case inputs
- 📋 **Schema violations** where your API returns different data than documented
- 🚪 **Validation bypasses** where invalid data gets accepted
- 🔗 **Integration failures** when responses don't match client expectations
- 🔄 **Stateful bugs** where operations work individually but fail in realistic workflows

## Projects

- 🧪 **[Schemathesis](https://github.com/schemathesis/schemathesis)** - the CLI and pytest plugin
- 🚀 **[GitHub Action](https://github.com/schemathesis/action)** - run Schemathesis in CI
- 🎯 **[TraceCov](https://github.com/schemathesis/tracecov)** - which parts of your OpenAPI spec your tests never exercise
- 🔬 **[Live Benchmarks](https://workbench.schemathesis.io)** - hour-long runs against Apache Airflow, Open WebUI, Prefect and more

```yaml
- uses: schemathesis/action@v3
  with:
    schema: "https://your-api.com/openapi.json"
```

📚 [Documentation](https://schemathesis.readthedocs.io/en/stable/) | 💬 [Discord](https://discord.gg/R9ASRAmHnA)
