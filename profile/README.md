# [Schemathesis.io](https://schemathesis.io): Effective API Testing, simplified

## 📋 Overview

Automate API testing with just an API spec. No manual tests, no complex setups. Reduce human error, save time, and improve API reliability.

### Quick Start

```bash
docker run schemathesis/schemathesis:stable
   run --checks all https://example.schemathesis.io/openapi.json
```

## 🎉 [Open Source: Schemathesis](https://github.com/schemathesis/schemathesis)

- **⏳ Time-Saving**: Auto-generates test cases, cutting down manual effort.
- **🔬 Comprehensive**: Uncover hidden bugs and security vulnerabilities with fuzzing techniques.
- **📚 Flexible**: Compatible with various API specs for a seamless testing experience.
- **🎛️ Customizable**: Tailor your tests with Python extensions.
- **🔄 Reproducible**: Investigate issues with generated code samples for failing tests.

## :octocat: GitHub Integration

### 🚀 [GitHub Action](https://github.com/schemathesis/action)

Integrate API tests directly into your CI/CD pipeline with minimal YAML config.

```yaml
- uses: schemathesis/action@v1
  with:
    schema: 'https://example.schemathesis.io/openapi.json'
```

### 📝 [GitHub App](https://github.com/apps/schemathesis)

Receive concise test summaries right in your PRs, making code review more informative

![schemathesis-github-report](https://github.com/schemathesis/.github/assets/1236561/b6cc4505-b1d6-4a2a-a5dd-b0938042923d)

## ☁️ [SaaS: Additional Features](https://schemathesis.io)

For advanced needs:

- 🌟 Enhanced data generation: Discover more issues before they hit production.
- ✅ Detailed checks: Conduct granular assessments for stronger API integrity.
- 📊 Graphical results: Visualize your API health and performance metrics.

[Quick Start Guide for SaaS](https://docs.schemathesis.io/quick-start)
