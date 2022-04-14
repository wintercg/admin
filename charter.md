# The Other Web Platform API Community Group Charter

This Charter is work in progress. To submit feedback, please use https://github.com/owpacg/bootstrap Issues to discuss and provide feedback.

**The name is still a work in progress**

* This Charter: https://github.com/owpacg/bootstrap/blob/main/charter.md
* Previous Charter: N/A
* Start Date: 2022-06
* Last Modifed: 2022-04-14

# Goals

Proposed:

The Other Web Platform API Community Group (OWPA) is intended to augment the work of other existing community and working groups focusing on the development of Web Platform features and APIs by focusing directly on the specific needs of non-Web Browser based implementations. Whereas existing community groups such as the Web Incubator Community Group (WICG) and the Web Hypertext Application Technology Working Group (WHATWG) are each explicitly scoped to features "that would be implemented in a browser or similar user agent", it will be the goal of the OWPA to focus on implementation of those same features in environments such as backend servers, serverless compute, IoT, command-line tools, and so forth -- essentially, everything that is *not* a browser.

Membership of the group is open to everybody but all participants will have signed the [W3C Community Contributor License Agreement](https://www.w3.org/community/about/agreements/cla/).

While the work of the OWPA will involve discussing and developing early ideas for new API specifications, it is not intended that the OWPA Community Group itself will publish its own specifications. Rather, the OWPA will work with existing groups such as WICG and WHATWG to advance proposals within those groups. However, in the case that a given proposal that has the support of the OWPA membership is not adopted to advance by one of these other venues, the OWPA membership can choose to publish a specification as a fallback option.

# Scope of Work

The Community Group will accept for discussion any proposal for a Web Platform feature that would be implemented by any non-Web browser platform, with specific emphasis and priority given to compatibility with equivalent Web Browser implementations. While the focus of the Community Group will be on meeting the needs of non-browser platforms, it will not entertain any proposal that intentionally introduces incompatibilities with any Web Platform APIs implemented by Web Browsers.

All suggestions, pull requests, issues, or comments made about a proposal fall under the CLA. Editors of feature proposals must ensure that no contributions are adopted from anyone that has not signed the CLA.

# Out of Scope

Features or ideas that do not have applicability in non-Web Browser, EcmaScript-based runtimes will be out of scope.

# Deliverables

The Community Group will maintain an index of proposals within the group's GitHub organization. Individual proposals may take many forms, such as discussions for contributions to other existing specifications (e.g. proposed new features, new versions of an existing specification) or even a complete new Web Platform feature specification. Each proposal must have an individual Sponsor that is a member of the OWPA Community Group. The Sponsor will provide regular status updates to both the announcement mailing list and the Community Group's GitHub.

## Non-Normative Reports

The group may produce other Community Group Reports within the scope of this charter but that are not Specifications, for instance use cases, requirements, or white papers.

## Test Suites and Other Software

The group MAY produce test suites to support the Specifications. Please see the GitHub LICENSE file for test suite contribution licensing information.

# Dependencies or Liaisons

It is anticipated that the group will collaborate with appropriate W3C Working Groups, Community Groups, WHATWG Workstreams, and runtime implementors in the development and advancement of all proposals. The following groups are the most likely to adopt proposals from this group:

* Web Incubator Community Group
* Multiple WHATWG Work streams including (but not limited to): DOM, HTML, Encoding, Fetch, File System, Infra, Streams, URL, Web IDL, and WebSockets.
* Web Applications Working Group
* Non-browser EcmaScript-based runtime platforms such as Node.js, Deno, Cloudflare Workers, and others.

# Community and Business Group Process

The group operates under the Community and Business Group Process. Terms in this Charter that conflict with those of the Community and Business Group Process are void.

As with other Community Groups, W3C seeks organizational licensing commitments under the W3C Community Contributor License Agreement (CLA). When people request to participate without representing their organization's legal interests, W3C will in general approve those requests for this group with the following understanding: W3C will seek and expect an organizational commitment under the CLA starting with the individual's first request to make a contribution to a group Deliverable. The section on Contribution Mechanics describes how W3C expects to monitor these contribution requests.

The W3C Code of Ethics and Professional Conduct applies to participation in this group.

# Work Limited to Charter Scope

The group will not publish Specifications on topics other than those listed under Specifications above. See below for how to modify the charter.

# Contribution Mechanics

Substantive Contributions to Specifications can only be made by Community Group Participants who have agreed to the W3C Community Contributor License Agreement (CLA).

Specifications created in the Community Group must use the W3C Software and Document License. All other documents produced by the group should use that License where possible.

Community Group participants agree to make all contributions in the GitHub repo the group is using for the particular document. This may be in the form of a pull request (preferred), by raising an issue, or by adding a comment to an existing issue.

All Github repositories attached to the Community Group must contain a copy of the CONTRIBUTING and LICENSE files.

# Transparency

The group will conduct all of its technical work in public. If the group uses GitHub, all technical work will occur in its GitHub repositories (and not in mailing list discussions). This is to ensure contributions can be tracked through a software tool.

Meetings may be restricted to Community Group participants, but a public summary or minutes must be posted to the group's public mailing list, or to a GitHub issue if the group uses GitHub.

# Decision Process

This group will seek to make decisions where there is consensus. Groups are free to decide how to make decisions (e.g. Participants who have earned Committer status for a history of useful contributions assess consensus, or the Chair assesses consensus, or where consensus isn't clear there is a Call for Consensus [CfC] to allow multi-day online feedback for a proposed course of action). It is expected that participants can earn Committer status through a history of valuable contributions as is common in open source projects. After discussion and due consideration of different opinions, a decision should be publicly recorded (where GitHub is used as the resolution of an Issue).

If substantial disagreement remains (e.g. the group is divided) and the group needs to decide an Issue in order to continue to make progress, the Committers will choose an alternative that had substantial support (with a vote of Committers if necessary). Individuals who disagree with the choice are strongly encouraged to take ownership of their objection by taking ownership of an alternative fork. This is explicitly allowed (and preferred to blocking progress) with a goal of letting implementation experience inform which spec is ultimately chosen by the group to move ahead with.

Any decisions reached at any meeting are tentative and should be recorded in a GitHub Issue for groups that use GitHub and otherwise on the group's public mail list. Any group participant may object to a decision reached at an online or in-person meeting within 7 days of publication of the decision provided that they include clear technical reasons for their objection. The Chairs will facilitate discussion to try to resolve the objection according to the decision process.

It is the Chairs' responsibility to ensure that the decision process is fair, respects the consensus of the CG, and does not unreasonably favour or discriminate against any group participant or their employer.

# Chair Selection

Participants in this group choose their Chair(s) and can replace their Chair(s) at any time using whatever means they prefer. However, if 5 participants, no two from the same organisation, call for an election, the group must use the following process to replace any current Chair(s) with a new Chair, consulting the Community Development Lead on election operations (e.g., voting infrastructure and using RFC 2777).

Participants announce their candidacies. Participants have 14 days to announce their candidacies, but this period ends as soon as all participants have announced their intentions. If there is only one candidate, that person becomes the Chair. If there are two or more candidates, there is a vote. Otherwise, nothing changes.
Participants vote. Participants have 21 days to vote for a single candidate, but this period ends as soon as all participants have voted. The individual who receives the most votes, no two from the same organisation, is elected chair. In case of a tie, RFC2777 is used to break the tie. An elected Chair may appoint co-Chairs.
Participants dissatisfied with the outcome of an election may ask the Community Development Lead to intervene. The Community Development Lead, after evaluating the election, may take any action including no action.

# Amendments to this Charter

The group can decide to work on a proposed amended charter, editing the text using the Decision Process described above. The decision on whether to adopt the amended charter is made by conducting a 30-day vote on the proposed new charter. The new charter, if approved, takes effect on either the proposed date in the charter itself, or 7 days after the result of the election is announced, whichever is later. A new charter must receive 2/3 of the votes cast in the approval vote to pass. The group may make simple corrections to the charter such as deliverable dates by the simpler group decision process rather than this charter amendment process. The group will use the amendment process for any substantive changes to the goals, scope, deliverables, decision process or rules for amending the charter.
