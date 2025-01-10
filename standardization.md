## Standardization Update (2024)

As of September 2024, the WinterCG co-chairs (@lucacasonato, @CanadaHonk) and multiple participants agree to move standardization of WinterCG away from W3C and towards Ecma, as a new Ecma Technical Committee ("WinterTC"). We propose to formally take this decision in the WinterCG meeting on 2024-09-19.

EDIT: As of December 2024, WinterTC has been formed, with @lucacasonato and @andreubotella as its co-chairs.

### What problem are we trying to solve?

We want to standardize WinterCG work, especially the Minimum Common API. This is not possible in a W3C Community Group:

> In short: moving this work to ECMA now would require a bit of work to ensure the IPR commitments are managed, but that's not the end of the world; however, I would STRONGLY recommend that WinterCG not be considered "where the standard is developed" in the future; that should either be a WG or elsewhere (like ECMA) that is designed for that work.

https://github.com/wintercg/admin/issues/73#issuecomment-2334896142

### How would WinterTC operate?

WinterTC is proposed to operate very similarly to TC39, in terms of Ecma procedures. Many WinterCG have had positive experiences with TC39 which we would like to replicate, including Ecma's Invited Expert policy and its application within TC39, which has been critical for inclusion. The group may also create a self-nomination form for invited experts (to be reviewed by chairs) but the formal structure (where IEs are approved Ecma management) remains the same. We believe easy and open access to the group is important to allow both individuals and companies to easily contribute to and follow the specifications we are to produce.

We initially proposed a structure spanning a W3C Community Group and an Ecma Technical Committee. However, we have decided not to take this path due to the great difficulty of making the IPR transfer from the CG to the TC legally sound, low-friction and continuous.[^1] In any case, technical standards development work will need to take place in a TC or WG, rather than a W3C CG.

### Why Ecma instead of W3C?

- There is an emerging critical mass of Ecma members which are members of Ecma and want to participate in WinterCG, whereas certain key WinterCG participants are not W3C members (including both co-chairs).
- In some members' personal experience, Ecma has been easier to work with for outside contributors than W3C WGs (eg invited experts).[^2] W3C members have emphasized to WinterCG participants that the W3C IE system works well in some WGs, but participants still felt more comfortable and secure about Ecma.
- WinterCG's work generally seems more aligned with JavaScript than the web, so multiple people see Ecma as a more fitting place as it also houses TC39.

### What are the possible downsides of moving to Ecma?

- Some concerns were raised that it could be more difficult to work with W3C-owned groups as part of Ecma, but our positive experiences working across institutional boundaries, both from WinterCG with WHATWG, and with TC39 with W3C and WHATWG, make us optimistic that this will not be a significant impediment to our work. We are happy to work with W3C to alleviate any specific concerns about this.[^2]
- A migratory effort to move from W3C to Ecma will be required to ask contributors to relicense IPR appropriately, re-invite invited experts, etc. Given the one-time nature of this transition, and the small number of WinterCG participants, we're optimistic that it can be done.[^2]

[^1]: https://github.com/wintercg/admin/issues/58
[^2]: https://github.com/wintercg/admin/issues/74