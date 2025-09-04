##########################################################
Guidelines for User Support with the Rubin Community Forum
##########################################################

.. abstract::

   Guidelines for using the Rubin Community Forum to support the scientific community in their use of the data products, services, and tools created by the Rubin Observatory (or by other groups, e.g., brokers, independent data access centers). This primarily includes guidelines for answering users' questions and resolving issues, but also for posting Rubin-related news and announcements, enabling science discussions and collaboration, and settings to make accounts identifiable as Rubin staff.


Overview
========

The Rubin Community Forum (hereafter, the Forum) is based on the Discourse platform and can be found at the URL community.lsst.org.
Much of its content is publicly visible, and anyone may make an account and make posts (i.e., Rubin data rights are not required).

**The Forum’s primary use case is** `User support`_.
Anyone may ask a question about the Rubin Observatory’s data products, services, and tools; the Support category is dedicated to questions from users.

A traditional, closed help desk won’t scale well to the anticipated 10000 scientists and students.
This open platform enables self-help (i.e., users can search for similar questions) and crowd-source solutions (anyone may chime in with answers), while also providing the capabilities for Rubin staff to moderate posts and follow-up on unsolved issues.
The secondary use cases of the Forum are dispersing `News and announcements`_ and enabling `Scientific discussions`_.

This document contains guidance for everyone providing user support via the Forum.
This applies mainly to Rubin staff, but also representatives of broker and IDAC teams using designated Support sub-categories for their user support.
Members of the broader Rubin community do not need to read or follow this guidance when posting in the Forum.

This technical note supersedes the Interim Model for Community Support in `DMTN-155 <https://dmtn-155.lsst.io/>`_, and provides additional, practical details on the Model for Community Support in `RTN-006 <https://rtn-006.lsst.io/>`_.


User support
============

Answering users questions and resolving reported issues is the primary function of the Forum.


The Support category
--------------------

The Support category is entirely dedicated to answering user questions.

**Topic types:**
The only new topics posted in this category should be questions and issues reported by users.
No news, announcements, or discussion topics should be posted here.
All types of questions and issues are encouraged: "naive" questions; bug reports; account access issues; technically complex questions; inquiries about scientific analysis; and so on.

**Marked solutions:**
The marked solution functionality is enabled for this category.
Once the threaded reply post that answers the question is marked as the solution, it floats to the top of the thread and the topic gets a checkmark icon that identifies it as "solved".

**Daily monitoring:**
This category is monitored by the Rubin Community Science team who follow up on all unsolved topics.
The broker and IDAC subcategories are monitored by members of the relevant teams.


Goals, metrics, and principles
------------------------------

In providing support to users via the Forum, there are two goals:

#. The topic gets a marked solution.
#. The user has a positive experience.

The metrics, principles, and guidelines are designed to achieve these two goals.

**Metrics:**
The Rubin Community Science team tracks several quantities as key metrics to assess how well the goals are being met.
The Discourse platform, on which the Forum is based, has built-in tools that track the number of new users, visits, topics, posts, etc. as a function of time.

On a weekly basis, the number of new vs. solved Support topics is compared to make sure reported issues are being solved.

On a yearly basis, the number of accepted solutions and the time to first response are reviewed to ensure all issues got solutions, and that the time to first response was <24 hours on average.
The number of daily engaged users is also reviewed and indicators of whether users are having positive experiences.

**Principles:**
All responses to user support requests should be formulated with the goals in mind, and aim to incorporate the following principles.

Prompt.

* All new Support topics should have a first response within 24 hours.
* Reply posts that can be immediately marked as the solution are best.
* Partial answers are OK.

Direct.

* Answer the user’s question directly, as they’ve written it.
* Avoid hypothesizing on their use-case scenario.
* Avoid unnecessary commentary or questions.

Validated.

* Do not guess.
* Test and confirm a solution works before posting.

Inclusive.

* Use language that is simple and kind.
* Avoid jargon, acronyms, sarcasm, and jokes.
* Offensive or exclusionary language is never permitted.
* See the Forum's `Community Guidelines <https://community.lsst.org/faq>`_.

Referenced.

* Provide hotlinks to relevant documentation where applicable.


Guidelines for user support
---------------------------

Practical advice on how to provide user support in a way that is consistent with the goals and principles.


For everyone
^^^^^^^^^^^^

Encourage use of the Forum.

* Direct users to the Support category.

* Reassure them that all questions are appropriate and welcomed.

  * E.g., *"This is a great question, could you post it as a new topic in the Support category of the Rubin Community Forum at community.lsst.org? We’ll follow-up on it there."*


Provide validated examples that can be marked as the solution.

* Guesses or potential answers cannot be marked as a solution, and are not preferred.

  * E.g., *"You might want to look in the lsst geom or afw packages"* is not preferred.

* An answer that has been tested and confirmed to work can be marked as the solution by the support provider when it is posted; this is much preferred.

  * E.g., *"Here is some example code that imports the lsst.geom package and uses the radToDeg function to ..."* (followed by copy-pastable code block) is preferred.


Coordinate responses offline and follow up later, when needed.

* Full, validated solutions can take time and collaboration to develop; that’s OK.

* Avoid @-mentions in the Forum thread to people who “might know”.

* Provide an expected timeline without shutting down further conversation:

  * E.g., *"Myself and the <team> team will work on a solution and report back within a week. In the meantime others are encouraged to chime in on this thread."*


Be familiar with the Forum’s functionality.

* Review the banner instructions and the topics tagged with "forum-howto".

* E.g., how to mark solutions, format code and math, and flag posts.


For Rubin staff
^^^^^^^^^^^^^^^

Join the Rubin Observatory Slack channel ``#sp-cst-forum-support``.

* All new Support category topics have a Slack post there, via the Forum Bot.

* Use a threaded discussion to ask questions, coordinate responses, and at-mention other staff.

* Avoid starting new threads in other Slack channels for topics, to keep discussion centralized.

  * OK to post link to the Slack *thread* in other channels to encourage others to join that discussion.

  * If new Slack threads start, link to them from the ``#sp-cst-forum-support`` so Forum Watchers can find it.


Make your Forum account recognizable as Rubin staff by updating your account preferences.

* Adopt a username and name that are recognizable as you.

  * E.g., "MelissaG" is preferred to "CookiesForever3000" or "mlg".

* Change your profile picture from the default.

  * It need not be a picture of you.

  * The point is to look like an active account.

* Join the `LSST group <https://community.lsst.org/g/LSST>`_ and choose "LSST" as your "Title".

  * Or join the group relevant to your department or team.

  * It is OK to create new staff groups and add "Flair".

* Fill out your profile’s "About Me", timezone, and institute, at minimum.


CST
***

Make your Forum account recognizable as a Rubin CST member.

* Join the `CST group <https://community.lsst.org/g/CST>`_.
* In account preferences, under "Flair" choose "CST".
* The helping-hands symbol will appear in the bottom-right corner of your profile picture, identifying you as a CST member.


Most CST members will be moderators.

* Review the capabilities of `Moderators`_.


All CST members will serve in rotation as the weekly Forum Watcher.

* Review the `Forum Watchers`_ responsibilities.


Open tickets in the CST’s Issue Resolution epic in Jira, as needed, for follow-up.


DM
**

Join the LSST `Data Management group <https://community.lsst.org/g/LSSTDM>`_.

* Optionally, set "LSST Data Management" as your "Title" under account preferences.

As of writing, the LSSTDM group did not have a "Flair" option.
If, in the future, the LSSTDM group owners add a flair, feel free to choose it for your account.

Rubin DM staff are welcome to voluntarily serve as `Moderators`_ or `Forum Watchers`_.

If a question or reported issue will take work to resolve, discuss this work with your team lead.


For brokers and IDACs
^^^^^^^^^^^^^^^^^^^^^

Broker and IDAC teams are welcome to have subcategories under Support, and to provide their own user support via the Forum.

Teams are responsible to monitor their subcategory.

* At least one team representative should set themselves to “watching” the category.
* Rubin staff will not monitor these subcategories.
* Team reps should keep in mind the goals, metrics, and principles.

These subcategories should not be used for service announcements.

* Forum users are not advised to ‘watch’ the Support subcategories.
* Announcements are Topics that will never be solved, and will degrade the metrics.
* Use the Science Announcements category instead.

It is OK to create groups and add relevant titles and flair, so that team members are identifiable as representatives of the broker or IDAC team.


Roles and responsibilities
--------------------------

Rubin staff accounts can have special roles, which come with special responsibilities and powers.

Admins
^^^^^^

The Forum group `Admins <https://community.lsst.org/g/admins>`_ is composed of Jonathan Sick, Frossie Economou, and Melissa Graham.
They are identifiable by the double-shield icons that appear next to their name.

Admins have the power to edit the Forum's structure, layout, categories, banners, and so on.
Admins can edit user account profiles, merge duplicate accounts, and silence and suspend users.


Silencing and suspension
************************

The Lead Community Scientist is the single point of contact on all cases where users might need to be silenced or suspended.

**Silencing**:
A silenced user can log in, but cannot post new topics or replies (although they can send private messages).

A user will be silenced if their posts are repeatedly flagged or reported for violating the Forum's `Community Guidelines <https://community.lsst.org/faq>`_, and the Lead Community Scientist issues a warning via private message that if this behavior continues they will be silenced, and the behavior continues anyway.

There is some grey area in interpreting the guidelines, but "Improving the Discussion" and "Keep it Tidy" applies to posts that:

* are excessively long and rambling (e.g., opinion pieces)
* do not ask a question, or repeatedly ask the same question
* are not Rubin-related (e.g., expound on general astronomy theories)
* repeatedly or excessively at-mention other users


Silencing is temporary, and the timeframe should be set at two weeks.
Silenced users should be unsilenced after two weeks (provided the violations do not continue via private message, in which case a silenced user might be suspended before being unsilenced).

**Suspension:**
A suspended user will be unable to log in.

A user will be suspended if, after silencing, the negative behavior continues, the Lead Community Scientist issues another warning via private message that if this behavior continues they will be suspended, and the behavior continues anyway.

Suspensions are permanent.



Moderators
^^^^^^^^^^

The Forum group `Moderators <https://community.lsst.org/g/moderators>`_ is composed of CST and DM members, and broker and IDAC team representatives.
They are identifiable by the shield icon that appears next to their name. 

Moderator accounts have the power to take actions such as:

* editing a topic’s title or category
* moving a threaded post to a different or new topic
* marking someone else’s post as a topic solution
* reviewing posts that were flagged automatically or by other users
* deleting flagged posts and topics, and the associated user


Guidance on flagging and moderation.

* `Discourse platform advice on flags <https://meta.discourse.org/t/discourse-moderation-guide/63116#handling-flags-17>`_
* `How to be a forum moderator <https://community.lsst.org/t/how-to-be-a-forum-moderator/4700>`_
* `How and why to flag a post <https://community.lsst.org/t/how-and-why-to-flag-a-post/4699>`_


How to moderate flagged posts.

* Approve flagged posts that seem fine.

  * Keep in mind that the bot-detectors can mistake real people for bots.

  * E.g., posts with "too many links" or that are "written too fast" can trigger the bot-detector.

* Reject flagged posts that are obviously bots, are non-astronomy or advertisements, or are CoC violations.

  * Also delete the user when it is obviously a bot or an advertiser.

* Reject flagged posts that are in violation of the Forum's `Community Guidelines <https://community.lsst.org/faq>`_.

* If unsure, ask about it in Slack.


How to move a reply post to a new topic.

* Click the wrench, select "Select Posts", click "Select" on the post(s) to be moved.
* In the pop-up click "Move To", then fill out the next pop-up and click "Move to a New Topic".
* Explain to the user what you did and why, reaffirm that it was a good question and that you, as moderator, want to make sure it gets resolved.


If you witness harassment, flag (or remove) the inappropriate post.

* Forum admin and moderators will still be able to see it (for reference).

* Depending on the situation, consider:

  * reaching out to the receiver and offering support

  * referring the receiver to Rubin's Workplace Culture Advocates

  * raising the issue to the CST for assistance


If you think a user needs to be silenced or suspended, raise the issue with the Lead Community Scientist (see `Admins`_).


Forum Watchers
^^^^^^^^^^^^^^

Every week, one member of the Rubin Community Science team is the designated Forum Watcher.
In addition to the principles and best practices above, Forum Watchers have extra responsibilities.

Enable real-time notifications.

* E.g., via web browser or email.


Rapidly review and approve posts from new Forum users.

* To avoid AI bots, posts from new users need approval.
* Aim for same-day approvals (within hours during your local workday).
* For background see `New user permissions and availability of posts <https://community.lsst.org/t/new-user-permissions-and-availability-of-posts/9357>`_.


Moderate the Forum by flagging posts and dealing with flags.

* As described in `Moderators`_.


Keep an eye out for new questions posted in old or solved topics.

* If you can answer it right away, just do so.
* If not, move the reply to a new topic thread (see `Moderators`_).


Review all new Support topics and take a swift initial action.

* This "initial action" will depend on the question and your own expertise.
* Aim for an initial response within 24 hours.
* Provide answers if you already know them, or can find them quickly.
* Try to reproduce the user’s issue yourself.
* Ask for clarification and encourage users to post code and error messages.
* Try to figure out the solution, or proceed to triage (below).


Triage more complicated Support topics for follow-up.

* Reach out to other Rubin staff for technical assistance.

* Open new Jira tickets in the CST Issue Resolution epic when follow-up work is needed.

  * Follow the CST internal workflows in Confluence for issue resolution and Jira use.

* Avoid short reply posts like *"We’re looking into it"*, as they don’t provide a timescale to set expectations and it can shut down further input from other Forum users.

* Instead use reply posts like *"We’ve opened an internal work ticket (<link SP ticket>) to follow up on this issue and we’ll report back within <timeframe>. In the meantime, all are welcome to chime in with ideas here"*.


Review unsolved Support topics from the past month.

* If a clear solution has been posted but not marked, mark it.

* If a *potential* solution has been posted and not marked, encourage the user to report back whether the issue is resolved.

  * Do not do this if the last post in the thread is already doing that.

* If work is proceeding in a corresponding Jira ticket, it’s OK to do nothing.

* Check the relevant thread in the Slack channel ``#sp-cst-forum-support``.

  * There may be a reason why this topic is being left unsolved.

* Otherwise, review and triage the topic as if it were new.

  * Ensure there is a Jira ticket for unsolved topics.


Be prepared to report in the weekly CST meeting.

* Raise questions and challenges for team discussion.
* CST will review progress on Jira tickets in the Issue Resolution epic.


Confidential support
--------------------

Rare situations in which a support topic might publicly reveal critical details of a work in progress might need confidential support.

First, advise the user to try anonymizing their question when they post, using one of these methods.

* Recreate the error with an object that is not of interest.
* Describe the issue without quoting object or visit identifier numbers.

Alternatively, if it is not possible for the user to describe the issue without the risk of revealing critical details, they should send a direct (private) message to the Lead and Deputy Lead Community Scientists, Melissa Graham (@MelissaGraham) and Jeff Carlin (@jeffcarlin), who will follow-up confidentially.

For more guidance on confidential support:

* `How to ask a question confidentially <https://community.lsst.org/t/how-to-ask-a-question-confidentially/8200>`_


News and announcements
======================

Dispersing information such as news, announcements, events, and opportunities is a secondary function of the Forum.

The Forum banner advises users to "watch" two categories in order to stay informed: the News and Science Announcements categories.


The News category
-----------------

All major news for scientists from Rubin Observatory should go in the News category.

* The biweekly Rubin Digest.
* Major conferences and workshops.
* Commissioning updates.
* Major data and software releases.
* Anticipated service disruptions (in the Data Services subcategory).

To keep the rate of new topics to a few per week or less, only members of the Rubin News Editors group may create new topics in this category.


The Science Announcements category
----------------------------------

Anyone may make a new topic in this category to advertise Rubin-related events.

* Meetings and seminars.
* Conferences and workshops not run by Rubin staff.
* Data or software releases from non-staff developers.

Advice for everyone is provided in `How to advertise in the Forum <https://community.lsst.org/t/how-to-advertise-in-the-forum/8196>`_.


Tips for effective advertising
------------------------------

Create a new topic for every new announcement.

* This will prompt notifications for users “tracking” the category.
* This provides a new thread for comments, questions, etc.

Include the time, date, and year in the topic title.

* To distinguish topics for recurring events (e.g., annual workshops, data releases).
* This applies also to deadlines.

Safeguard against Zoom-bombing.

* All topics are publicly visible.
* Do not do not post Zoom links in the body of the topic.
* Consider, e.g., a Google form with an automatic email reply with the link.

Post notes and recordings as replies in the thread.

* Paste a YouTube link on a new line and the video will automatically embed.


Scientific discussions
======================

Open discussion and collaboration on any and all topics related to Rubin science is a secondary function of the Forum.


The Science category
--------------------

This category and its subcategories are open for anyone to post new topics for discussion.

There are no guidelines regarding the types of topics that are posted – it is completely left to the broader Rubin community to use these categories however they want.

These categories are not monitored by Rubin staff and do not have the "marked solution" functionality enabled.


Time-domain research announcements
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forum users may propose to use the Discourse API in a sub-category to auto-generate new topics for time-domain phenomena.
This enables the Forum to be used for public, worldwide discussions about time sensitive follow-up.

New APIs are first implemented on a year-long trial basis to confirm that the number of auto generated new topics is on order a few per day or less (any more is too many for human interaction, which means the Forum is the wrong tool).
Such APIs must be muted from the Forum landing page feed, and it is recommended to restrict access to a group (i.e., users must opt-in to seeing the announcements), but the group itself can be openly joinable.

The Forum admins (Rubin staff) retain the right to restrict or remove such API-based functionality if it interferes with users’ ability to obtain support or news.


The Science Collaborations category
-----------------------------------

This category and its subcategories are accessible only by Forum users who have joined one of the groups associated with an LSST Science Collaboration.

They are completely left to the Science Collaborations to use however they want.

They are not monitored by Rubin staff and do not have the "marked solution" functionality enabled.


Recommendations for Science Collaborations Chairs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In order to help Science Collaboration chairs make the best use of the Forum, the Rubin Community Science team has prepared a set of optional recommendations in the Forum topic `How to use the Forum as Science Collaboration chair <https://community.lsst.org/t/how-to-use-the-forum-as-science-collaboration-chair/8420>`_.



Terminology
===========

Banner: The main landing page of the Rubin Community Forum has an expandable banner (header) with instructions.

Categories: High-level themes to organize topics. Only Rubin staff can create new categories.

Topics: A topic thread starts with a single post, which other Forum users can reply to.
Topics are stored in categories.
All logged-in Forum users can create new topics and post replies in the thread.

Tags: A topic can have any number of tags, or none.
Tags are useful as a secondary means of organization (after categories).

Profile: The attributes of a user's account, such as username, profile picture, and notification settings.
To edit profile preferences click on your profile picture in the circle at upper right, then the person icon, then on “Preferences”.
Alternatively: ``community.lsst.org/u/<username>/preferences/account``.

Groups: Groups identify Rubin staff teams, committees, and Science Collaborations.
Some categories are only visible to members of certain groups.
Some groups allow themselves to be @-mentioned or messaged.

Private (direct) messages: To access messages, click on your profile picture at upper right, then the envelope icon to see a list of recent messages.
Click on the envelope icon again to go to your inbox.
Alternatively: ``community.lsst.org/u/<username>/messages``.

Watch / subscribe: a setting that enables users to get notifications (in-browser or via email) for all new topics in a given category.
