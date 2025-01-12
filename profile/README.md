# [Schemathesis]([https://schemathesis.io](https://github.com/schemathesis/schemathesis)): Effective API Testing, simplified

## 📋 Overview

Schemathesis is an API testing tool that automatically finds crashes and validates spec compliance.

- **🎯 Catch Bugs & Ensure Compliance**: Detect hidden crashes, edge cases, and spec violations.

- **⚡ Fast & Automated Testing**: Generate diverse test cases from your API schema to save time.

- **🧩 Seamless Integration**: Compatible with OpenAPI, GraphQL, and CI/CD workflows.

- **🔧 Customizable**: Adapt testing with Python extensions and rich configurations.

- **🐞 Debugging Made Easy**: Detailed reports and reproducible cURL commands.

- **🔬 Research-Backed**: Recognized in academic studies as a state-of-the-art API testing tool.

### Quick Start

```bash
docker run schemathesis/schemathesis:stable
   run --checks all https://example.schemathesis.io/openapi.json
```

### 🚀 [GitHub Action](https://github.com/schemathesis/action)

Integrate API tests directly into your CI/CD pipeline with minimal YAML config.

```yaml
- uses: schemathesis/action@v1
  with:
    schema: 'https://example.schemathesis.io/openapi.json'
```
