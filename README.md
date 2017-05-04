# rust-unofficial guidelines

The rust-unofficial organization is a landing place for useful community
projects which would otherwise be abandoned.

The [nursery](https://github.com/rust-lang-nursery) is an organization where
official Rust project [teams](https://www.rust-lang.org/en-US/team.html) store
projects in development that are important to the Rust compiler itself and its
infrastructure.

## Why an org?

GitHub's permissions model makes it much easier to share ownership of projects
when they're owned by an organization.

* Keeping semi-abandoned repos in this organization helps offload the
  administrative tasks of managing user permissions to the Rust Community Team

* Keeping a repo in an org owned by an active team means that if all the
  maintainers disappear and someone else wants to step up, we can give them
  permissions instead of having to fork the project.

## Adding a repo to rust-unofficial

All Rust Community Team members have owner permissions on the rust-unofficial
organization, and can help you add a repository.

### Criteria for inclusion

#### "Useful" == "has users"

Any repo that's in use helping the Rust community, and moderately up to date,
is appropriate to consider moving to the rust-unofficial org. Documents,
crates, and tools written in Rust that have Rustaceans using or depending on
them all count.

#### Has a leader/caretaker

If you're a sole maintainer looking to retire from your repo entirely, you'll
need to find a caretaker for the project's maintenance before we'll transfer it
to the rust-unofficial organization.

The caretaker doesn't have to be an expert on your project, but needs to be
willing to take the initiative to reply to issues and act on pull requests.

The caretaker doesn't have to dedicate a lot of time to the project, but should
plan on taking an hour a couple times each month to respond to activity on the
repo.

If you are a community member who wants to see a repo saved from abandonment, 
you can be its caretaker! The intent of this rule is to make sure that this
organization doesn't collect abandoned or "Somebody Else's Problem" repos. 
"Somebody Else's Problem" repos create a bad experience for contributors and
for org owners.

#### Licensed

Repos should contain a valid LICENSE file, because people aren't legally free
to use unlicensed code. The LICENSE must be one which allows anyone to
maintain and use the software -- any
[OSI-approved](https://opensource.org/licenses) license is fine, and we'll
consider non-OSI licenses case by case to make sure they allow us to add
maintainers to the repo and distribute the code.

#### Follows the CoC

It should go without saying, but projects whose purpose or community violate
the spirit of the [Rust Code of
Conduct](https://www.rust-lang.org/en-US/conduct.html) guidelines will not be
adopted into this org.

### Getting your repo added

Join `#rust-community` on `irc.mozilla.org` and ask for help, or email
`community-team@rust-lang.org`. Include:

* What repo it is
* Who uses it / how it helps the community
* Who the leader/caretaker permissions should go to
* Confirm that the license allows modification and redistribution
* Confirm that the repo's purpose and content are consistent with the intent
  of the Code of Conduct

If the repo is suitable for inclusion in rust-unofficial, we'll first create
the `reponame-caretakers` team in the org and invite its leaders/caretakers.
Once they've accepted the invitations, we'll then have you transfer ownership
of the repo to the organization, and add the caretakers team with owner
permissions.

## Repo changes / removal

If there comes a time when a repo in rust-unofficial no longer meets the
organization's criteria, the Rust Community Team may:

* Contact the repo's caretakers and suggest a way to fix the situation
  (solutions can include adding more caretakers, changing specific content, or
  moving the repo to another org)
* If caretakers don't respond within a week or two of contact, we may add
  other volunteers as additional caretakers to the repo
* If no caretaker can be found for an extended period of time (several
  months), a community team member may mark the repo as deprecated or transfer
  it back to you or to another org

## Policy changes

If these policies turn out to be insufficient or unclear, we might change
them. If you have any suggestions for how the guidelines could be better or
clearer, submit an issue or PR to [this
repo](https://github.com/rust-unofficial/about)!
