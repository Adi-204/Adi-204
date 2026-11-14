### Hi, I'm Adi 👋

I'm a core maintainer of the [AsyncAPI Generator](https://github.com/asyncapi/generator), a journey that started with [Google Summer of Code 2025](https://gist.github.com/Adi-204/a4040124ed8cb510465e8e38b1fd422d). Most of my time goes into code generation for event-driven APIs and keeping the generator monorepo healthy.

## What I'm working on 🔭

<table>
  <tr style="vertical-align: top;">
    <td width="50%">
      <h3><a href="https://github.com/asyncapi/generator">AsyncAPI Generator</a></h3>
      <p>Generates anything from an AsyncAPI document using templates. I review PRs, triage issues, mentor new contributors, and work on the templates and the packages around them.</p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/Adi-204/asyncapi-mcp-server">AsyncAPI MCP Server</a></h3>
      <p>An <a href="https://modelcontextprotocol.io/">MCP</a> server that lets AI assistants parse, validate and convert AsyncAPI documents, generate models, and run the Generator.</p>
    </td>
  </tr>
</table>

## Tooling

- [AI-assisted maintenance](https://github.com/asyncapi/generator/tree/master/.claude/skills) - Agent guidelines, AI code review setup, and agent skills that let contributors and maintainers automate repetitive work in the generator.
- [AsyncAPI Keeper](https://github.com/asyncapi/generator/tree/master/apps/keeper) - A library I started for validating messages against AsyncAPI documents, used by the generated clients.
- [Generator Components](https://github.com/asyncapi/generator/tree/master/packages/components) - Reusable components for building templates in any language, so templates don't duplicate the same logic.
- [Baked-in templates](https://github.com/asyncapi/generator/tree/master/packages/templates) - Official templates shipped inside the generator, like the WebSocket clients for JavaScript, Python, Dart and Java and the Kafka Java Quarkus client.
- [Generator Hooks](https://github.com/asyncapi/generator/tree/master/apps/hooks) - Built-in lifecycle hooks for the generator, like saving the bundled AsyncAPI document next to the generated output.
- [Generator React SDK](https://github.com/asyncapi/generator/tree/master/apps/react-sdk) - The React render engine templates are written with, currently being upgraded to React 18.
- [AsyncAPI CLI](https://github.com/asyncapi/cli) - The command line tool for working with AsyncAPI documents, which runs the generator under the hood.
- [Headlamp](https://github.com/kubernetes-sigs/headlamp) - A Kubernetes web UI, where I contribute fixes to the app and its plugins.

## Writing ✍️

I write on [Medium](https://medium.com/@adiboghawala), mostly about open source and what I've learned along the way.

- [Google Summer of Code 2025 with AsyncAPI: final project report](https://gist.github.com/Adi-204/a4040124ed8cb510465e8e38b1fd422d)
- [My GSoC 2025 Progress with AsyncAPI: Beyond Just Coding](https://medium.com/@adiboghawala/my-gsoc-2025-progress-with-asyncapi-beyond-just-coding-1a8212352819)
- [Contribute. Connect. Get Selected: My GSoC Story](https://medium.com/@adiboghawala/contribute-connect-get-selected-my-gsoc-story-e7548ca1f1ad)
- [KWoC | Kharagpur Winter of Code 2024: Project Report](https://medium.com/@adiboghawala/kwoc-kharagpur-winter-of-code-2024-project-report-357213b9108e)

## Programs

- **Google Summer of Code 2025**, AsyncAPI: [AsyncAPI Generator Maintainership](https://summerofcode.withgoogle.com/programs/2025/projects/MsWQPcNn)
- **AsyncAPI Maintainer Program 2026**: mentor for the AsyncAPI Generator
- **Kharagpur Winter of Code 2024**
