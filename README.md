# Platform Control Plane

Use this repository to request help or work from the Thunderbird Platform Engineering team. Open a [Platform Engineering request](https://github.com/thunderbird/routing/issues/new?template=platform-request.yml) for infrastructure, identity, observability, CI/CD, security, deliverability, or other platform needs. You can also use the form when you are unsure which team owns the work.

Describe the outcome you need, the impact, and any timing constraints. A Platform Engineering team member will review the issue, ask for missing details if needed, and decide how to route it. Creating an issue does not commit the team to a delivery date.

**This is a public repository.** Do not include credentials, private customer data, security-sensitive details, or links that reveal secrets in an issue. Summarize sensitive context and ask the team how to share it securely.

## For Platform Engineering triage

1. Review new issues in this repository. Clarify scope, impact, owner, and timing with the requester.
2. Once triaged and accepted for Platform Engineering work, add the issue to the [Platform Infrastructure project](https://github.com/orgs/thunderbird/projects/40). The project is private; keep the original issue as the request record so the requester can follow public updates.
3. Set the project's **Status** to **Backlog** or the appropriate next state; assign an owner and set **Priority** and **Workstream** when known.
4. If another team owns the request, explain the handoff on the issue and close or transfer it as appropriate. Do not add untriaged requests to the project.

This repository also contains the existing traffic-routing infrastructure under [`pulumi/`](pulumi/). See the [routing infrastructure README](pulumi/README.md) for operational details.
