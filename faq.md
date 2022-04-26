# The Other Web Platform API Community Group

## Who are we?

This community group is a group of people who are interested in using Web
Platform APIs outside of the browser, namely on the server (Deno / Node) or edge
runtimes (Cloudflare Workers / Deno). The group currently consists of members
from the following organizations:

- Bloomberg
- Cloudflare
- Deno
- Node.js
- Shopify
- Vercel

The group is open to anyone who also shares the interest in using Web Platform
APIs outside of the browser.

## What are we trying to do?

The ultimate goal of the group is to promote runtimes supporting a comprehensive
unified API surface that JavaScript developers can rely on regardless of the
runtime they are using: be it browsers, servers, embedded applications, or edge
runtimes.

The members of the group want to provide a space to better coordinate between
browser vendors and other implementors on how Web Platform APIs can be best
implemented and used outside of browsers.

### How are we trying to do this?

We want to provide guidance and documentation on how server side runtimes can
best implement Web Platform APIs and to what extent they could deviate from
browsers.

We want to provide feedback to spec authors of Web Platform APIs from the view
point of non-Browser runtimes to help them make informed decisions about future
specification changes.

We want to coordinate and propose updates to existing Web Platform APIs (in
existing venues) that we think would benefit the goal of a comprehensive unified
API surface for all JS developers.

## Why are we doing this?

The members of this group all share the belief that a comprehensive unified API
surface for JS runtimes is something that would benefit the JS community as a
whole. In the past members have individually worked on making this a reality.

This disparate approach with little coordination has historically led to much
confusion between not just browser vendors, spec authors, and other
implementors, but also between non browser implementors and other non browser
implementors on topics of unified API. This was often caused by the fact that
discussions were spread over various disparate issue and PR comments with often
little context or cohesion between them.

We think that by working together more tightly we can provide browser vendors
and specification editors with more meaningful feedback from users of
non-browser JS runtimes. This will help them make informed decisions about
future specification changes that relate to the goal of a comprehensive unified
API surface for JS runtimes.

## What are we NOT trying to do?

We are not trying to be a specification body that specifies new APIs. We want to
work with members of existing specification bodies to improve existing APIs.

We will never fork or create new versions of existing specifications. For any
change we propose, the goal is always for it to be incorporated into an upstream
spec in an existing venue (such as WHATWG or W3C).

We are not trying to shift the focus of Web Platform APIs to only serve
non-browser runtimes. We want to see more API surface that is useful and works
great both in browsers and in other runtimes.
