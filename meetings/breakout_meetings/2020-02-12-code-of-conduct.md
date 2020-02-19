# Code of Conduct Working Group

## Purpose

To provide guidance, recommendations and proposals to the OpenJS Foundation Cross Project Council on Code of Conduct related policies.

## Scope of Work
* Get agreement on minimum viable CoC process and get it landed
  *  How close is the current proposal to that and what needs to be adjusted to reach the MVP?

* What extensions would make sense, and do the projects agree to that. Discuss suggestions that have been made:
  * Foundation wide bans
  * Sharing information across projects
  * Escalation processes (particularly up to Foundation)
  * Processes to adjudicate disagreements between CPC and projects in moderation recommendations/steps

## Actions/Agenda

* Decision: Is this a valid MVP? https://github.com/openjs-foundation/cross-project-council/pull/379
    * If NO, what specific elements need to be addressed.
    * If YES, what if any steps are needed to begin implementation and enforcement.

* Question: Does this group need to meet again?

## Participants
  * Michael Dawson
  * Jordan Harband
  * Jory Burson
  * Joe Sepi
  * Anton Molleda
  * Eemeli Aro
  * Myles Borins
  * Matteo Collina
  * Ben Michel
  * Tobie Langel (stepping in for someone on the AMP CoC WG)
  * James Snell ?(based on those suggesting extensions to MVP or showing concerns in collab summit)

## Notes (2020-02-12 Call)

Present: Myles, Jory, Joe, Robin, Anton, Ben, Brian, Naina, Eemeli, Michael, Tobie

### Minutes
Jory: Does [pull request 379](https://github.com/openjs-foundation/cross-project-council/pull/379/files) go far enough for our first draft? If the answer is no, where do we go from here? If yes, what do we need to set up to make this an official policy?

Michael: Overall, there's 2 pieces: one describes the outside view, and the 2nd describes how we handle the reports internally. The main addition is we want to use one code of conduct across all the projects. The other is that it adds an escalation process. The escalation process provides a place that projects can report to if they're being treated unfairly. For the body handling these kinds of things we'll want broad representation across projects and disciplines. The CPC can make a subset that can be adopted by projects. They're required to use the CoC and have to follow the path of escalation as documented.

Jory: Naina gave helpful feedback early on this. I'm curious to hear from Naina about how she's thinking about this now regarding recent changes.

Naina: The proposal on our end seems good. My only concern is that in our work to change the contributor covenant – that's been moving pretty slowly. Is it usually this slow? Our ability to influence adoption is going to be limited if our progress is going to be slow withing the WG.

Michael: Is the concern that it's just taking a long time?

Naina: Yeah, it hasn't moved since January 10th.

Michael: I'd be more concerned if it wasn't open for discussion.

Naina: Not concerned with how we're doing it, that's going to be fine.

Jory: If upstream changes are going to take too long, we'll want to have a developed plan b.

>Possible Concern: The length of time that it takes to have PRs upstreamed into the Contributor Covenant
>* idea: float patch strategy

Joe: The last comments are in Nov. Yeah, been a while.

Michael: I'd start with how this was presented in the first place. If we think that things are going to take too long, we should get together with the group that started it. We should start to understand if it's going to be a one off.

Myles: The switch from 1.0 to 2.0 had unexpected changes. Secondly, there's no clear ownership here. There's no group that acutally owns the CoC or the group doing this and folks don't feel empowered to do this yet. Once that happens, this situation will probably be mitigated.

>Possible Need: Empowered CPC sub-team to monitor changes & speed

Michael: Agree. Once we get it bootstrapped, it should fall into place

Myles: We float changes on dependencies all the time on Node.js core. We should be able to update patches and float the patches and not be blocked upstream by this.

Brian: Looking at the merits of waiting for something to be upstream vs. something that's available now – there's a tremendous amount of value in place as soon as possible. All these things can be reviewed and revised over time.

Michael: For example, on V8 we send it upstream – but usually we float it. We should always be open to do this depending on how things are going.

Jory: Are there any thoughts from the Webhint or Electron side?

Anton: The CoC from the Electron team is very hard. It gives a lot of power to discipline if needed. My concern is that if we don't regularly update the CoC we request projects to adopt, they might be waiting for changes upstream.

>Possible Concern: Communicating patches/changes out to the projects. How does the group make sure these are updated (GH issue, etc)

Michael: Shouldn't be that common of a situation.

Anton: Let's see how fast upstream gets updated, and not overthink it.

Jory: So what I'm hearing is that there's a need to ensure there's a need to check in on a suggested change before it's accepted and distributed across the ecosystem.

Anton: There may be a parity problem if OpenJS updates thier CoC and each project has to change theirs accordingly.

Myles: OpenJS projects should be pointing at the OpenJS CoC vs. keeping a local copy.

Brian: Projects should only have their own if they plan on maintaining a more stringent CoC.

Myles: I'm not sure that's the way we're going to set this up. There needs to be a central authority for generating the CoC.

Michael: It's more work for maintainers to manually update, but worth it.

Myles: Tooling can help us. A github action for instance to keep repos in sync. It seems like an automatable problem.

Brian: I like that. That ensures that the same CoC is rolled out across all the repose with minial pain.

Eemeli: My recollection is in sync with Myles'. Rather than trying to resolve exactly what we end up with, it's best to cover our options at this stage in order to cement our CoC practices.

>Possible Need: Guidance and tooling for using things like a .gh repo to managing

Brian: How often are we expecting to change after the initial change. Do we need this right now?

Eemeli: If we want to track with the upstream's latest release, we'll likely be doing this once or twice a year.

Myles: A single module could work to handle that if it's once or twice a year.

Jory: This feels like a next order problem that we don't need to have the answer to right now in order to merge this PR.

Naina: I agree.

Jory: Jordan H has already approved the PR. Has consensus been reached that this is a viable MVP? Should we merge it?

All: No objections.

Jory: Then the answer is yes. Hooray!

Jory: Now we need to figure out how to create this empowered team. As a matter of process, we should likely open these things as separate issues. I definitely feel that at least we should capture everything as a summary as we do this.

Michael: As we start to work on this we can create separate sub-issues.

Jory: Does this specific group need to meet then? Has the need of the ad-hoc group been answered? Can we leave the rest to the new CoC task force?

Joe: Isn't the COCP team a moderation team?

Michael: Their scope is escalations. What we've agreed upon is that we have an MVP.

Brian: The MVP is an adopted CoC, and a default escalation path. We have to have this in place asap. There could be an issue tomorrow.

Robin: If we can time-block and get this in place as we build it that's best. We really need this in place.

Myles: Having a list of volunteers that is spun out of this group and on a mailing list would be beneficial today.

All: General agreement.

Tobie: Let's make sure that the COCP's membership is diverse. 

Micheal: So we have to make sure we have a quorum of diversity now. A board member, a CPC member, top-level member, non-top level member, etc.

Brian: I can spin up a self nomination period, then we can take it to a vote.

Joe: What happens if we end up with a non diverse panel? If we land this, is it a hard stop? Can more people volunteer over time?

Robin: If you want diversity you have to reach out and invite them. I think it's important we do that.

Myles: People who're 'experts' is a bit ambiguous. Regarding the language here, doing another pass at it is probably appropriate. Should invites be done on a project by project basis? Also, what if someone we invite isn't comfortable about doing this? 

>Probable Future Need: training for individuals serving on the moderation team

Eemeli: Doing a self nomintation and vote isn't likely as advantageous as doing an intentional reach out in the interest of actual diversity.

Michael: We should still land this so we can move forward in any regard.

Joe: So 'land' means moving the PR we're discussing to stage 3. Should we modify that language to not be so prescriptive before we move to stage 3?

Michael: We need to figure out that language now then. We don't want this to be halted again.

Myles: We can add a simply caveat to address this. We shouldn't theoretically be adding things right before a merge if it's not vetted by the CPC and board, but right now we can just add people to the list if we feel like we should do it. I'm concerned that we're going to get stuck in a process holding pattern, because we're getting stuck right now while discussing it in this call. Let's add everyone who's been on the call to this lest, land the PR, and iterate. Let's bootstrap this now with the people here – if they don't want to participate they can request to be removed. If we're not happy with what we have we can change it.

Myles: Is there any problem with bootstrapping it this way, now?

All: No.

Myles: Okay, let's do it! 🚀

Robin: One of the hard things about project leads is that they're mostly all men. It's not diverse. Folks in the marketing committee are on the ground where the bad stuff happens.

Myles: The marketing will have a very reasonable stake in maintaining the CoC.

Jory: Alright, we have a lot of great action items. We've reached a logical conclusion of this call.

Michael: I'll land this PR as stage 3, then we'll get board approval, then we can take actions to PR in a change representing the marketing committee. That's the first order for next steps, then we can discuss what's next when we meet?

Jory: Yes. Thank you all! 🙏

All: Cheers! 🍻
