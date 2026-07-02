# Agent Skills (agents-skills)
An index and topic collection covering Agent Skills, the packaged, file-based capability units that AI coding agents load to extend their behavior. Agent Skills bundle instructions, scripts, schemas, and reference material into directories that agents discover, plan against, and execute at runtime, giving organizations a portable way to govern how AI assistants interact with their products and APIs. This collection tracks vendor-published skill repositories (Claude Code skills, Claude Agent SDK skills, Cursor rules, OpenAI Apps SDK skills, and capability packages) shipped by API providers across developer tools, data platforms, SaaS, and infrastructure.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - Agent Skills, Claude Skills, Capability Packages, AI Agents, Developer Tooling

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Skill Definition Schema](https://raw.githubusercontent.com/api-evangelist/agents-skills/refs/heads/main/json-schema/agents-skills-skill-definition-schema.json)
- [JSONSchema - Skill Manifest Schema](https://raw.githubusercontent.com/api-evangelist/agents-skills/refs/heads/main/json-schema/agents-skills-skill-manifest-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/agents-skills/refs/heads/main/json-ld/agents-skills-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/agents-skills/refs/heads/main/vocabulary/agents-skills-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| File-Based Capability Packaging | Agent Skills bundle markdown instructions, executable scripts, schemas, and reference material into versioned directories that agents can load deterministically at runtime. |
| Vendor-Published Skill Repositories | API providers ship official GitHub repositories such as resend-skills, ngrok/agent-skills, postman-skills, and jfrog-skills to deliver first-party automation behavior for their products. |
| Progressive Disclosure of Context | Skills surface a short SKILL.md frontmatter for discovery, then load deeper instructions, scripts, and assets only when an agent activates them, keeping token usage low. |
| Agent-Executable Tooling | Skills package shell, Python, or Node scripts alongside instructions so agents can perform multi-step work instead of relying on prose-only prompting. |
| Multi-Runtime Compatibility | Skill formats are emerging across Claude Code, Claude Agent SDK, Cursor, OpenAI Apps SDK, and Gemini, with vendors publishing parallel skill sets for each runtime. |
| Skill Discovery and Governance | Organizations curate skill catalogs, sign skill manifests, and gate skill activation through allow lists so AI agents only run vetted capability packages. |
| API-First Skill Generation | Skills are increasingly generated from OpenAPI, AsyncAPI, and APIs.json descriptions so each API operation becomes a callable, governed capability inside an agent. |
| Open Skill Ecosystem | A growing ecosystem of community-maintained skill registries and indexes complements vendor repos, mirroring how npm and PyPI formed around packages. |

## Use Cases

| Name | Description |
|------|-------------|
| First-Party Product Skills | SaaS vendors ship official skill repos so AI agents in Claude Code or Cursor can create resources, run reports, and operate their products without bespoke prompt engineering. |
| Internal Developer Platform Skills | Platform teams package CI/CD, deployment, and observability workflows as governed skills so every engineering agent uses the same approved automations. |
| API Onboarding and Education | API providers use skills to walk agents through authentication, sandbox setup, and "hello world" requests, accelerating time-to-first-call for developer-led agents. |
| Governed Capability Distribution | Compliance-sensitive organizations distribute skills with allow-lists, signing, and audit trails to ensure only approved AI behaviors run against production systems. |
| API Specification to Skill Pipelines | Teams convert OpenAPI specs into skill bundles (one operation per tool) so agents get typed, governed access to every endpoint without writing custom wrappers. |
| Cross-Runtime Skill Portability | Vendors maintain mirror skill sets for Claude, Cursor, and OpenAI Apps SDK, giving customers a consistent experience across whichever coding agent they choose. |
| Skill-Driven Customer Support | Support and DevRel teams publish skills that diagnose common issues, pull logs, and open tickets, letting customer-side agents resolve problems autonomously. |
| Sandbox and Test Environment Skills | Skill bundles provision throwaway environments, seed test data, and tear down resources so agents can exercise APIs safely during development and CI. |

## Integrations

| Name | Description |
|------|-------------|
| Claude Code | Anthropic's official coding agent loads skills from the .claude/skills directory and surfaces them as plan-then-execute capabilities. |
| Claude Agent SDK | The Claude Agent SDK lets developers embed skill loading and execution into their own agent harnesses with the same SKILL.md contract as Claude Code. |
| Cursor | Cursor consumes vendor rules and skill-style instruction bundles to extend its in-editor coding agent with provider-specific behavior. |
| OpenAI Apps SDK | The OpenAI Apps SDK provides a skill-equivalent surface so apps and agents on the OpenAI platform can ship packaged capabilities. |
| Google Gemini | Gemini's GEMINI.md and skill-style instruction files let vendors target Google's coding agent surface alongside Claude and Cursor. |
| GitHub | GitHub hosts the canonical distribution channel for skill repositories, including vendor-published agent-skills, claude-skills, and *-skills repos. |
| Postman | Postman's skill repository ships first-party capabilities for working with Postman collections, workspaces, and the Postman API from coding agents. |
| Anthropic | Anthropic publishes the SKILL.md format, reference skill repositories, and the Skills feature in Claude Code that anchors the broader ecosystem. |

## Artifacts

Machine-readable specifications for the Agent Skills topic.

### JSON Schema

- [Skill Definition Schema](json-schema/agents-skills-skill-definition-schema.json)
- [Skill Manifest Schema](json-schema/agents-skills-skill-manifest-schema.json)

### JSON Structure

- [Skill Definition Structure](json-structure/agents-skills-skill-definition-structure.json)
- [Skill Manifest Structure](json-structure/agents-skills-skill-manifest-structure.json)

### JSON-LD

- [Agent Skills Context](json-ld/agents-skills-context.jsonld)

## Vocabulary

- [Agent Skills Vocabulary](vocabulary/agents-skills-vocabulary.yaml) — Unified taxonomy for skill bundles covering resources, actions, workflows, runtimes, and personas across vendor-published skill repositories.

## Network

This index references the following Agent Skills provider repositories:

- [ActiveCampaign](https://github.com/api-evangelist/activecampaign)
- [Airbyte](https://github.com/api-evangelist/airbyte)
- [Airtable](https://github.com/api-evangelist/airtable)
- [Android](https://github.com/api-evangelist/android)
- [Angular](https://github.com/api-evangelist/angular)
- [Anthropic](https://github.com/api-evangelist/anthropic)
- [Anthropic Claude](https://github.com/api-evangelist/anthropic-claude)
- [Apify](https://github.com/api-evangelist/apify)
- [Apollo Config](https://github.com/api-evangelist/apollo-config)
- [Apollo GraphQL](https://github.com/api-evangelist/apollo-graphql)
- [Appium](https://github.com/api-evangelist/appium)
- [Appwrite](https://github.com/api-evangelist/appwrite)
- [Atlassian](https://github.com/api-evangelist/atlassian)
- [Auth0](https://github.com/api-evangelist/auth0)
- [Box](https://github.com/api-evangelist/box)
- [Canva](https://github.com/api-evangelist/canva)
- [Cerbos](https://github.com/api-evangelist/cerbos)
- [Claude](https://github.com/api-evangelist/claude)
- [Contentful](https://github.com/api-evangelist/contentful)
- [Databricks](https://github.com/api-evangelist/databricks)
- [Docsify](https://github.com/api-evangelist/docsify)
- [Figma](https://github.com/api-evangelist/figma)
- [Fivetran](https://github.com/api-evangelist/fivetran)
- [GEMINI.md](https://github.com/api-evangelist/gemini-md)
- [GitHub](https://github.com/api-evangelist/github)
- [Google Gemini](https://github.com/api-evangelist/google-gemini)
- [Hookdeck](https://github.com/api-evangelist/hookdeck)
- [HubSpot](https://github.com/api-evangelist/hubspot)
- [Hugging Face](https://github.com/api-evangelist/hugging-face)
- [Jentic](https://github.com/api-evangelist/jentic)
- [JFrog](https://github.com/api-evangelist/jfrog)
- [MailerLite](https://github.com/api-evangelist/mailerlite)
- [Microsoft TypeScript](https://github.com/api-evangelist/microsoft-typescript)
- [MongoDB](https://github.com/api-evangelist/mongodb)
- [ngrok](https://github.com/api-evangelist/ngrok)
- [OpenAI](https://github.com/api-evangelist/openai)
- [Postman](https://github.com/api-evangelist/postman)
- [Prisma](https://github.com/api-evangelist/prisma)
- [Pulumi](https://github.com/api-evangelist/pulumi)
- [Replicate](https://github.com/api-evangelist/replicate)
- [Resend](https://github.com/api-evangelist/resend)
- [Sanity](https://github.com/api-evangelist/sanity)
- [Speakeasy](https://github.com/api-evangelist/speakeasy)
- [Supabase](https://github.com/api-evangelist/supabase)
- [Temporal](https://github.com/api-evangelist/temporal)
- [TypeScript](https://github.com/api-evangelist/typescript)
- [Webflow](https://github.com/api-evangelist/webflow)
- [WorkOS](https://github.com/api-evangelist/workos)
- [Zoom](https://github.com/api-evangelist/zoom)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
