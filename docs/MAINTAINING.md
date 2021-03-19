# Maintaining LoopBack

Congratulations! Since you're reading this page, you are probably already a
maintainer of this repo or close to be one. Thank you for your contributions so
far!

## Why do I want to be a maintainer?

- Greater influence on LoopBack's future direction
- Commit (write) rights to `loopback-next` repo
- Ability to review and land pull requests, edit/categorize/close issues

## What are responsibilities of a maintainer?

We ask you to follow the existing processes, see
http://loopback.io/doc/en/contrib/Governance.html. This means mostly:

- Be nice to others
- Try to reach consensus with other maintainers before making a decision
- Always use pull requests to make code changes
- Honour our current conventions, see
  http://loopback.io/doc/en/contrib/triaging-pull-requests.html and
  http://loopback.io/doc/en/contrib/style-guide.html (but feel free to propose
  changes to these conventions!)
- To avoid possible confusion, we don't have any specific requirements about the
  amount of time you should spend on the project - just keep working on things
  that you find important to you, in a pace that suits you. We may ask you to
  take a look at issues and pull requests related to code you contributed
  yourself.

## More questions?

**Q: Now that I have rights to merge pull requests, how many approvals from
other maintainers before I can merge?**

A: If the changes are straightforward and you're confident about the changes,
please go ahead to merge it. Otherwise you can always mention
[@strongloop/loopback-maintainers](https://github.com/orgs/strongloop/teams/loopback-maintainers)
in the GitHub issues/pull requests.

**Q: If I have questions/suggestions on the contribution process, what should I
do?**

A: We are always open for suggestions on how to make the process for
contributors or maintainers smooth. If you have any feedback, please open a
GitHub ticket for discussion.

## Nominating new maintainers

The nomination process is open to all current maintainers. Nominations are
discussed in private, using
[GitHub Team Discussions](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/about-team-discussions).
(Don't confuse Team Discussions with recently introduced project-level
[Discussions](https://docs.github.com/en/discussions).)

1. To nominate a new maintainer, post a new comment to the Team Discussion of
   the team you want the new maintainer to join. If you are not sure which team
   to choose, then pick
   [loopback-maintainers](https://github.com/orgs/strongloop/teams/loopback-maintainers).

   _New to Team Discussions? Learn more in GitHub docs:
   [Creating a new discussion](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/creating-a-team-discussion)._

2. Set the title to `Nominate {@handle}`, e.g. `Nominate @bajtos`.

3. In the description, fill in the following template. Use hyperlinks where
   appropriate, to make it easier for other maintainers to find and review the
   supporting documentation.

   ```md
   **GitHub id:** <!-- e.g. @bajtos -->

   **Active github repo(s):**

   <!-- e.g. https//github.com/strongloop/loopback-datasource-juggler -->

   **Reasons for nomination:**

   <!--
   A short explanation why you are nominating the person. Have they contributed
   a significant improvement or a series of small changes? Are they active in
   our issue tracker and/or discussions? Something else?
   -->

   **Their work & contributions:**

   <!--
   Please include links to GitHub where people assessing the nomination can
   review comments and code posted by the nominee.

   Few example URLs:

     All pull requests created by @nflaig in loopback-next repository:
     https://github.com/strongloop/loopback-next/pulls/nflaig

     Issues in any of `strongloop` repositories where @mitsos1os commented:
     https://github.com/issues?utf8=✓&q=org%3Astrongloop+involves%3Amitsos1os
   -->
   ```

4. Make sure to change the default visibility from
   `StrongLoop and IBM API Connect` to `Private`.

5. Post a link to the new topic to the Slack channel
   [#loopback-maintainers](https://loopbackio.slack.com/archives/GRP782GAZ), to
   let other maintainers know about the nomination and ask for feedback.

6. Allow at least 7 days for everybody to review the nomination. A nomination is
   accepted if there are at least 2 other maintainers voting for it and there
   are no (unresolved) objections.

7. Once the nomination is accepted, ask @dhmlau to reach out to the nominated
   person and invite them to become a maintainer.

8. Before sending the invitation to join the GitHub org and maintainers team,
   delete the nomination discussion, so that it won't be visible to the new
   maintainer.

   _We hope this setup will enable honest and open discussions about both
   positive and negative things, preventing self-censorship we might apply if we
   knew the nominee was going to read it after joining the project. Having said
   that, our code of conduct applies to nomination discussions too. Keep your
   feedback civilized and constructive, as always._
