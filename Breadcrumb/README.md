The idea behind these breadcrumbs is to provide a framework for people to create personalized curricula that can be given to other learners to work through and improve as they do.  These breadcrumbs represent the basic cell that makes up the larger structure of Praxis.  They should, in their 1.0 implementation, have the following characteristics:

1. Tracking
There should be an identifier that represents not only the seed that lies at the root of the trail of crumbs, but also some information about where it has traveled and what it's versioning is.
2. Encapsulated ???
Each breadcrumb should represent a complete learning track, similar to a course hierarchy in a traditional college.  These crumbs do not necessarily have to be complete to be transmitted, but the completion of the crumb should be an ever-present goal [[ this element may conflict with **flexibility** and**ease of transmission**, and if that is the case this is the one we should axe. ]]
3. Mentored
The last person to work on the crumb should make themselves available to answer questions if possible.  As a matter of fact, if you put information in a crumb it should be tied to your contact information in some way that allows someone doing legitimate work on the crumb to reach out for questions about the crumb.  I understand that this might lend itself to some problems (all of a sudden, your contact deets are public) so this piece requires more thought and reflection to come up with a solution that a) Doesn't expose sensetive personal data and b) allows for a robust feedback mechanism that contributes to improvement of the crumb.  Additional concerns relate to how open-source a crumb can be (if I have a thousand people working through my crumb I don't want to be bogged down with a thousand questions in a day).  Perhaps there are answers to be had in stackxchange's mechanisms to reduce redundant questions and flexibly attach answers to unique ones.
4. Principled
Every crumb should contain a license that delineates not only the usability of the crumb (something like an EFF or apache), but also contains the cultural source code of the Praxis project.  Central to the operation of this community is going to be the values and principles it is based on.  Additionally, these crumbs should reference a guide that serves as a template for all crumbs - a set of guidelines (like these in this list) that define best-practices for creating and curating self-driven curricula.
5. Naming Convention
The naming convention should contain as much information about who wrote the breadcrumb and what it's about as possible.  Also, names should be so unique that it's impossible to mistake two breadcrumbs on the same topic.  Additionally, the format of a breadcrumb name should be immediately recognizable as a breadcrumb.  This naming convention should apply to the directory that houses the breadcrumb as well as the git it lives in.  Perhaps as well to the central file of the breadcrumb.
6. Ease of transmission
Whatever other elements there are to these, it is imperative that after creating a breadcrumb, it is easy for an individual to give it out to as many people as possible without being precious about it.  This fosters widespread transmission, which in turn fuels the iteration engine and, more importantly, provides the greatest chances of finding someone who will complete and revise the breadcrumb and retransmit the culture.
7. Flexible
The format and structure of these breadcrumbs should be flexible enough to allow for broad experimentation.  Coupled with the iteration engine, this should provide optimal results (as if we get 5000 shitty crumbs and one fantastic one, this project can be considered a success.)
8. README
It should be a cultural convention that we write good, accessible READMEs.  Especially if the format and structure is going to be flexible.  We should try to make it a point of pride that anyone can pick up a breadcrumb, read the README, and make use of the crumb.


# Naming Conventions Spitballing and Breakdown
{Version number - where X.YY X=the number of breadcrumbers who have worked on this breadcrumb, zero indexed -and- YY is current revision }{Initials of original breadcrumber}{Initials of most recent breadcrumber}{Initials of current breadcrumber}{Topic, at the most specific scope that encapsulates the whole of the breadcrumb}


0.00_BM-XX-XX_PYTHON

