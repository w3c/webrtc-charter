# WebRTC Working Group workmode

This document proposes a set of guiding principles to ensure clear responsibilities and set expectations in enabling productive discussions towards consensus in the WebRTC Working Group.

## Issue management

The Chairs are responsible for prioritizing issues that need a Working Group decision, with a focus on ensuring practical interoperable implementations of the relevant specifications, including through input from implementers on issues with the most impact on their implementation effort. Prioritizing these issues includes managing possible interdependencies between them. For high-priority issues, the Chairs should maintain a clear understanding of what might be blocking their progress and specific plans to drive a resolution, using synchronous and asynchronous approaches.

An issue with more than 10 comments makes it difficult for people to grasp; issue comments should only be used to bring new information that would help the group make a decision. In particular:
* An argument that has already been made in an issue thread does not need to be repeated.
* Beyond an initial tagging of relevant participants, issue comments should not be used to bring attention from or to a particular individual.

The Chairs may temporarily lock an issue where comments are no longer helping make consensus emerge. The Chairs are responsible for suggesting a path forward in such a situation.

When progress in an issue stalls (e.g. because no consensus seems to be emerging), Working Group participants that need rapid resolution of the said issue (e.g. because of implementation schedule) should raise it by email to the Chairs' attention, contextualizing the time-sensitiveness. The Chairs are then responsible for assessing the priority of the said issue.

### In Practice
Requests for issue resolution prioritization to be sent to webrtc-chairs@w3.org with an explanation of what should motive that priority (implementation schedule, spec dependencies, process considerations, developers need, security/privacy risk)

 #### Prioritizing issues
Priorities are set by the WG chairs, based on requests. An issue may be in two states: Prioritized or “normal”. The WG chairs can move issues in both directions.

When considering to move an issue, the chairs will consider:
* Is the case made to prioritize the issue convincing?
   * Implementation schedule: how critical to interop & adoption is the issue? (i.e. will resolving the issue make the spec work in more browsers, and impact whether a developer would use it)
   * Spec dependencies: how widely implemented / adopted is the spec depending on the resolution of that issue?
   * Process considerations: is resolution needed for a significant process milestone (wide review, CR snapshot, Rec)
   * Developer needs: do we have signals from a diverse set of developers they need progress on the said issue?
   * security/privacy risk: are end users exposed to security/privacy risks until the issue is resolved?
* If not, decline until a more convincing case is made
* If yes, assign a chair as responsible for proposing a path forward; ideally, one as neutral as possible on the topic at hand
   * These issues get reviewed weekly at chairs meeting until they get resolution; they get priority handling during WG & editors meetings
   * Path forward may include:
      * Sense of the room (how strongly do the issue participants feel about the issue? Are they ready to formally object to a contrary decision?) + Chairs decision
      * Summary of trade-offs anchored in the priority of constituents + Chairs decision
      * Formal WG vote


## Github issue etiquette

1. Think over your comments before you write, and check them before submitting. Try to keep them as clear and succinct as possible.

2. Always keep to the topic of the issue. If there are other things you want to bring up, raise additional issues. The aim should be to keep each issue focused on a specific topic.

3. Always remain polite and constructive in your comments. Do not assign intent or interpretations to other contributors' comments.

4. You can attract someone's attention to an issue where their input would be useful, by including an @ sign followed by their github id; but once someone has been flagged in an issue, and if you want to draw their attention to a new point, use discretion in flagging them again publicly (vs contacting them out of band, e.g. by email).

The Chairs are responsible for ensuring the github etiquette is followed by all.

## Meetings under the WebRTC Working Group umbrella

### Working Group Meetings

The (generally monthly) WebRTC Working Group meeting is used to establish the level of Working Group consensus on issues and proposals that require a Working Group decision. The Chairs are responsible for ensuring the highest priority issues get sufficient time to unblock progress, in particular where the decision is time sensitive.

The chairs will prioritize agenda and time boxes based on requests for agenda time.

To get agenda time, an issue should have at least one of:
* A filed issue, with comments showing interest
* A filed PR
* For issues that don’t fit into existing documents: An explainer and/or proposed spec in a publicly accessible repository

Issues that are declared as prioritized issues will be given time ahead of non-prioritized issues.

The chairs will insist that slides presenting the issue are added to the agenda deck at least 2 days before the planned meeting date.


### Editors Meetings
The weekly WebRTC Editors meeting is used to facilitate progress on the editorial work needed to update specifications, through:
* Merging pull requests that represent an existing Working Group decision, to the satisfaction of the spec editors and chairs
* Identifying pull requests that need more editorial work with a well-defined owner (through pull request assignee)
* Identifying pull requests that reveal lack of clarity on the Working Group decision and that needs to be brought back to the group via discussion in an issue; these pull requests should be marked as draft
* Identifying issues whose discussion seem to have converged in consensus, assigning an editor to propose a pull request to codify that consensus

Beyond recognizing consensus in issue discussions, the editors meeting is not expected to make progress on issue resolution.

The agenda is informal; if formality is needed, Bernard will apply it.

### Chairs Meetings
The weekly WebRTC Chairs meeting is used to ensure the coordination of efforts around Working Group meetings, coordination with other groups and organizations, to enable Chairs to formulate Working Group decisions (emerging e.g. from calls for consensus) and to lift any obstacle that may be blocking progress on the development of the group's specifications.

