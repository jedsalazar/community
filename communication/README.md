# Communication

The Kubernetes community abides by the [Kubernetes code of conduct] on all of
communication platforms that we moderate listed below with noted exceptions.  
Here is an excerpt from the code of conduct:

> _As contributors and maintainers of this project, and in the interest
> of fostering an open and welcoming community, we pledge to respect
> all people who contribute through reporting issues, posting feature
> requests, updating documentation, submitting pull requests or patches,
> and other activities._

## Purpose of this doc

A detailed list of upstream communication platforms and resources for contributors.
Since upstream contributors are generally consumers, many of our channels intertwine.
See [Misc Community Resources] for more end user/troubleshooting targeted paths.

## Community Groups

Kubernetes encompasses many projects, organized into [community groups].
The upstream communication flows through those channels, most
notably in the Special Interest Groups [SIGs] that own the docs and
codebases. Their communication channels may include mailing lists, slack channels,
zoom meetings, meeting agenda/notes, and can be found on their READMEs and on the
community groups/[SIGs] page.

You can actively or passively participate in one of the following ways:
- the community groups public meeting(s) listed in the above community groups page
- every Thursday at our [weekly community meeting] over [zoom] at [10am US Pacific Time]
- intro sessions at KubeCon/CloudNativeCon live or recordings on YouTube[need a link here]

Nevertheless, below find a list of many general channels, groups
and meetings devoted to the Kubernetes project. Please check the guidelines and
any relevant chat/conversation history before posting. Spam and sales pitches are
not tolerated on these platforms.

## Decisions Are Made Here

The project is very large with a robust community group ecosystem and bubbling up
information is important. Transparency is necessary and these channels are key:

- [kubernetes-dev] mailing list - all upstream Kubernetes news and discussion.
Many commmunity groups have charters that state they have to post here for
certain topics like project wide changes. Joining this mailing list is required
[k-dev moderators]
for GitHub [org membership] and will get you access to all community docs that are
not in GitHub.
- GitHub Issues and PRs in an [associated repository] and
- KEPs[(Kubernetes Enhancement Proposals)]
  - We don't recommend following or watching any repository unless you are using
  [heavy email filters]. Getting involved with the community group(s) directly is
  the best way to find out how to best watch what you need on GitHub.  

## Discussions Happen Here

We talk a lot, too.

### Slack

Our real-time platform with Kubernetes enthusiasts spread across 250+ channels.
Owned and operated by sig-contributor-experience.
[Join] | [Slack Guidelines] | [slack moderators] | #kubernetes-dev

Pro-tip: If you want to add a new channel, simply file a request following [these
instructions].  

### Mailing lists and forums

Most of the Kubernetes mailing lists are hosted through Google Groups or [Discuss Kubernetes].
These also power most of the access to our documentation and calendar items like
SIG meetings.  
[mailing list guidelines] | [email filtering tips]

- [kubernetes-announce] broadcasts major project announcements such as releases
and security issues
- [kubernetes-dev] hosts contributor announcements and discussions for upstream
- [Discuss Kubernetes] is a forum where Kubernetes users trade notes with sections
for contributors and all kinds of ecosystem related content
- Additional Google groups exist and can be joined for discussion related to each
community groups as noted above.  These are linked from the [SIG list](/sig-list.md).

### Calendar & Meetings

We use Zoom for all of our community group meetings and contributor programs.  
[Zoom Guidelines]

We keep a [shared calendar] with all of our community group meetings. If you'd
like a contributor event published, please reach out to #sig-contribex on slack.  

### Social Media & Blogs

**Twitter**  
- [@kubernetesio]  
 - owned and operated by CNCF. Contact: social@cncf.io
- [Last Week in Kubernetes Development]  
 - owned and operated by Josh Berkus

**YouTube**   
owned and operated by sig-contribex [community management] subproject  
[Kubernetes Community channel] - recordings of
community group meetings, Thursday community call, meet our contributors, office
hours, and more  
[YouTube Guidelines]  

**Kubernetes [Blog]**   
owned by sig-docs and operated by the
[blog team]  
| [submit a blog post]| [2018 blog metrics]

## Misc Community Resources
### Issues & Troubleshooting

For questions about installing, running, or troubleshooting Kubernetes,
please start with the [troubleshooting guide]. If that doesn't answer your question(s),
try to post on discuss.kubernetes.io or if you think you found a bug, please [file an issue].

### Office Hours

Office hours are held once a month. Please refer to [the docs]()
to learn more. Join the conversation on slack under #office-hours.

### Other
- [r/kubernetes] - reddit channel owned and operated by community members and
not an official channel for the project.
- [awesome kubernetes list] - not an official repo; maintained by a community member.
a repo with a huge collection of links to books, talks, and other Kubernetes learning
resources.
- [kubeweekly] - owned by cncf and curated by community members listed on the site.
Collection of news, blogs, talks, and events for all things Kubernetes.
send submissions to kubeweekly@cncf.io

### Conferences, Meetups, Summits, and Face to Face Meetings

CNCF is the main driver for all KubeCon + CloudNativeCons, Kubernetes Forums,
and the [Kubernetes Meetup Pro] program on meetup.com. KubeCon + CloudNativeCon,
held every spring in Europe, summer in China, and winter in North America.
Information about these and other community events is available on the CNCF [events]
pages.  

The project also has several face to face meetings and contributor summits
throughout the year. To stay updated, check the calendar, your community group of
interest, and/or the #contributor-summit slack channel for more information.


### Thank You

A special thanks to all of our volunteer [moderators] who work in different time
zones all over the world to make all of our communication platforms an enjoyable
place!



[Blog]: https://kubernetes.io/blog/
[shared calendar]: https://calendar.google.com/calendar/embed?src=cgnt364vd8s86hr2phapfjc6uk%40group.calendar.google.com&ctz=America/Los_Angeles
[Kubernetes code of conduct]: /code-of-conduct.md
[events]: https://www.cncf.io/events/
[file an issue]: https://github.com/kubernetes/kubernetes/issues/new
[kubernetes-announce]: https://groups.google.com/forum/#!forum/kubernetes-announce
[kubernetes-dev]: https://groups.google.com/forum/#!forum/kubernetes-dev
[Discuss Kubernetes]: https://discuss.kubernetes.io
[Join]: http://slack.k8s.io
[Slack Guidelines]: /communication/slack-guidelines.md
[10am US Pacific Time]: https://www.google.com/search?q=1000+am+in+pst
[troubleshooting guide]: https://kubernetes.io/docs/tasks/debug-application-cluster/troubleshooting/
[@kubernetesio]: https://twitter.com/kubernetesio
[zoom]: https://zoom.us/my/kubernetescommunity
[weekly community meeting]: https://docs.google.com/document/d/1VQDIAB0OqiSjIHI8AWMvSdceWhnz56jNpZrLs6o7NJY/edit#
[community groups]: https://git.k8s.io/community/governance.md#community-groups
[these instructions]: /slack-guidelines.md#requesting-a-channel
[community management]: https://github.com/kubernetes/community/tree/master/sig-contributor-experience#community-management
[kubeweekly]: https://kubeweekly.io/
[r/kubernetes]: https://www.reddit.com/r/kubernetes/
[awesome kubernetes list]: https://github.com/ramitsurana/awesome-kubernetes
[Last Week in Kubernetes Development]: http://lwkd.info/
[Kubernetes Meetup Pro]: https://github.com/cncf/meetups
[associated repository]: https://github.com/kubernetes/community/tree/master/github-management#actively-used-github-organizations
[Misc Community Resources]: #linktothissectionofdoc
[mailing list guidelines]: https://git.k8s.io/community/communication/mailing-list-guidelines.md
[SIGs]: /sig-list.md
[(Kubernetes Enhancement Proposals)]: https://github.com/kubernetes/enhancements/tree/master/keps
[Kubernetes Community channel]: https://www.youtube.com/c/kubernetescommunity
[YouTube Guidelines]: https://github.com/kubernetes/community/blob/master/communication/youtube/youtube-guidelines.md
[2018 blog metrics]: https://docs.google.com/spreadsheets/d/19nhQppxmFfrqoYue4JsxUKN6nTZ-ZOebjXOspumXjIc/edit?usp=sharing
[email filtering tips]: https://github.com/kubernetes/community/blob/master/communication/best-practices.md
[heavy email filters]: https://github.com/kubernetes/community/blob/master/communication/best-practices.md
[org membership]: https://github.com/kubernetes/community/blob/master/community-membership.md
[blog team]: https://github.com/kubernetes/community/tree/master/sig-docs/blog-subproject
[submit a blog post]: https://kubernetes.io/docs/contribute/start/#write-a-blog-post
[zoom guidelines]: https://github.com/kubernetes/community/blob/master/communication/zoom-guidelines.md
[the doc]: /events/office-hours.md
[moderators]: https://github.com/kubernetes/community/blob/master/communication/moderators.md
[slack moderators]: https://github.com/kubernetes/community/blob/master/communication/moderators.md#slack
