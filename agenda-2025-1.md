# did:webvh DID Method Work Item Rolling Agenda<!-- omit in toc -->

**Zoom Link**: [https://us02web.zoom.us/j/83119969275?pwd=IZTuXgGLtdLPjPLuB6q8zHXazxHSsU.1](https://us02web.zoom.us/j/83119969275?pwd=IZTuXgGLtdLPjPLuB6q8zHXazxHSsU.1)

**Agenda**: [did:webvh Info Site](https://didwebvh.info/latest/agenda/), [HackMD](https://hackmd.io/k4cIK9vQSlaeg2pdHE51IQ), [did:webvh Repository](https://github.com/decentralized-identity/didwebvh/blob/main/agenda.md) (synchronized after each meeting).

[**WG projects**](https://github.com/decentralized-identity?q=wg-cc&type=&language=) | [DIF page](https://identity.foundation/working-groups/claims-credentials.html) | [Mailing list and Wiki](https://lists.identity.foundation/g/cc-wg) | [Meeting recordings](https://docs.google.com/spreadsheets/d/1wgccmMvIImx30qVE9GhRKWWv3vmL2ZyUauuKx3IfRmA/edit?gid=111226877#gid=111226877)

## Table of Contents<!-- omit in toc -->

- [Meeting Information](#meeting-information)
- [Future Topics](#future-topics)
- [Later Meetings](#later-meetings)
- [Meeting - 19 Jun 2025](#meeting---19-jun-2025)
- [Meeting - 05 Jun 2025](#meeting---05-jun-2025)
- [Meeting - 22 May 2025](#meeting---22-may-2025)
- [Meeting - 08 May 2025](#meeting---08-may-2025)
- [Meeting - 24 Apr 2025](#meeting---24-apr-2025)
- [Meeting - 10 Apr 2025](#meeting---10-apr-2025)
- [Meeting - 27 Mar 2025](#meeting---27-mar-2025)
- [Meeting - 13 Mar 2025](#meeting---13-mar-2025)
- [Meeting - 27 Feb 2025](#meeting---27-feb-2025)
- [Meeting - 13 Feb 2025](#meeting---13-feb-2025)
- [Meeting - 30 Jan 2025](#meeting---30-jan-2025)
- [Meeting - 16 Jan 2025](#meeting---16-jan-2025)
- [Prior Meetings](#prior-meetings)

## Meeting Information

- Before you contribute - **[join DIF]** and [sign the WG charter] (both are required!)
- Meeting Time: Every second Thursday at 9:00 Pacific (~=18:00 Central Europe)
- [Calendar entry]
- [ID WG participation tracking]
- [Zoom room]
- Links and Repositories:
    - [Specification], [Spec Repo], [Information Site]
    - Implementations: [TS], [Python], [Go], [Rust], [Server-Py]
    - Test Suite: [Test Suite]

_Participants are encouraged to turn your video on. This is a good way to build rapport across the contributor community._

_This document is live-edited DURING each call, and stable/authoritative copies live on our github repo under `/agenda.md`, link: [Agenda]._

[join DIF]: https://identity.foundation/join
[sign the WG charter]: https://bit.ly/DIF-WG-select1
[Calendar entry]: https://calendar.google.com/event?action=TEMPLATE&tmeid=NG5jYWowbmZsdWNzM21tYjBsbDIzdG50ZzFfMjAyNDA5MTJUMTYwMDAwWiBkZWNlbnRyYWxpemVkLmlkZW50aXR5QG0&tmsrc=decentralized.identity%40gmail.com&scp=ALL
[Zoom Room]: https://us02web.zoom.us/j/83119969275?pwd=IZTuXgGLtdLPjPLuB6q8zHXazxHSsU.1
[DIF Code of Conduct]: https://github.com/decentralized-identity/org/blob/master/code-of-conduct.md
[ID WG participation tracking]: https://docs.google.com/spreadsheets/d/12hFa574v5PRrKfzIKMgDTjxuU6lvtBhrmLspfKkN4oE/edit#gid=0
[operations@identity.foundation]: mailto:operations@identity.foundation
[did:webvh Specification license]: https://github.com/decentralized-identity/didwebvh/blob/main/LICENSE.md
[Agenda]: https://github.com/decentralized-identity/trustdidweb/blob/main/agenda.md
[Specification]: https://identity.foundation/didwevbvh
[Spec Repo]: https://github.com/decentralized-identity/didwebvh
[did:webvh AnonCreds Method]: https://identity.foundation/didwebvh/anoncreds-method/
[Information Site]: https://didwebvh.info
[Python]: https://github.com/decentralized-identity/didwebvh-py
[TS]: https://github.com/decentralized-identity/didwebvh-ts
[Go]: https://pkg.go.dev/github.com/nuts-foundation/trustdidweb-go
[Server-Py]: https://github.com/decentralized-identity/didwebvh-server-py
[Watcher-Py]: https://github.com/decentralized-identity/didwebvh-watcher-py
[Rust]: https://github.com/decentralized-identity/didwebvh-rs
[Affinidi Rust]: https://github.com/affinidi/affinidi-tdk-rs/tree/main/crates/affinidi-did-resolver/affinidi-did-resolver-methods/did-webvh
[Test Suite]: https://github.com/decentralized-identity/didwebvh-test-suite
[Implementations]: https://github.com/decentralized-identity/didwebvh-implementations
[did:webvh ACA-Py Plugin]: https://github.com/openwallet-foundation/acapy-plugins/tree/main/webvh
[did:webvh Static]: https://github.com/OpSecId/webvh-static
[did:webvh Tutorial]: https://didwebvh.info/latest/demos/understanding_didwebvh/

## Future Topics

- Using the `did:webvh` log format with other DID Methods
- Merging `did:webvh` features into `did:web`?

--------------------------------
## Later Meetings

Agendas for the current set of `did:webvh` Work Item meetings can be in the [Agenda] file.

[Agenda]: https://github.com/decentralized-identity/didwebvh/tree/main/agenda.md

## Meeting - 19 Jun 2025

Time: 9:00 Pacific / 17:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/cxdZE58NpGzcq4ps82KIDY56D180hlN8ciC_2Zf1qy6saNImJzcdEwpIABcClXBJ.J1Y2XDSJ17vFOL73)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Stephen to update the tutorial page on the web info site with Affinidi's tutorial details.
2. Stephen to pursue clarification on witness handling with Glenn from Affinidi, based on Patrick's input.
3. Stephen to add an issue and PR for adding service endpoints to the did:web equivalent of did:webvh.
4. Stephen to add a note about including "also known as" references in both did:webvh and did:web documents.
5. Patrick to update the tutorial to include service endpoints in the did:web example.
6. BC Gov team to continue work on implementing a production-level did:webvh system with policy enforcement mechanisms.
7. Patrick to continue development of the did:webvh server with configurable policy enforcement features.
8. Patrick to develop the endorser service as a plugin for supporting did:webvh in Traction.

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Patrick St. Louis
- Alexander Shenshin
- Sam Curren
- Phillip Long

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:
    1. 

4. Status updates on the implementations
    1. [TS] -- 1.0 is done, next is getting the Credo PR Merged, and getting Universal Resolver to 1.0.
    2. [Python] -- 
    3. [Rust] -- 
    4. [Server-Py] -- focused on enforcing policies for publishing DIDs and resources. BC has a sandbox instance -- equivalent to the BCovrin Test Indy ledger (reset biweekly).
    5. [Watcher-Py] -- Watcher service being stood up. Discussion about using GitHub as a Watcher -- not for production!
    6. [did:webvh AnonCreds Method] -- 
    7. [did:webvh ACA-Py Plugin] -- Watcher notification added.
    8. [Test Suite] -- 
    9. [did:webvh Tutorial] -- Published -- link updated to point to the tutorial

5. To Do's from Last Meeting:

    1. DONE - Stephen to contact DID Method standardization editors and W3C folks regarding moving did:webvh onto a standards track
    2. DONE - Patrick to reach out to Procivis about their Rust implementation and test suite collaboration
    3. DONE - Stephen to contact Affinidi about their Rust implementation and test suite collaboration
    4. DONE - Brian to complete TypeScript implementation 1.0 updates and testing
    5. Brian to merge Credo PR after 1.0 update
    6. Patrick to develop feature file for ACA-Py did:webvh in OWF's Agent Test Harness
    7. Patrick to create generator test suite for listing DID features and log history
    9. DONE - Patrick to follow up with Catena-X about implementing Web VH for their supply chain platform
    10. DONE - Stephen/Patrick to update did:webvh tutorial guidance
    11. Team to add benchmarks for did:webvh implementation

6. Need an inventory of **MUST** statements. Look at how the W3C ReSpec tool flags such statements and see if that can be done in SpecUp.

7. Question from Affinidi about witnesses. The handling logic for adding and pruning witness proofs is tricky. Can/should we make it easier?
    1. Current handling is per individual witness: A witness proof asserts that witness approves of all prior log entries. A proof of a *published* log entry means that all prior proofs from that witness can be removed. The caveat of a "published" log entry, and the need to publish the `witness.json` file **BEFORE** publishing the
    3. Proposal: A witnessed log entry implies all prior log entries are also witnessed?
        1. **Problem**:  Publish two entries of a DID Log together, change the witnesses in the first entry, change the witnesses, in the second, have the new witnesses provide proofs. Since verifiers would not expect the proofs from old witnesses are retained, the scenario would be considered valid -- which is a weakness in the approach.
    5. When there is an unchanged set of witnesses, the two schemes are equivalent.

7. Should the guidance on creating a parallel `did:web` include putting in the implicit services that are part of `did:webvh`?  I think it should be a requirement.  Another point -- add an "alsoKnownAs" in the `did:webvh` DID Doc. Both are non-normative in the `did:webvh` spec. Will add issue and PR.

8. Open Discussion -- what do you want to discuss?

## Meeting - 05 Jun 2025

Time: 9:00 Pacific / 17:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/wdkCmWS4s6ZRvwH6E0MnyX3uR8TWMoSsJcJ1V4QJKwvfLOmQPWZ8vDBA9ytn1Mys.RSQxygtU5GLtIfjG)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Stephen to contact DID Method standardization editors and W3C folks regarding moving did:webvh onto a standards track
2. Patrick to reach out to Procivis about their Rust implementation and test suite collaboration
3. Patrick to contact Affinidi about their Rust implementation and test suite collaboration
4. Brian to complete TypeScript implementation 1.0 updates and testing
5. Brian to merge Credo PR after 1.0 update
6. Patrick to develop feature file for ACA-Py did:webvh in OWF's Agent Test Harness
7. Patrick to create generator test suite for listing DID features and log history
9. Patrick to follow up with Catena-X about implementing Web VH for their supply chain platform
10. Stephen/Patrick to update did:webvh tutorial guidance
11. Team to add benchmarks for did:webvh implementation

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Patrick St. Louis
- Alexander Shenshin
- Sam Curren
- Phillip Long
- Makki Elfatih

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:
    1. DID Methods WG `did:webvh` Deep Dive went well -- [Recording](https://us02web.zoom.us/rec/share/AJ5AINNqN0mc-gDtSsKPjgyknBjXViRsVpXklZFcC4vObcrRxAoXQ3c9kCRkmEKA.ZAK46kp3nq77dWIm), [Presentation Slides](https://bit.ly/didwebvhDD). TBD what comes next...
        1. DIF Recommendation.
        2. Getting onto W3C Standards track.
    3. Ideas for AnonCreds Revocation to address the "No Phone Home" issue for `did:webvh` (and other ledgers) to be discussed at the AnonCreds Working Group Meeting this coming Monday, June 9, 2025 at 7:00 Pacific / 16:00 Central Europe -- [Agenda and Zoom Info](https://lf-hyperledger.atlassian.net/wiki/spaces/ANONCREDS/pages/322797569/2025-06-09+AnonCreds+Working+Group+Meeting)
        1. Discussion ensued about the preception of Phone Home by verifiers at presentation time. Suggestion is to contact Steve McCowan about putting wording into the did:webvh spec about mitigating that.

4. Status updates on the implementations
    1. [TS] -- no new updates -- next up 1.0, getting the Credo PR Merged, and getting Universal Resolver to 1.0.
    2. [Python] -- 1.0rc0 release was created and published.
    3. [Rust] -- no updates to DIF instance. Two new Rust implementations including this one from [Procivis](https://github.com/procivis/one-core/tree/main/lib/one-core/src/provider/did_method/webvh)
    4. [Server-Py] -- The `/whois` has been added -- can receive and publish the VP. Will try to verify the presentation proof, but not the VCs in the VP.  VCs get tricky because of what support is needed for cryptosuites, etc. More thought to be done on this. 1.0rc0 is being published.
    5. [Watcher-Py] -- 
    6. [did:webvh AnonCreds Method] -- done -- potential updates being discussed about revocation.
    7. [did:webvh ACA-Py Plugin] -- work on Witnesses happening. Defined that ACA-Py will do the contacting of the Watchers on receipt of a success message from the `did:webvh` Server.
    8. [Test Suite] -- OpSecID hosts a test `did:webvh` Server that anyone can use -- public auth keys (analagous to the BCovrin Test Indy network). Gets reset regularly on new main branch merges for now. Also looking to add some `did:webvh` tests in OWF's [Agent Test Harness](https://aries-interop.info).
    9. [did:webvh Tutorial] -- New! But the tutorial needs some more detail.

5. To Do's from Last Meeting:

    1. DONE Stephen to populate the deep dive presentation template for the DID Web VH method.
    2. Brian to create benchmarks for the DID Web VH method implementation.
    3. DONE Brian to provide reference for the Universal Resolver status (version 0.5).
    4. DONE Stephen to review and update the DID Traits matrix and method proposal, making any necessary pull requests.
    5. DONE Patrick to continue work on adding a /whois endpoint and support in the Plugin for allowing a DID Controller to publish a verified presentation at the whois endpoint.
    6. DONE Stephen to add the new DID Web VH Watcher implementation (didwebvh-watcher-py repository) to the list of implementations.
    7. DONE Stephen to follow up with Patrick regarding the W3C Test Suite for the DID Web VH method.

6. [did:webvh Tutorial] -- working -- just needs some guidance added.

7. Open Discussion -- what do you want to discuss?

## Meeting - 22 May 2025

Time: 9:00 Pacific / 17:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/play/Bqjxqom9kjufKmRmj4FzrL-odgS11cf1YgDdOv5r1hGPbSp98xZ6eLlB6Ye26ZmCul4N_Am-5mphsYo.sc4qdXQkBI0JeW7o?eagerLoadZvaPages=sidemenu.billing.plan_management&accessLevel=meeting&canPlayFromShare=true&from=share_recording_detail&continueMode=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Fus02web.zoom.us%2Frec%2Fshare%2FjRxrW4UlmKxm2sKfrjxTQk9p1AXvE_YfyiE8KN5da_dHtzdhN3wLaxT10A3TvMVl.R2HMrrz0xotcz-Sz)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Stephen to populate the deep dive presentation template for the DID Web VH method.
2. Brian to create benchmarks for the DID Web VH method implementation.
3. Brian to provide reference for the Universal Resolver status (version 0.5).
4. Stephen to review and update the DID Traits matrix and method proposal, making any necessary pull requests.
5. Patrick to continue work on adding a /whois endpoint and support in the Plugin for allowing a DID Controller to publish a verified presentation at the whois endpoint.
6. Stephen to add the new DID Web VH Watcher implementation (didwebvh-watcher-py repository) to the list of implementations.
7. Stephen to follow up with Patrick regarding the W3C Test Suite for the DID Web VH method.

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Dmitri Zagidulin
- Juan Caballero
- Sebastian Schmittner
- Alexander Shenshin

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:
    1. DIF's TSC has approved the did:webvh DID Method specifcation version 1.0.
    2. Stephen to provide a "deep dive" at the DID Method Standardization Working Group Meeting on May 28, 2025 at 9:00 Pacific / 18:00 Central Europe -- [Zoom Link](https://us02web.zoom.us/j/88676811119?pwd=YxKNPVRvfeBihnIJQUa9i1uDHrPidH.1). Idea is that this will lead to a possible "DIF Recommendation" vote.

3. [Deep dive presentation](https://docs.google.com/presentation/d/1yWXVtWy2xrioztP23lEx26SnNARgqs6cumvdNvammgg/edit?usp=sharing) based on a template provided by DIF. Points we want to highlight?

4. Status updates on the implementations
    1. [TS] -- 
    2. [Python] -- now at 1.0
    3. [Rust] -- 
    4. [Server-Py] -- now at 1.0
    5. [Watcher-Py] -- Created
    6. [did:webvh AnonCreds Method] -- done
    7. [did:webvh ACA-Py Plugin] -- now at 1.0, integrated with Traction. BC Gov Sandbox will soon have did:webvh support.
    8. [Test Suite] -- 
    9. [did:webvh Static] -- 

5. To Do's from Last Meeting:

    1. DONE - Bumblefudge to open a tracking issue on the spec for adding a section on risk mitigation related to "phone home" concerns.
    2. DONE - Bumblefudge to open an issue to review which parts of the Security Consideration section need to be made normative versus non-normative.
    3. Andrew to update the "DNS privacy considerations" section title in the spec to better capture client security concerns.
    4. Patrick to look into creating a Python script that can work with spec-up to count normative statements (sentences containing "must").
    5. ISSUE CREATED - Stephen to add a reference to the JSON schema for the DID Web VH data model in the spec.
    6. ISSUE CREATED - Stephen to move the problem details document to a stable location (suggested: did-webvh.info/security).
    7. ISSUE CREATED - Stephen to create an issue for conducting test runs of large-scale (multi-thousand) updates to a DID.
    8. DONE - Kim Hamilton Duffy to bring forward the 1.0 status of the spec to the TSC.

6. Open Discussion -- what do you want to discuss?

## Meeting - 08 May 2025

Time: 9:00 Pacific / 17:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/play/0cGtM4o0-_LqZJaFXbW1KCLwwJhEmvldBOeiV3iiSlLQ3ZpiHzkVQpgotO3wEIEEY83VZailpJppTFmT.uxX0dB2hk9E4d_zk?eagerLoadZvaPages=sidemenu.billing.plan_management&accessLevel=meeting&canPlayFromShare=true&from=share_recording_detail&continueMode=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Fus02web.zoom.us%2Frec%2Fshare%2F7UfjUK__ahyAmLIWQ6BT1fQS8dYfKrFqMj0pamyMmj5apAasPnpIjkGh9k8XoO8C.djQ0z0q1-KhRcUN6)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Bumblefudge to open a tracking issue on the spec for adding a section on risk mitigation related to "phone home" concerns.
2. Bumblefudge to open an issue to review which parts of the Security Consideration section need to be made normative versus non-normative.
3. Andrew to update the "DNS privacy considerations" section title in the spec to better capture client security concerns.
4. Patrick to look into creating a Python script that can work with spec-up to count normative statements (sentences containing "must").
5. Stephen to add a reference to the JSON schema for the DID Web VH data model in the spec.
6. Stephen to move the problem details document to a stable location (suggested: did-webvh.info/security).
7. Stephen to create an issue for conducting test runs of large-scale (multi-thousand) updates to a DID.
8. Kim Hamilton Duffy to bring forward the 1.0 status of the spec to the TSC.

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Andrew Whitehead
- Patrick St. Louis
- Sam Curren
- Kaliya Young
- Dmitri Zagidulin
- Juan Caballero

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:
    1. did:webvh DID Method specifcation verison 1.0 has been announced.

3. Status updates on the implementations
    1. [TS] -- Small changes recently. Recently focused on BC Wallet running locally to allow for adding in support for did:webvh. All the work in Credo is done (still a PR).
    2. [Python] -- PR pending with compatibility fixes. Updates for 1.0 may be open today, and regen the test suite to be 1.0.
    3. [Rust] -- 
    3. [Server-Py] -- PR is complete for the next update/tweaks left. Has the latest features. Next up is the /whois endpoint to allow a controller to update the VP. In line with the ACA-Py Plugin.
    4. [did:webvh AnonCreds Method](https://identity.foundation/didwebvh/anoncreds-method/) -- done
    5. [did:webvh ACA-Py Plugin](https://github.com/openwallet-foundation/acapy-plugins/tree/main/webvh) -- [Demo: Using Traction to configure a did:webvh DID](https://www.loom.com/share/cf46394620534da6859d69b8e276f43d?sid=a0ffcb61-3ef5-4366-be1b-77f00eaefcaa).
    6. [Test Suite] -- Exists!
    7. [did:webvh Static](https://github.com/OpSecId/webvh-static) -- No change

4. To Do's from Last Meeting:

    1. DONE Stephen to create a PR for the 1.0 version of the did:webvh specification.
    2. DONE Stephen to update the [didwebvh.info](https://didwebvh.info) site with new information and FAQs.
    3. DONE Team to develop an MVP test suite architecture for did:webvh, including:
        1. Determining minimum acceptable tests
        2. Considering data model validator tests
        3. Exploring options for resolver tests and generator tests
        4. Team to review and potentially implement negative test cases for the test suite.
        5. Team to review the [Go implementation test suite](https://github.com/nuts-foundation/trustdidweb-go/tree/main/testdata) for reference.
    4. DONE Stephen to add a section on cryptographic agility to the specification for clarity.
    5. Team to consider creating a paper or analysis on did:webvh file growth and performance over time.
    6. Dmitri to define extra properties on OpenID entity statements for watchers in future work.
    7. DONE Stephen to create an issue for developing a JSON schema for the did:webvh data model.


5. THE TEST SUITE!!!
    1. Data Model Validator
        1. Test Suite input data set.
    2. Resolver Tests
        1. Negative data tests -- need a way to create negative tests, other than just by editing the data -- that would break the proofs.
            1. Does the resolver return an appropriate error message for various test cases.
            2. Ties the error case to a normative statement in the spec. Question: How to get an inventory of the normative process?
    4. Generator Tests -- architecture/data
        1. Published keypairs
        2. How to express the evolution of a DID.
        3. How to do interoperability testing.
        4. How to define negative tests.
        5. How to run locally.
        6. How to publish the results for different implementations.
    5. Witnesses
    6. Watchers

6. Plans for updates to the spec.
    1. Clarifications and simplifications.
    2. Cleaning up `[[spec]]` references and ref/defs.
    3. Security and Privacy sections. Anyone able to help?
    4. Getting "spec to a standard" advice and applying those changes.
    5. Finding an inventory of normative statements -- beyond search for `**MUST**`, etc.

7. Discussion about the "phone home" meme and `did:webvh`
    1. Discussed and there was agreement that some text should be put into the Security and Privacy section about the issue. 

## Meeting - 24 Apr 2025

Time: 9:00 Pacific / 17:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/izTN_SdNjbZHO8MaXpzYbHt4kYSXvox6-2IOF7Io00GwIQwqp8fNPY627Kw7iS5-.B0HVUrZbvUDBVgAs)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Stephen to create a PR for the 1.0 version of the did:webvh specification.
2. Stephen to update the [didwebvh.info](https://didwebvh.info) site with new information and FAQs.
3. Team to develop an MVP test suite architecture for did:webvh, including:
    1. Determining minimum acceptable tests
    2. Considering data model validator tests
    3. Exploring options for resolver tests and generator tests
    4. Team to review and potentially implement negative test cases for the test suite.
    5. Team to review the [Go implementation test suite](https://github.com/nuts-foundation/trustdidweb-go/tree/main/testdata) for reference.
4. Stephen to add a section on cryptographic agility to the specification for clarity.
5. Team to consider creating a paper or analysis on did:webvh file growth and performance over time.
6. Dmitri to define extra properties on OpenID entity statements for watchers in future work.
7. Stephen to create an issue for developing a JSON schema for the did:webvh data model.

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Sebastian Schmittner <sebastian.schmittner@eecc.de>
- Brian Richter
- Andrew Whitehead
- Patrick St. Louis
- Alexander Shenshin
- Dmitri Zagidulin

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:

3. Status updates on the implementations
    1. [TS](https://github.com/decentralized-identity/didwebvh-ts) -- Some progress on the Credo integration, adding AnonCreds. Having to write some custom code for DI proofs. Potential issue -- proof arrays vs. proof object in Credo. (Great) Idea from Dmitri -- create a JSON Schema for the did:webvh log entry -- added issue [203](https://github.com/decentralized-identity/didwebvh/issues/203).
    2. [Python](https://github.com/decentralized-identity/didwebvh-py) -- No changes
    3. [Rust](https://github.com/decentralized-identity/didwebvh-rs) -- No further updates.
    3. [Server Python](https://github.com/decentralized-identity/didwebvh-server-py) -- Evolving with ACA-Py plugin
    4. [did:webvh AnonCreds Method](https://identity.foundation/didwebvh/anoncreds-method/) -- done
    5. [did:webvh ACA-Py Plugin](https://github.com/openwallet-foundation/acapy-plugins/tree/main/webvh) -- Evolving with did:webvh Server Python. Now deployed into Traction, and now doing improvements for operations. Working on a witness queue. ACA-Py handling of keys. Collaborating with the Cheqd folks on common issues with key handling/usage.
    6. [did:webvh Static](https://github.com/OpSecId/webvh-static) -- will likely evolve into the test suite. Really needed!!

4. To Do's from Last Meeting:

    1. DONE Andrew to update the examples in the did-webvh-py library to v0.6, including removing the weight parameter and adding watcher URLs for testing validation.
    2. DONE - Stephen to update the specification with the latest examples (at least to v0.5, ideally to v0.6/v1.0).
    3. DONE - Stephen to clean up and clarify the specification language, particularly regarding null parameters and witness thresholds.
    4. TODO Stephen to update the didwebvh.info site with information about watchers.
    5. TODO Stephen to prepare the specification for declaration as version 1.0, allowing for final cleanups and clarifications.
    6. REALLY? Patrick to reach out to the Swiss government team to discuss their implementation and potential update to version 1.0.
    7. NEEDED! Team to consider developing a test suite for backwards compatibility, particularly for v0.3.

5. Comments and feedback from Brian's use of AI to generate critiques of did:webvh and a comparison of it vs. other web-based DID methods.  See the assessments [here](https://docs.google.com/document/d/108sasow3PzJoS1VnL8xx_0_1MhoB4rLtxS1t3WIuQXs/edit?usp=sharing).
    1. Performance concerns -- JSONL/caching, publishing benchmarks.
        1. Show an example -- e.g. version per week for 50 years -- how big is the file?  Processing time?
    3. GDPR concern -- really?
    4. Enhancing cryptographic agility.
        1. *"The specification lacks clear mechanisms for graceful cryptographic agility within the log itself. How would a transition to a new hash function or signature suite be managed mid-history?"* -- need to clarify.
    6. webs and webplus are "higher-assurance methods" -- really?
    7. Concerns about updates - atomicity/concurrency, file growth, non-database file. Given the context of DID updates, this is unlikely to be an issue. A DID Controller with concerns about that would need to take steps to control concurrent write access to the Log.
    9. Availability -- mentioned throughout. Mitigated somewhat by watchers.
        1. Leverage the work on Issuer Registries -- settled on using the OpenID Federation spec. Could add watchers to the Issuer data, and could build on the same trust mechanisms. See [this data about issuer registry research](https://blog.dcconsortium.org/selecting-the-openid-federation-specification-for-the-dcc-and-credential-engine-issuer-registry-f9079f620472).
    11. *"Witness Mechanism Immaturity: The optional witness feature lacks sufficient specification regarding discovery, operation, and security guarantees, limiting its current practical value"*
    12. [Suggestions for improvement](https://docs.google.com/document/d/108sasow3PzJoS1VnL8xx_0_1MhoB4rLtxS1t3WIuQXs/edit?tab=t.tbxtos8dia2#heading=h.n9nkj8zf4901)
    13. *"A thoughtful attempt"* -- well done!
    14. No built in revocation/expiry, lack of privacy features, no verifiable timestamp.

6. Discussion: the path to v1.0?
    1. [Current Issues](https://github.com/decentralized-identity/didwebvh/issues)
    2. Other issues:
        1. A number of issues have been [closed](https://github.com/decentralized-identity/didwebvh/issues?q=is%3Aissue%20state%3Aclosed).
        4. Issues to cover in the information site, not in the spec. [#170](https://github.com/decentralized-identity/didwebvh/issues/170).
    5. THE TEST SUITE!!!
        1. Data Model Validator
            1. Test Suite input data set.
        2. Resolver Tests
            1. Negative data tests -- need a way to create negative tests, other than just by editing the data -- that would break the proofs.
        4. Generator Tests -- architecture/data
            1. Published keypairs
            2. How to express the evolution of a DID.
            3. How to do interoperability testing.
            4. How to define negative tests.
            5. How to run locally.
            6. How to publish the results for different implementations.
        5. Witnesses
        6. Watchers

7.  Any substantive changes pre-1.0?
    1. No! 

8. Plans for updates to the spec.
    1. Clarifications and simplifications.
    2. Cleaning up `[[spec]]` references and ref/defs.
    3. Security and Privacy sections. Anyone able to help?
    4. Getting "spec to a standard" advice and applying those changes.

## Meeting - 10 Apr 2025

Time: 9:00 Pacific / 17:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/P3qDK6jMdasFvaUhUOM1LRUe-uREX8ThwwvDgZ0wJqqRUhz6nyJaW_mM3tHZscbP.5nbDCThyU6t_fVQz)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. DONE Andrew to update the examples in the did-webvh-py library to v0.6, including removing the weight parameter and adding watcher URLs for testing validation.
2. Stephen to update the specification with the latest examples (at least to v0.5, ideally to v0.6).
3. Stephen to clean up and clarify the specification language, particularly regarding null parameters and witness thresholds.
4. Stephen to update the did-webvh.info site with information about watchers.
5. Stephen to prepare the specification for declaration as version 1.0, allowing for final cleanups and clarifications.
6. Patrick to reach out to the Swiss government team to discuss their implementation and potential update to version 1.0.
7. Team to consider developing a test suite for backwards compatibility, particularly for v0.3.

### Attendees:<!-- omit in toc -->

- Stephen Curran

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:

3. Status updates on the implementations
    1. [TS](https://github.com/decentralized-identity/didwebvh-ts) -- Little progress
    2. [Python](https://github.com/decentralized-identity/didwebvh-py) -- Examples updated, implementation at v0.5.
    3. [Rust](https://github.com/decentralized-identity/didwebvh-rs) -- Created!
    3. [Server Python](https://github.com/decentralized-identity/didwebvh-server-py) -- Evovling with ACA-Py plugin
    4. [did:webvh AnonCreds Method](https://identity.foundation/didwebvh/anoncreds-method/) -- done
    5. [did:webvh ACA-Py Plugin](https://github.com/openwallet-foundation/acapy-plugins/tree/main/webvh) -- Evolving with Server Python.
    6. [did:webvh Static](https://github.com/OpSecId/webvh-static) -- 

4. To Do's from Last Meeting:

    1. DONE - Stephen to update the PR regarding the ID being valid if it matches any verified DID document version.
    2. DONE - Stephen to revise the error codes section in the spec to focus on invalid DID and not found errors, moving other potential error messages to the informational site.
    3. DONE - Stephen to update the metadata PR to reflect scenarios where log parsing is aborted early.
    4. DONE - Patrick to send Stephen an updated, properly formatted YAML file for the watcher interface.
    5. DONE - Patrick to update the get log endpoint in the YAML file to return the DID JSON-LD as the response.
    6. DONE Andrew to review and provide feedback on the pending PRs.
    7. DONE All team members to review the PRs and provide feedback to finalize version 1.0.
    8. Dimitri to present on DID Web VH at IIW and participate in DID-related discussions.

5. Discussion: the path to v1.0?
    1. [Current Issues](https://github.com/decentralized-identity/didwebvh/issues)
    2. Watchers discussion -- Complete -- merged. Only significant change was to remove the "witness-watcher" concept, and the API call to convey the pending entry to a witness to be signed.
    4. Other issues:
        1. A number of issues have been [closed](https://github.com/decentralized-identity/didwebvh/issues?q=is%3Aissue%20state%3Aclosed).
        2. [#189](https://github.com/decentralized-identity/didwebvh/issues/189) -- need to update the examples, so need examples to use.
        3. [#188](https://github.com/decentralized-identity/didwebvh/issues/188) -- clarifcation to be made to watchers section after current watchers PR is merged.
        4. Issues to cover in the information site, not in the spec. [#170](https://github.com/decentralized-identity/didwebvh/issues/170), [#160](https://github.com/decentralized-identity/didwebvh/issues/160).

6.  Do we have a definitive list of 1.0 changes?
    1.  Any changes needed? AFAIK, we qre done with 1.0. -- AGREED!
    2.  Next step is to declare the current version as 1.0 while still allowing for cleanups and clarifications.

7. Plans for updates to the spec.
    1. Clarifications and simplifications.
    2. Cleaning up `[[spec]]` references and ref/defs.
    3. Security and Privacy sections. Anyone able to help?
        4. Alexander Shenshin added some content this week. Broader review probably still needed.
    5. Getting "spec to a standard" advice and applying those changes.

## Meeting - 27 Mar 2025

Time: 9:00 Pacific / 17:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/tsaTCpXJK-t0Ox1D9iEmEgd43wUVoKWfuQ5ItbXvDLDEQV6xeVavuhQEpht67Z8.clyH2pTtPERhUigq)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. DONE - Stephen to update the PR regarding the ID being valid if it matches any verified DID document version.
2. DONE - Stephen to revise the error codes section in the spec to focus on invalid DID and not found errors, moving other potential error messages to the informational site.
3. DONE - Stephen to update the metadata PR to reflect scenarios where log parsing is aborted early.
4. DONE - Patrick to send Stephen an updated, properly formatted YAML file for the watcher interface.
5. DONE - Patrick to update the get log endpoint in the YAML file to return the DID JSON-LD as the response.
6. Andrew to review and provide feedback on the pending PRs.
7. All team members to review the PRs and provide feedback to finalize version 1.0.
8. Dimitri to present on DID Web VH at IIW and participate in DID-related discussions.

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Andrew Whitehead
- Patrick St. Louis
- Alexander Shenshin
- Sylvain Martel
- Sam Curren

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:

3. Status updates on the implementations
    1. [TS](https://github.com/decentralized-identity/didwebvh-ts) -- Credo PR moving forward. Asked about v0.3 compatibility.
    2. [Python](https://github.com/decentralized-identity/didwebvh-py) -- At v0.5 -- need the examples updated.
    3. [Server](https://github.com/decentralized-identity/didwebvh-server-py) -- tweaks.
    4. [did:webvh AnonCreds Method](https://identity.foundation/didwebvh/anoncreds-method/) -- done
    5. [did:webvh ACA-Py Plugin](https://github.com/openwallet-foundation/acapy-plugins/tree/main/webvh) -- tweaks. 
    6. [did:webvh Static](https://github.com/OpSecId/webvh-static) -- 

4. To Do's from Last Meeting:
    1. DONE - Stephen to update the watcher PR to make watchers more generic while keeping HTTP behavior defined
    2. DONE - Patrick to add an OpenAPI specification for the watcher endpoints
    3. DONE - Stephen to add a new endpoint for requesting deletion of data from watchers
    4. Stephen to update the spec to include service endpoints for watchers and resources
    5. Brian to create v0.5 examples for the specification
    6. Stephen to address clarifications requested by Patrick after merging the watcher section
    7. DONE - Stephen to close issue #131
    8. Stephen to draft a proposal for DNS-based witness integration for high assurance DIDs
    9. DONE - Implementers (Andrew, Brian, etc.) to provide additional resolver metadata based on the universal resolver output
    10. DONE - Stephen to add error codes to the specification

5. Discussion: the path to v1.0?
    1. [Current Issues](https://github.com/decentralized-identity/didwebvh/issues)
    2. Watchers discussion -- [the current PR](https://github.com/decentralized-identity/didwebvh/pull/181)
    4. Other issues:
        1. A number of issues have been [closed](https://github.com/decentralized-identity/didwebvh/issues?q=is%3Aissue%20state%3Aclosed).
        2. [#191](https://github.com/decentralized-identity/didwebvh/issues/191) New issue about resolver returning an error if the DID being resolved is not in the DIDDoc -- either the requested version or latest version. PR [#192](https://github.com/decentralized-identity/didwebvh/pull/192).  **Decision**:its OK if the location matches the `id` in *any* verified DIDDoc. PR Updated.
        3. [#189](https://github.com/decentralized-identity/didwebvh/issues/189) -- need to update the examples, so need examples to use.
        4. [#188](https://github.com/decentralized-identity/didwebvh/issues/188) -- clarifcation to be made to watchers section after current watchers PR is merged.
        5.  [#87](https://github.com/decentralized-identity/didwebvh/issues/78) -- High Assurance DIDs with DNS.
            1. Do we need to find a VM public key via DNS instead of via the DID? No -- too constraining -- one key.
            2. Do we want to add a DNS record (with details) that proves something about the DID? Maybe -- a proof from the latest update key?  a proof from a (special?) witness?
                1. Is such a proof sufficient to demonstrate a DID-to-DNS binding?
            4. Leave it that the "non-did:web" DID-to-DNS binding be used.
            5. **Decision**: For 1.0 and interoperability, we'll leave it at option 3 and as an information site document, but not in the spec. Also gives time for the other spec. to stabilize and for us to consider if a did:webvh specific approach is needed.
        7. Issues to cover in the information site, not in the spec. [#170](https://github.com/decentralized-identity/didwebvh/issues/170), [#160](https://github.com/decentralized-identity/didwebvh/issues/160)
        8.  [#43](https://github.com/decentralized-identity/didwebvh/issues/43) -- Additional resolver metadata -- needs details from implementers and then a PR. Minimal errors -- what to do if Log found but not the witness. PR updated.
        9.  [#23](https://github.com/decentralized-identity/didwebvh/issues/23) -- Error Codes -- do we need them in the spec? Needs details from implementers. PR Updated.

6.  Do we have a definitive list of 1.0 changes?
    1.  DID Resolution metadata when there are invalid entries at the end of the log. DONE
    2.  Review Andrew's issue for the metadata to make sure that all are covered. 

7. Plans for updates to the spec.
    1. Clarifications and simplifications.
    2. Cleaning up `[[spec]]` references and ref/defs.
    3. Security and Privacy sections. Anyone able to help?
    4. Getting "spec to a standard" advice and applying those changes.

## Meeting - 13 Mar 2025

Time: 9:00 Pacific / 17:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/KPkCkaUMME8zTBEizJei5_1fWoGx4UdQKjHdLTjmk12LyilGUYr-Hms_o6RES04p.9Mxku3lQ9QbTZJJo)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Stephen to update the watcher PR to make watchers more generic while keeping HTTP behavior defined
2. Patrick to add an OpenAPI specification for the watcher endpoints
3. Stephen to add a new endpoint for requesting deletion of data from watchers
4. Stephen to update the spec to include service endpoints for watchers and resources
5. Brian to create v0.5 examples for the specification
6. Stephen to address clarifications requested by Patrick after merging the watcher section
7. Stephen to close issue #131
8. Stephen to draft a proposal for DNS-based witness integration for high assurance DIDs
9. Implementers (Andrew, Brian, etc.) to provide additional resolver metadata based on the universal resolver output
10. Stephen to add error codes to the specification

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Andrew Whitehead
- Patrick St. Louis
- Alexander Shenshin
- Dmitri Zagidulin
- Phillip Long
- Jamie Hale

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:

3. Status updates on the implementations
    1. [TS](https://github.com/decentralized-identity/didwebvh-ts) -- PR to enable use in Credo. Working and almost ready to go.
    2. [Python](https://github.com/decentralized-identity/didwebvh-py) -- No updates.
    3. [Server](https://github.com/decentralized-identity/didwebvh-server-py) -- worked on in parallel with the ACA-Py plugin work. 
    4. [did:webvh AnonCreds Method](https://identity.foundation/didwebvh/anoncreds-method/) -- stable.
    5. [did:webvh ACA-Py Plugin](https://github.com/openwallet-foundation/acapy-plugins/tree/main/webvh) -- Updates and deactivates. Witness and pre-rotation in ACA-Py. Patrick covering how witnesses will work in ACA-Py.
    6. [did:webvh Static](https://github.com/OpSecId/webvh-static) -- 

4. To Do's from Last Meeting:
    1. [DONE PR](https://github.com/decentralized-identity/didwebvh/pull/181) Stephen to create a PR addressing watchers in the specification.
    2. [DONE, Merged](https://github.com/decentralized-identity/didwebvh/pull/182) Stephen to update the PR on international domains based on Ankar's feedback.
    3. [DONE, Merged](https://github.com/decentralized-identity/didwebvh/pull/185) Stephen to add a PR for the "right to be forgotten" deactivation method.
    4. [DONE, Merged](https://github.com/decentralized-identity/didwebvh/pull/186) Stephen to update the resolution issues based on Andrew's resolution algorithm document.
    5. DONE Stephen to close the "did link resources" issue.
    6. DONE -- Discussions continuing Stephen to meet with Tim Bauma and Jesse Carter about high assurance DIDs and did:webvh.
    7. Andrew and Brian to provide input on DID metadata for resolver metadata.
    8. Stephen to formalize DID metadata in the specification.
    9. Patrick, Andrew, and Brian to provide input on error codes and problem details for did:webvh resolution.
    10. Stephen to update the security and privacy sections of the specification.
    11. DONE - [Recording](https://zoom.us/rec/share/lPdHF5O2nQneyYQ_dZaNyo2qs303a-IW6UE6JMuwf6BgBcEmLvtNyrK6GwNHz3ud.oFIoM5T3MzkRbsYq) Stephen to present did:webvh at the Open Wallet Foundation Wallet Interop SIG meeting on Monday.

5. Discussion: the path to v1.0?
    1. [Current Issues](https://github.com/decentralized-identity/didwebvh/issues)
    2. Watchers discussion -- [the current PR](https://github.com/decentralized-identity/didwebvh/pull/181) -- sufficient/complete? Overview:
        1. Adds an optional "`watcherURL`" to `witness`.
        2. Adds a `watchers` parameter that is a list of `watcherURL`s
        3. Defines that a `watcher` is a web server that responds to a set of GET and POST HTTP requests:
            1. GET DID Log, Witness Proofs, Resource (by path)
            2. POSTs are webhooks -- "DID Updated", "Resources Updated" (no content -- just a notification)
                1. Do we need to define retries or just mention that implementations should have an appropriate retry mechanism.
            3. For witness-watchers: "DID Entry" (includes the entry and a callback for the proof)
        4. Conversation -- add a "delete" request for the SCID and leave it to governance for what to do.
        5. Service entry for list of watchers, list of resources -- not needed -- automatically included in the DID Resolution metadata.
        6. Change the URLs to not be constrained to HTTP, but if they are here is how to use them.
    4. Other issues:
        1. A number of issues have been [closed](https://github.com/decentralized-identity/didwebvh/issues?q=is%3Aissue%20state%3Aclosed).
        2. [#189](https://github.com/decentralized-identity/didwebvh/issues/189) -- need to update the examples, so need examples to use.
        3. [#188](https://github.com/decentralized-identity/didwebvh/issues/188) -- clarifcation to be made to watchers section after current watchers PR is merged.
        4. [#131](https://github.com/decentralized-identity/didwebvh/issues/131) -- Resolution issues -- PR added.
        5.  [#87](https://github.com/decentralized-identity/didwebvh/issues/78) -- High Assurance DIDs with DNS -- Meeting with Jesse and Tim.  Define a witness based scheme, where the witness evidence is in the DNS record.
        6.  [#43](https://github.com/decentralized-identity/didwebvh/issues/43) -- Additional resolver metadata -- needs details from implementers and then a PR.
        7.  [#23](https://github.com/decentralized-identity/didwebvh/issues/23) -- Error Codes -- do we need them in the spec? Needs details from implementers.

6. Plans for updates to the spec.
    1. A ChatGPT pass, likely using the using the "Academic Assistant Pro" GPT. That should include DRYing the spec to remove duplication.
    2. Cleaning up `[[spec]]` references -- Brian has enabled us to add our own spec references.
    3. Security and Privacy sections. Anyone able to help?
    4. Getting "spec to a standard" advice and applying those changes.

## Meeting - 27 Feb 2025

Time: 9:00 Pacific / 18:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/play/wmqDv_pg0Tz6GB0N3Lbj02RuTdBdehxH6YuTF9sTTZnPDrTJg-Lf9MbWlrU5HiG9Vo1MSRbasm85Vds9.MnIgiMI3JxO3QB1q?accessLevel=meeting&canPlayFromShare=true&from=share_recording_detail&continueMode=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Fus02web.zoom.us%2Frec%2Fshare%2Fgj4iz_fH24RgvqYUHZ9O70Fj-2zj37iJvJxRX1cQb0H4peElrz6tqtwjdEEXJREh.W51LDel4mloHf1Y5)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Stephen to create a PR addressing watchers in the specification.
2. Stephen to update the PR on international domains based on Ankar's feedback.
3. Stephen to add a PR for the "right to be forgotten" deactivation method.
4. Stephen to update the resolution issues based on Andrew's resolution algorithm document.
5. Stephen to close the "did link resources" issue.
6. Stephen to meet with Tim Bauma and Jesse Carter about high assurance DIDs and did:webvh.
7. Andrew and Brian to provide input on DID metadata for resolver metadata.
8. Stephen to formalize DID metadata in the specification.
9. Patrick, Andrew, and Brian to provide input on error codes and problem details for did:webvh resolution.
10. Stephen to update the security and privacy sections of the specification.
11. Stephen to present did:webvh at the Open Wallet Foundation Wallet Interop SIG meeting on Monday.

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Andrew Whitehead
- Patrick St. Louis
- Alexander Shenshin
- Sylvain Martel
- Dmitri Zagidulin
- John Jordan
- Phillip Long
- Jamie Hale
- Sam Curren

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:

3. Status updates on the implementations
    1. TS -- Stable at 0.5, and working on getting it into Credo and Bifold
    2. PY -- Stable at v0.5.
    3. Server -- Load Testing, Attested Resources vewier.
    4. did:webvh AnonCreds Method -- [Spec. Published](https://identity.foundation/didwebvh/anoncreds-method/). PR to be created to add it to the [AnonCreds Methods Registry](https://hyperledger.github.io/anoncreds-methods-registry/)
    5. [did:webvh Static](https://github.com/OpSecId/webvh-static)

4. To Do's from Last Meeting:
    1. DONE - Stephen to update the specification to remove weights for witnesses.
    2. DONE - [PR #178](https://github.com/decentralized-identity/didwebvh/pull/178) Stephen to ensure the specification includes text about trusting a did:web:vh DID and the need for additional signals beyond verifiability.
    3. DONE - Stephen to propose a PR mentioning watchers but keeping them out of scope in the specification.
    4. Sylvain(MCN) to push the latest version of the Rust implementation to the repository.
    5. DONE - Patrick to review and merge the PR for the did:web:vh and AnonCreds method specification.
    6. DONE (right?) All implementers to review open issues and consider what needs to be addressed for version 1.0.
    7. Andrew to review and provide feedback on the verification algorithm document in the did:web:vh information site.
    8. DONE - Stephen to confirm with Kim the Work Item Zoom link.

5. Discussion: the path to v1.0?
    1. [Current Issues](https://github.com/decentralized-identity/didwebvh/issues)
    2. Proposal to add a "timelock" item associated with portability into the parameters, much like the DNS timelock capability. See [Issue #173](https://github.com/decentralized-identity/didwebvh/issues/173) -- Decision was to add a comment to the spec about DNS and timelock, but to not add a feature.
    3. Watchers -- some thoughts were generated at the meeting and in issues raised. Specific issues with defined actions may follow. Added to: [#170:comment](https://github.com/decentralized-identity/didwebvh/issues/170#issuecomment-2652152103) -- Decision was made to add the concept of watchers and a PR will be added.
    4. Other issues:
        1. [#171](https://github.com/decentralized-identity/didwebvh/issues/170) -- International Domains - addressed by [PR #179](https://github.com/decentralized-identity/didwebvh/pull/182) -- pending resolution.
        2. [#161](https://github.com/decentralized-identity/didwebvh/issues/161) -- Right to be Forgotten -- add a reference to deleting the DID in the deactivate section.
        3. [#131](https://github.com/decentralized-identity/didwebvh/issues/131) -- Resolution issues -- PR to be added.
        4.  [#107](https://github.com/decentralized-identity/didwebvh/issues/107) -- DID Linked Resources -- discussed, and to be closed.
        5.  [#87](https://github.com/decentralized-identity/didwebvh/issues/78) -- High Assurance DIDs with DNS -- Meeting with Jesse and Tim.
        6.  [#73](https://github.com/decentralized-identity/didwebvh/issues/73) -- "Trusting" a `did:webvh` DID -- resolved. Close.
        7.  [#43](https://github.com/decentralized-identity/didwebvh/issues/43) -- Additional resolver metadata -- needs details from implementers and then a PR.
        8.  [#23](https://github.com/decentralized-identity/didwebvh/issues/23) -- Error Codes -- do we need them in the spec? Needs details from implementers.

6. Plans for updates to the spec.
    1. A ChatGPT pass, likely using the using the "Academic Assistant Pro" GPT. That should include DRYing the spec to remove duplication.
    2. Cleaning up `[[spec]]` references -- Brian has enabled us to add our own spec references.
    3. Security and Privacy sections. Anyone able to help?
    4. Getting "spec to a standard" advice and applying those changes.

7. [Spec. PRs and Issues](https://github.com/decentralized-identity/trustdidweb/issues)

## Meeting - 13 Feb 2025

Time: 9:00 Pacific / 18:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/ot8NDM7E18U-YpqtqiiALz2R03pSjNNcpAphh1Lk9m4gTtA65i_rHZSBbyPXIBWp.8J5mlJKWAVpqCaCv)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Stephen to update the specification to remove weights for witnesses.
2. Stephen to ensure the specification includes text about trusting a did:web:vh DID and the need for additional signals beyond verifiability.
3. Stephen to propose a PR mentioning watchers but keeping them out of scope in the specification.
4. Sylvain(MCN) to push the latest version of the Rust implementation to the repository.
5. Patrick to review and merge the PR for the did:web:vh and AnonCreds method specification.
6. All implementers to review open issues and consider what needs to be addressed for version 1.0.
7. Andrew to review and provide feedback on the verification algorithm document in the did:web:vh information site.
8. Stephen to confirm with Kim the Work Item Zoom link.


### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Andrew Whitehead
- Patrick St. Louis
- Alexander Shenshin
- Sylvain Martel
- Dmitri Zagidulin
- Michal Pietrus

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:

3. Status updates on the implementations
    1. TS -- Stable at 0.5, universal resolver updated, and working on getting it into Credo and Bifold
    2. PY -- Stable at v0.5.
    3. Server -- Lots of updates, AnonCreds exchange -- create/update attested resources.
    4. did:webvh AnonCreds Method -- [Spec. PR](https://github.com/decentralized-identity/didwebvh/pull/174) created, pending merging. Will follow up with a PR to add it to the [AnonCreds Methods Registry](https://hyperledger.github.io/anoncreds-methods-registry/)
    5. [did:webvh Static](https://github.com/OpSecId/webvh-static) -- 

4. To Do's from Last Meeting:
    1. DONE -- Andrew to detail the verification algorithm, including error handling -- [document](https://hackmd.io/@andrewwhitehead/HynYtHt_Jg)
    2. DONE -- Stephen to add issue on watchers to the specification or implementers guide. Added to: [#170:comment](https://github.com/decentralized-identity/didwebvh/issues/170#issuecomment-2652152103)
    3. DONE (right?) -- All implementers to review and provide feedback on any necessary changes or additions to the spec based on their implementation experiences.
    4. DONE -- Stephen to go through all open issues and post messages about them, closing them where possible.
    5. DONE (right?) -- All team members to consider what changes are necessary before moving to version 1.0.

5. Discussion: the path to v1.0?
    1. [Current Issues](https://github.com/decentralized-identity/didwebvh/issues)
    2. Potential change - @andrewwhitehead wants to reevaluate witnesses and weights. See also issue [170](https://github.com/decentralized-identity/didwebvh/issues/170) suggesting to remove weights.
        1. Threshold -- aim for the BFT problem.
            1. KERI -- weights are equal, so there is no incentive to attack specific witnesses.
            2. From the DID Log, we use did:keys, so there is no way to "attack" the witnesses. Stephen -- not sure this is right... :-)
            3. Andrew -- difficult to reason about it without including watchers and so on. Are witnesses needed to witness -- complicates the governance?
            4. Remove the weights -- yes or no? Yes remove them.  Can be added at the business layer if important.
        3. Multisig -- a different problem.  Each keeper gets a different weight, and its bound to the protocol.  What is it?  More than one participate that is a co-owner of an identifier.  Can have any, number of keys.
    4. Portability -- is it solid enough? @PatStLouis is considering this and may raise an issue. See issue [173-- make portability `true` by default](https://github.com/decentralized-identity/didwebvh/issues/173).
        1. Downside of did:web was the lack of portability.
        2. A major mitigation to a number of web scenarios.  Why disable by default?
        3. Flag is there and it can be set to false if wanted.
        4. Half baked?  How do you find a DID after it has moved? 
        5. Default to `true` -- yes or no? No - leave it as is.
    6. Watchers -- some thoughts were generated at the meeting and in issues raised. Specific issues with defined actions may follow. Added to: [#170:comment](https://github.com/decentralized-identity/didwebvh/issues/170#issuecomment-2652152103)
    7. Other issues:
        1. [#171](https://github.com/decentralized-identity/didwebvh/issues/170) -- Unicode
        2. [#161](https://github.com/decentralized-identity/didwebvh/issues/161) -- Right to be Forgotten
        3. [#131](https://github.com/decentralized-identity/didwebvh/issues/131) -- Resolution issues.
        4.  [#107](https://github.com/decentralized-identity/didwebvh/issues/107) -- DID Linked Resources.
        5.  [#87](https://github.com/decentralized-identity/didwebvh/issues/78) -- High Assurance DIDs with DNS.
        6.  [#73](https://github.com/decentralized-identity/didwebvh/issues/73) -- "Trusting" a `did:webvh` DID.
        7.  [#43](https://github.com/decentralized-identity/didwebvh/issues/43) -- Additional resolver metadata.
        8.  [#23](https://github.com/decentralized-identity/didwebvh/issues/23) -- Error Codes -- do we need them in the spec?

6. Plans for updates to the spec.
    1. A ChatGPT pass, likely using the using the "Academic Assistant Pro" GPT. That should include DRYing the spec to remove duplication.
    2. Cleaning up `[[spec]]` references -- Brian has enabled us to add our own spec references.
    3. Security and Privacy sections. Anyone able to help?
    4. Getting "spec to a standard" advice and applying those changes.

7. [Spec. PRs and Issues](https://github.com/decentralized-identity/trustdidweb/issues)

## Meeting - 30 Jan 2025

Time: 9:00 Pacific / 18:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/8qcxIyRud7lXp3u0w91W5SMA93jGalWy4SBeLOHYLim3Y6BeWe_IDayV9ZhSEUN3.9xHC7NSWXEWoHyWx)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Andrew to detail the verification algorithm, including error handling.
2. Stephen to add issue on watchers to the specification or implementers guide.
3. All implementers to review and provide feedback on any necessary changes or additions to the spec based on their implementation experiences.
4. Stephen to go through all open issues and post messages about them, closing them where possible.
5. All team members to consider what changes are necessary before moving to version 1.0.

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Andrew Whitehead
- Patrick St. Louis
- Emiliano Sune
- Alexander Shenshin
- Jamie Hale
- Phillip Long
- Sylvain Martel
- Dmitri Zagidulin
- Markus Sabadello
- Ben Taylor

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and requests for additional Agenda Topics

2. Announcements:

3. Status updates on the implementations
    1. TS -- At v0.5 and deployed to npm as didwebvh-ts. Next up testing the NPM package.
    2. PY -- At v0.5 on PyPi. Compatible with the TS version based on some minimal testing. Plan a tweak to the witness verification approach. Planning some interop tests that can be run across all implementations.  A few test cases are needed - especially around witness cases.
    3. Server -- Gave a demo of AnonCreds objects published and resolved to implement a full credential flow. Developed with the ACA-Py plugin. Main focus security and loading/resolving. Working on revocation flow.
    4. did:webvh AnonCreds Method -- to be discussed.
    5. [did:webvh Static](https://github.com/OpSecId/webvh-static) -- no change. Next might be to add creating AnonCreds resources to show "real" examples.

4. To Do's from Last Meeting:
    1. DONE - Daniel/Stephen to collaborate on a best practices document for key references in DID documents, focusing on keeping valid keys in the current DID document now published on the [https://didwebvh.info](https://didwebvh.info/latest/implementers-guide/did-valid-keys/) site.
    2. DONE - Stephen has added the agenda link in the meeting information [here](https://didwebvh.info/latest/agenda/) on the [https://didwebvh.info](https://didwebvh.info) site.
    3. DONE - Brian to complete implementation of files resolution and witness functionality for v0.5 spec.
    4. DONE - Andrew to finish updates to the resolver for collecting witness rules and verifying proofs for v0.5 spec.
    5. PROGRESS - Patrick to focus on implementing uploading of an AnonCreds object on the web server. Internal demo given of a full issue-present-verify flow using credentials rooted in a did:webvh DID. Next up: including revocation.
    6. PROGRESS - Jamie to work on DIDComm protocol for requesting witness signatures. In ACA-Py plugin.
    7. PROGRESS - Patrick to implement witness and DID rotation features for the server.
    9. RESOLVED -- WON'T DO - did:webvh team to consider implementing the witness proofs as VCs in the`/whois` VP in a future version (v0.6 or later). See notes below on resolution.
    10. DONE - did:webvh team to further discuss and decide on the implementation of revocation registry entries.

5. Discussion: the path to v1.0?
    1. [Current Issues](https://github.com/decentralized-identity/didwebvh/issues)
    2. Resolved [Issue 165 - Using /whois for witness proofs](https://github.com/decentralized-identity/didwebvh/issues/165) and agreed we wouldn't use `/whois` for witness proofs. It might be used by a witness to attest to the DID itself (not in the spec -- perhaps implementer's guide), but not for proofs on specific versions of the DID.
    3. Potential change - @andrewwhitehead wants to reevaluate witnesses and weights.
    4. Portability -- is it solid enough? @PatStLouis is considering this and may raise an issue.
    5. Watchers -- some thoughts were generated at the meeting and in issues raised. Specific issues with defined actions may follow.
    6. Clarification -- the step-by-step details of the verification, based on the experience of implementations, at a  general level. Likely for the implementers guide.

6. Revisiting DID Key references for rotated keys
    1. [Best practices document](https://didwebvh.info/latest/implementers-guide/did-valid-keys/) from Daniel Bluhm and Char Howland added to the [info site](https://didwebvh.info).

7. Progress on DID Resources using AnonCreds objects -- document: 
    1. Define the `attestedResource` object -- JSON, with an identified resource, a proof, with the resource (file) name the multihash of the resource `base58(multihash(JCS(resource)))`, with the file located using the (implicit or explicit) `#files` service -- e.g., by default relative to the root of the DID.
    2. Schema, CredDef are `attestedResources`. Their IDs are DID URLs calculated during generation and shared to other parties (e.g. `schemaID` is in the CredDef, `credDefId` is in the Credential).
        1. Does/can the resource name include the components of the object -- e.g. `schemaName`, `schemaVersion`, `tag`? Presumably, the controller can make that part of the DID URLs. Should we consider formalizing it?  E.g. `<did>/anoncreds/schema/ver/<schemaname>/<schemaver>/<attestedresouce>.json`
        2. Is there a way to get a list of all attestedResources, including their identifying metadata? What if the metadata is not part of the DID URLs?
        3. Should did:webvh formalize that a folder can be resolved with a list of contents returned (e.g. `<did>/anoncreds/schema/ver/` returns a list of `<schemaNames>`).
    3. RevRegDef is also an `attestedResource`, with its ID generated during creation, and shared from the Issuer to the Holder in the issued Credential.
    4. The RevRegDef contains a current list (index) of its RevRegEntry `attestedResource`s. When a new RevRegEntry is created and published, the index is updated with the `timestamp` and `attestedResource` identifier, and the RevRegDef resource is republished.
        1. The index is _outside_ of the resource that is attested. As such, the updates **do not** change the `attestedResource` name of the RevReg. The proof on the attested resource **DOES** get updated to include the index.
    5. A client needing a RevRegEntry for an arbitrary or specific timestamp, must:
        1. Retrieve the known associated `revRegDefId` `attestedResource`.
            1. The Holder knows the `id` because it is in the Credential from the Issuer.
            2. The Verifier knows the `id` because it is in the Presentation from the Holder.
        2. Scan the timestamps in the list (index) for the one of interest:
            1. Holder gets the one active at a given timestamp (or from/to period) from the verifier.
            2. Verifier gets the associated with a specific timestamp in the Presentation from the Holder.
        3. Use the `attestedResource` ID (DID URL) to get the RevRegEntry of interest.
            1. The RevRegEntry contains the full state of the RevReg at the given `timestamp`.
            2. The `did:webvh` AnonCreds method will not use deltas (as does Indy), but will use full state, as does Cheqd.
    6. Evolving design document: [AnonCreds in did:webvh](https://hackmd.io/@SpWXgFH9Rbyoa0JW3agDcg/HJU-4azPJl)

8. Plans for updates to the spec.
    1. A ChatGPT pass, likely using the using the "Academic Assistant Pro" GPT. That should include DRYing the spec to remove duplication.
    2. Cleaning up `[[spec]]` references -- Brian has enabled us to add our own spec references.
    3. Security and Privacy sections. Anyone able to help?
    4. Getting "spec to a standard" advice and applying those changes.

9. [Spec. PRs and Issues](https://github.com/decentralized-identity/trustdidweb/issues)

## Meeting - 16 Jan 2025

Time: 9:00 Pacific / 18:00 Central Europe

Recording: [Zoom Recording and Chat Transcript](https://us02web.zoom.us/rec/share/7ruZUqMbHh3hzK2tVGnirAqNTLYX6pUbj4bB7QYAqkITDVOs-VeNFMHpNOTt4Iw.GQr_fjDMJ-f1ek2h)

### To Do's from this Meeting (as generated by Zoom):<!-- omit in toc -->

1. Daniel/Stephen to collaborate on a best practices document for key references in DID documents, focusing on keeping valid keys in the current DID document for publication on the [https://didwebvh.info](https://didwebvh.info) site.
2. Stephen to add the agenda link in the meeting information on the [https://didwebvh.info](https://didwebvh.info) site.
3. Brian to complete implementation of files resolution and witness functionality for v0.5 spec.
4. Andrew to finish updates to the resolver for collecting witness rules and verifying proofs for v0.5 spec.
5. Patrick to focus on implementing uploading of an AnonCreds object on the web server.
6. Jamie to work on DIDComm protocol for requesting witness signatures.
7. Patrick to implement witness and DID rotation features for the server.
9. did:webvh team to consider implementing the witness proofs as VCs in the`/whois` VP in a future version (v0.6 or later).
10. did:webvh team to further discuss and decide on the implementation of revocation registry entries.

### Attendees:<!-- omit in toc -->

- Stephen Curran
- Brian Richter
- Andrew Whitehead
- Patrick St. Louis
- Kaliya Young
- Emiliano Sune
- Alexander Shenshin
- Char Howland
- Daniel Bluhm
- Jamie Hale
- Phillip Long
- Sylvain Martel
- Dmitri Zagidulin
- Markus Sabadello

### Agenda and Notes<!-- omit in toc -->

1. Welcome and Adminstrivia
    1. Recording on?
    2. Please make sure you: [join DIF], [sign the WG Charter], and follow the [DIF Code of Conduct]. Questions? Please contact [operations@identity.foundation].
    3. [did:webvh Specification license] -- W3C Mode
    4. Introductions and additional Agenda Topics

2. Announcements:
    1. did:webhv v0.5 is now official. No changes yet to the editor's draft.
    2. Implementations renamed to `didwebvh` -- [TS](https://github.com/decentralized-identity/didwebvh-ts), [Python](https://github.com/decentralized-identity/didwebvh-py) and [server](https://github.com/decentralized-identity/didwebvh-server-py). Renaming complete!
    3. did:webvh has been merged into the [DID Extensions](https://github.com/w3c/did-extensions) repo and is now a "listed" DID Method.
    4. Presentation on did:webplus was made at this week's DIF ID Working Group meeting ([Recording](https://us02web.zoom.us/rec/play/KaANk-0AZ5igVvP4aOEyiPcOkqRQfnTMuJ9TTkATQ7_CL9cbfhTDxkOBP-DRzLZxNgwT-5rhCTqaHD-c.E7BFSM6Oixjv1WJa?canPlayFromShare=true&from=share_recording_detail&continueMode=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Fus02web.zoom.us%2Frec%2Fshare%2Fv11q2vzVD5w4td993gMAtTcZqc_-kw5pyDH-D40p948FllhOXVG1_FREDuQJbIqN.hJy4KKg3ogK3E2LS)). Interesting presentation, focusing on a Web-based DID Method that emphasises tools (a "DID Gateway") to enable the long term resolution of DIDs -- years to decades -- regardless of the status of the original DID.

3. Status updates on the implementations
    1. TS -- files resolution work near complete, about 50% complete of the witnesses, will do the `/whois`
    2. PY -- sync'd PR to renaming, generating a witness file, updates being made to the witness rules and proofs -- required some refactoring. Some updates to the interface to enable unit tests.
    3. Server -- opened some issues on the features -- especially resources. Current focus is on AnonCreds objects. Working on the witness -- enabling the process for witness proof request/response.
    4. A new project/repos was added to create static did:webvh DIDs and AnonCreds objects to enable testing. A series of small Python scripts -- useful for GHA for testing. [https://github.com/OpSecId/webvh-static](https://github.com/OpSecId/webvh-static).

4. To Do's from Last Meeting:
    1. **DONE** All participants to review the latest PR for v0.5 of the did:webvh specification.
    2. **DONE** [Commit](https://github.com/decentralized-identity/didwebvh/pull/159/commits/e13e35b958ea14a9a79ae2616d905871d6aca5c3) Stephen to add a commit to the PR clarifying that null and an empty list both mean no pre-rotation for the next_key_hashes parameter.
    3. **DONE** Stephen to finalize and declare v0.5 of the specification after the PR is merged.
    4. Dmitri to find and share external specs related to key security events.
    5. **DONE** [Issue](https://github.com/decentralized-identity/didwebvh/issues/161) Brian to create an issue about addressing right to deletion requests in the specification.
    6. **DONE?** Andrew to continue work on the resolver, including handling witness rules and improving caching behavior.
    7. **DONE?** All participants to join the did:webvh channel on the DIF Slack instance for future discussions.

5. Revisiting DID Key references for rotated keys
    1. Best practices: Retaining "valid" keys in the current DIDDoc vs. using DID version key references. What is the right way in the face of the need to revoke keys?
    2. There are techniques to declare a key "revoked".

6. Slack Topic: Using `/whois` as the holder of witness proofs
    1. Idea: Instead of current (v0.5) design of a file `witness.json` "beside" the `did.jsonl` containing proofs from the witnesses, we instead have the witnesses produce VCs that assert the version of the DID is valid, and the DID Controller puts the VCs into the `/whois` file. The same rules would apply about what VCs are needed -- at least the latest VC from a witness from a published DID entry. The `/whois` file containing the latest witness VCs **MUST** be published before publishing a new witnessed DID log entry.

6. Progress on DID Resources using AnonCreds objects as examples
    1. Goal -- an immutable object (via hash in the resource identifier), and a proof about the resource.
    2. Definition of an "attested resource" that can be the generically used as the most basic secured resource -- hash protected in the URL and signed by the DID Controller.
    3. The RevRegEntry use case -- periodically published objects that must be retained.
        1. Multiple access use cases -- "get latest", "get by ID", "get list by timestamp and then by ID"
    4. Evolving design document: [AnonCreds in did:webvh](https://hackmd.io/@SpWXgFH9Rbyoa0JW3agDcg/HJU-4azPJl)
    5. RevRegEntries
        1. Have a list that is a JSONL file that has the list of identifiers and each entry is a separate file.
            1. Related -- a did:webvh server **MAY** have a list of all DID Linked Resources. Must contain all of the files -- regardless of type. Perhaps we use that to get the list of RevRegEntries.
        2. Have a JSONL file that has all the entries. Get all the entries by retrieving the file. Can't be immutable in the identifier because the resource hash will change with each update to the log.

7. Plans for updates to the spec.
    1. A ChatGPT pass, likely using the using the "Academic Assistant Pro" GPT. That should include DRYing the spec to remove duplication.
    2. Cleaning up `[[spec]]` references -- Brian has enabled us to add our own spec references.
    3. Security and Privacy sections. Anyone able to help?
    4. Getting "spec to a standard" advice and applying those changes.

8.CEL proposal [announced by Manu](https://lists.w3.org/Archives/Public/public-credentials/2024Dec/0051.html).  I don't think we can use the spec directly, and it would complicate the explanations about what is in that spec, and what is in the did:webvh spec. Thoughts? There are some really useful ideas -- such as the ability to break logs into multiple files -- although we would want them in reverse from that they have defined.

9. [Spec. PRs and Issues](https://github.com/decentralized-identity/trustdidweb/issues)

## Prior Meetings

- 2024 meetings can be found in the [Agenda 2024] file.

[Agenda 2024]: https://github.com/decentralized-identity/didwebvh/tree/main/agenda-2024.md
