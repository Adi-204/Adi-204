### Hi, I'm Adi 👋

I maintain the [AsyncAPI Generator](https://github.com/asyncapi/generator), where I'm a code owner and the repo's first Templates Champion ([CODEOWNERS](https://github.com/asyncapi/generator/blob/master/CODEOWNERS)). I got here through [Google Summer of Code 2025](https://gist.github.com/Adi-204/a4040124ed8cb510465e8e38b1fd422d). Most of my time goes into code generation for event-driven APIs: the templates, the shared libraries behind them, and the CI and review process that keep a busy monorepo healthy.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adi-boghawala/)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/AdiBoghawala)
[![Medium](https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@adiboghawala)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:boghawalaadi@gmail.com)

## What I'm working on 🔭

<table>
  <tr style="vertical-align: top;">
    <td width="50%">
      <h3><a href="https://github.com/asyncapi/generator">AsyncAPI Generator</a></h3>
      <p>Generates anything from an AsyncAPI document using templates. I review PRs, triage issues, mentor new contributors, and work on the baked-in client templates and the packages around them.</p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/Adi-204/asyncapi-mcp-server">AsyncAPI MCP Server</a></h3>
      <p>An <a href="https://modelcontextprotocol.io/">MCP</a> server that lets any MCP client (Claude, Cursor, VS Code) parse, validate, lint and convert AsyncAPI documents, generate models with Modelina, and run the Generator. Published on <a href="https://www.npmjs.com/package/asyncapi-mcp-server">npm</a>.</p>
    </td>
  </tr>
</table>

## Contributions to the AsyncAPI Generator

**Libraries and templates**
- [`@asyncapi/keeper`](https://github.com/asyncapi/generator/tree/master/apps/keeper): a message validation library I started ([#1618](https://github.com/asyncapi/generator/pull/1618)), now used by the JavaScript WebSocket client to validate messages ([#1747](https://github.com/asyncapi/generator/pull/1747)).
- [`@asyncapi/generator-components`](https://github.com/asyncapi/generator/tree/master/packages/components): moved the WebSocket client components that every language duplicated into one shared package ([migration PRs](https://github.com/asyncapi/generator/pulls?q=is%3Apr+author%3AAdi-204+is%3Amerged+%22generator-components%22)).
- Spec-aware example files for the Dart, JavaScript and Python WebSocket clients ([#2139](https://github.com/asyncapi/generator/pull/2139)).
- Template config loading pulled out of `generator.js` into its own module, adding `.ageneratorrc` support ([#1655](https://github.com/asyncapi/generator/pull/1655)).

**Testing**
- One integration test suite shared by all WebSocket clients, replacing per-language copies that were about 80% identical ([#1630](https://github.com/asyncapi/generator/pull/1630), [#2042](https://github.com/asyncapi/generator/pull/2042)).

**Maintainer tooling**
- PR review checklist bot ([#1641](https://github.com/asyncapi/generator/pull/1641)), changeset release alignment check ([#2204](https://github.com/asyncapi/generator/pull/2204)), check that generated docs are up to date ([#2096](https://github.com/asyncapi/generator/pull/2096)), and GitHub Actions pinned to commit SHAs ([#2255](https://github.com/asyncapi/generator/pull/2255)).
- AI-assisted maintenance: `AGENTS.md` plus a CodeRabbit knowledge base for reviews ([#2065](https://github.com/asyncapi/generator/pull/2065), [#1817](https://github.com/asyncapi/generator/pull/1817)), and agent skills for promoting shared components and porting features between clients ([#2099](https://github.com/asyncapi/generator/pull/2099), [#2217](https://github.com/asyncapi/generator/pull/2217)).

## Writing ✍️

I write on [Medium](https://medium.com/@adiboghawala), mostly about open source and what I've learned along the way.

- [Google Summer of Code 2025 with AsyncAPI: final project report](https://gist.github.com/Adi-204/a4040124ed8cb510465e8e38b1fd422d)
- [My GSoC 2025 Progress with AsyncAPI: Beyond Just Coding](https://medium.com/@adiboghawala/my-gsoc-2025-progress-with-asyncapi-beyond-just-coding-1a8212352819)
- [Contribute. Connect. Get Selected: My GSoC Story](https://medium.com/@adiboghawala/contribute-connect-get-selected-my-gsoc-story-e7548ca1f1ad)
- [KWoC | Kharagpur Winter of Code 2024: Project Report](https://medium.com/@adiboghawala/kwoc-kharagpur-winter-of-code-2024-project-report-357213b9108e)

## Programs

- **Google Summer of Code 2025**, AsyncAPI: [AsyncAPI Generator Maintainership](https://summerofcode.withgoogle.com/programs/2025/projects/MsWQPcNn), mentored by [Lukasz Gornicki](https://github.com/derberg)
- **Kharagpur Winter of Code 2024**

<details>
  <summary>Earlier projects</summary>

- [SkinCancerClassifier](https://github.com/Adi-204/SkinCancerClassifier): a CNN that classifies dermoscopy images of skin lesions into seven disease classes.
- [python-mqtt-client-template](https://github.com/Adi-204/python-mqtt-client-template): an AsyncAPI Generator template for a Python MQTT client.

</details>
