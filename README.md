# Platform Control Plane

Use this repository to request help or work from the Thunderbird Platform Engineering team. Open a [Platform Engineering request](https://github.com/thunderbird/routing/issues/new?template=platform-request.yml) for infrastructure, identity, observability, CI/CD, security, deliverability, or other platform needs. You can also use the form when you are unsure which team owns the work.

Describe the outcome you need, the impact, and any timing constraints. New open issues automatically appear in the Platform Infrastructure project's **Needs Triaged** column. A Platform Engineering team member will review the issue, ask for missing details if needed, and decide how to route it. Creating an issue does not commit the team to a delivery date.

**This is a public repository.** Do not include credentials, private customer data, security-sensitive details, or links that reveal secrets in an issue. Summarize sensitive context and ask the team how to share it securely.

## For Platform Engineering triage

1. New open issues from this repository automatically enter the [Platform Infrastructure project](https://github.com/orgs/thunderbird/projects/40) with the **Needs Triaged** status. The project is private; keep the original issue as the request record so the requester can follow public updates.
2. Review the issue. Clarify scope, impact, owner, and timing with the requester.
3. Set the project's **Priority** field during triage:
   - **Emergency** — an active or imminent severe incident needing immediate response.
   - **Urgent** — needs prompt attention because a delivery, customer, or operational impact is time-sensitive.
   - **Not Urgent** — can be scheduled normally; delay has no material impact.
4. Set the project's **Status** to **Backlog** or the appropriate next state; assign an owner and set **Workstream** when known.
5. If another team owns the request, explain the handoff on the issue and close or transfer it as appropriate.

This repository also contains the existing traffic-routing infrastructure under [`pulumi/`](pulumi/). See the [routing infrastructure README](pulumi/README.md) for operational details.
