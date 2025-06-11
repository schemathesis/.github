# [Schemathesis]([https://schemathesis.io](https://github.com/schemathesis/schemathesis)): Catch API bugs before your users do

## 📋 Overview

Schemathesis automatically generates thousands of test cases from your OpenAPI or GraphQL schema and finds edge cases that break your API.

## What problems does it solve?

- 💥 **500 errors** that crash your API on edge case inputs
- 📋 **Schema violations** where your API returns different data than documented  
- 🚪 **Validation bypasses** where invalid data gets accepted
- 🔗 **Integration failures** when responses don't match client expectations

### Quick Start

```console
$ uvx schemathesis run http://example.schemathesis.io/openapi.json
```

### 🚀 [GitHub Action](https://github.com/schemathesis/action)

Run Schemathesis tests in CI/CD pipelines:

```yaml
- uses: schemathesis/action@v1
  with:
    schema: 'https://example.schemathesis.io/openapi.json'
```
