# [Schemathesis]([https://schemathesis.io](https://github.com/schemathesis/schemathesis)): Effective API Testing, simplified

## 📋 Overview

Schemathesis automatically generates and runs API tests from your OpenAPI or GraphQL schema to find bugs and spec violations.

- 📑 **Schema-Based Testing** - Transform API documentation into a comprehensive test suite
- 🚀 **Zero Configuration** - Begin testing immediately with a valid OpenAPI or GraphQL schema
- ⚙️ **CI-Ready** - Integrate API testing into existing pipelines without complex configuration
- 🛡️ **Effective Coverage** - Find edge cases no manual testing could uncover
- 🔬 **Research-Backed**: [Recognized](https://dl.acm.org/doi/10.1145/3617175) in [academic research](https://ieeexplore.ieee.org/document/9793781) as a state-of-the-art API testing tool

### Quick Start

```console
$ uvx schemathesis run http://example.schemathesis.io/openapi.json
```

### 🚀 [GitHub Action](https://github.com/schemathesis/action)

Integrate API tests directly into your CI/CD pipeline with minimal YAML config.

```yaml
- uses: schemathesis/action@v1
  with:
    schema: 'https://example.schemathesis.io/openapi.json'
```
