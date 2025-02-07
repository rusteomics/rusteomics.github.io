# Decision making

This document outlines the principles and processes that the Rusteomics teams follows when
making decisions. It is intended to provide transparency and predictability to the community, and
to ensure that decisions are made in a way that is consistent with the project’s values.

These principles were adapted from the [Rust decision making process][rust-decision-making], which
is originally licensed under MIT/Apache-2.0. See
[github.com/rust-lang/lang-team][rust-decision-making-source] for the original source and full
licensing terms.

## Principles of decision making

- Embrace differing viewpoints. When someone raises a concern, treat it as an opportunity to refine
  the design and to uncover and discuss the values underlying that concern. Dissent should be
  approached in a friendly, collaborative spirit.

- Thoroughly understand and collaboratively address concerns. No concern can be resolved without
  first comprehending it, including the fundamental values behind it. We demonstrate our
  understanding by documenting the issue and considering potential trade-offs in line with Rust’s
  design principles. Our goal is to find solutions that satisfy all parties’ values, rather than
  merely seeking compromises that are acceptable but do not fully address everyone’s concerns.

- Avoid forcing irreversible decisions. Whenever possible, decisions should be made in a reversible
  manner. If an irreversible choice (such as stabilizing a feature) must be made, heightened care
  must be taken to consider dissent. In such cases, attempt to find a superior alternative, establish
  common ground that can lead to consensus, or propose an intermediate step that tackles the same use
  case while allowing further evaluation. If none of these paths are feasible, consider taking no
  action at all, as refraining from change should generally be the simpler option. The threshold for
  moving forward with an irreversible decision in spite of an objection should be high.

- Respect expertise. When working through a concern, or in situations where an objection might be
  overridden, place considerable weight on the insights and recommendations of knowledgeable
  individuals. This includes team advisors, experts in the relevant field, and leaders or
  contributors in associated projects.

- Documenting the rationale fosters consistent, high-quality decisions. Even if an objection is
  ultimately not sustained, it should always be recorded, along with the reasons behind the team’s
  choice to proceed and any remaining open questions to revisit. The team member who originally
  raised the concern has the right to draft this record, framing any unresolved issues (within
  reasonable bounds).

- Consensus does not require unanimity. In this context, consensus means that every voice has been
  heard and every concern addressed—even if some objections are not deemed blocking. The team must
  collectively consider the final outcome acceptable, but this does not imply complete agreement
  from every individual.

## Decision making process

1. **Proposal**: A community member proposes a decision by opening an issue, pull request, or
   discussion thread in the appropriate repository. The proposal should include a clear description
   of the problem, the proposed solution, and the rationale behind it.

2. **Discussion**: The community discusses the proposal, asking questions and raising concerns. The
   goal is to ensure that everyone understands the proposal and its implications, and to identify
   any potential issues that need to be addressed.

3. **Resolution**: The community reaches a decision by consensus. If there are unresolved concerns,
   the proposal may be revised or postponed until they can be addressed. If consensus cannot be
   reached, the problem will be escalated to be discussed at an online meeting of the Rusteomics
   core team.

4. **Core team discussion (optional)**: If the community is unable to reach consensus, the proposal
   may be escalated to the Rusteomics core team for further discussion. The core team may choose to
   accept the proposal as-is, request revisions, or reject it outright. The outcome of this
   discussion is then communicated back to the community in the original issue, pull request, or
   discussion thread.

5. **Implementation**: Once a decision has been reached, the proposal is implemented by the
   community member who proposed it, or by another community member who volunteers to do so. The
   implementation should follow the guidelines outlined in the proposal, and should be reviewed by
   the community to ensure that it meets the project’s standards. This review process follows the
   same steps outlined here.

[rust-decision-making]: https://rust-lang.github.io/team/working-groups/decision-making.html
[rust-decision-making-source]: https://github.com/rust-lang/lang-team/blob/401f90116f28f07fd7c4680869add68f71441a2a/src/decision_process.md
