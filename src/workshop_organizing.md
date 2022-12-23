# Workshop Organizing

The general chair of each conference invites **workshop chairs**.
Here we use "workshops" also to refer to co-located conferences (e.g., CoNLL and WMT).
Around the end of the calendar year, the workshop chairs of conferences in the next year (usually ACL, EMNLP, COLING, NAACL, EACL and AACL) issue a joint call for workshop proposals.
We assume conferences are hybrid (in-person and virtual), and so are workshops. Deviations are possible, but must be clarified early.
[aclpub2](https://github.com/rycolab/aclpub2) is used to compile the proceedings. Workshops are expected to provide all the input files in designated metadata repositories and ensure they compile.

## Role and Duties of Workshop Chairs

### Joint Duties of Workshop Chairs for a Calendar Year
* Consult with Jennifer Rachford and last year's workshop chairs to ensure these guidelines are up-to-date
* Create a mailing list or Google Group for all workshop chairs of the calendar year (e.g., `workshop-chairs-<year>@googlegroups.com`)
* Obtain registration and attendance statistics from recent years
* Hold an online survey among ACL members about likely workshop attendance
* Issue a joint call for workshop proposals
* Set up a submission site for workshop proposals (so far this has always been on SoftConf START)
* Review the submitted proposals and jointly decide on selected workshops and their assignment to conferences

### Duties of Workshop Chairs for a Conference
* Create a mailing list or Google Group for all workshop organizers of the conference
* Create a Slack workspace for all workshop organizers of the conference
* Find out the layout of the venue (how many rooms and their capacity)
* Send the list of accepted workshops to the website chair so that they are put on the website
* Coordinate with the general chair of the conference to get the important dates for all workshops (submission deadline, notification deadline, camera-ready deadline, proceeding deadline)
* Communicate the instructions to the workshop organziers for assembling the materials for the proceedings, handbook, website and virtual platform ([example](https://docs.google.com/document/d/18AUrckT7HgO9e4J9P_P4cH4t5iZ0Rh5rGT3PyV35QQA/edit?usp=sharing))
* Prepare a coordination sheet for all conference workshops ([example](https://docs.google.com/spreadsheets/d/1qGfDoY4YUJuZ4dGjvut37xeRdbserDUQ_DqXrTabRTY/edit?usp=sharing)), containing the following information, to be filled in or verified by the workshop organizers:
  * Workshop ID (`W1`, `W2` etc.)
  * Abbreviation
  * Full name of the workshop (including ordinal number if relevant)
  * Full names, contact details, GitHub usernames and SoftConf usernames of all workshop organizers
  * Name of book chair (person responsible for assembling metadata)
  * URL of submission site for the workshop
  * Workshop website URL
  * Duration in days
  * Preferred day (if a single-day workshop)
  * Estimated number of physical posters
  * Whether the workshop is in-person, virtual only or hybrid
  * Metadata repository on GitHub (see below)
  * Name of invited speaker with waived registration fees (one per workshop)
* Assign workshops to days among the two days following or preceding the main conference
* Ask the conference publication chairs to create a GitHub organization for the conference
* Under the GitHub organization, create a repository for each workshop, which will contain the metadata for the proceedings, handbook, website and virtual platform ([example](https://github.com/rycolab/aclpub2/tree/main/examples/sigdial)):
* Ask workshop organziers to fill in the following files in their metadata repository as soon as possible:
  * `conference_details.yml`
  * `organizing_committee.yml`
  * `program_committee.yml`
* Issue attendance survey to all authors of accepted workshop papers and provide the workshop organizers with access to responses
* Provide the list of book titles to Jennifer Rachford to issue ISBNs, and add the ISBNs to each workshop's `conference_details.yml`
* Ask Jennifer Rachford how to handle waived registration fees - either through a coupon code or with a special registration form checkbox
* Coordinate requirements for space and in-person poster presentations with the local organizers
* Inform workshop organizers about poster board sizes
* Coordinate requirements for uploaded materials from authors, virtual poster space and Zoom room with the virtual platform provider (e.g., Underline)
* Receive list of Findings papers from program chairs and select papers to suggest to workshops for presentation
* Ask workshop organziers to fill in the following files in their metadata repository after they make acceptance decisions:
  * `papers.yml`
  * `program.yml`
  * `invited_talks.yml`

## Role and Duties of Workshop Organizers
* Submit workshop proposal to the joint call
* Publicizing the workshop
* Reviewing submissions
* Producing the camera-ready workshop proceedings
* Organizing the event itself
* Ensure that all participants are aware of [ACL's anti-harassment policy](https://www.aclweb.org/adminwiki/index.php/Anti-Harassment_Policy)
* Commit to all deadlines provided by the workshop chairs
* Nominate a *book chair* responsible for assembling the materials for the proceedings, handbook, website and virtual platform
* Create a website for the workshop and share the URL with the workshop chairs
* Create a submission platform for workshop papers: either
  * Set up OpenReview (free) and manage reviewing yourself: [form](https://openreview.net/group?id=OpenReview.net/Support)
  * Set up Softconf (paid by ACL) and manage reviewing yourself: ask the workshop chair to help, providing them with the following information (via the coordination sheet):
    * full name of the workshop
    * short name for submission site URL
    * softconf usernames of the organizers
  * Receive submissions from [ACL Rolling Review](https://aclrollingreview.org/organizers) (free, and you do not need to manage reviewing yourself): contact the [ARR Editors](mailto:editors@aclrollingreview.org), providing
    * a link to the workshop website,
    * the last ARR submission date
    * the last commitment date
  * Hybrid: a combination of OpenReview and ARR, or Softconf and ARR
* Check the information on the conference website and notify the workshop chairs if it needs updating
* If you have sponsors,
  * To generate an invoice, email Chris Callison-Burch the following information:
    * What company is sponsoring the workshop (CC your contact in the company)
    * The name of your workshop
    * How much money are they contributing to the workshop?
  * Instruct Jennifer Rachford how to make the payments from the sponsors
* Select one invited speaker who will be waived registration fees for the conferences and the workshops (or more if you have sponsorship and would like to use it to cover registrations)
* Select Findings papers for presentation and contact the authors to confirm with them and ensure they upload the required materials
* Add the required information to your metadata repository and ensure your proceedings compile with `aclpub2` and that the output looks OK

## Timeline
The timeline will vary from year to year. This was the EMNLP 2022 timeline:
* September 23, 2021: First call for submission of workshop proposals for ACL/NAACL-HLT/COLING/EMNLP 2022
* October 20, 2021: Deadline for submission of workshop proposals
* November 20, 2021: Notification of acceptance of workshops
* July 15, 2022: Last [ARR submission deadline](https://aclrollingreview.org/six-week-cycles/) for workshop papers 
* September 7, 2022: Workshop paper direct submission deadline
* October 2, 2022: Last ARR commitment deadline for workshop papers
* October 6, 2022: Workshop organizers receive list of Findings of EMNLP papers (150-200) to possibly be presented at workshops
* October 9, 2022: Workshop paper notification deadline
* October 16, 2022: Workshop paper camera ready deadline
* October 20, 2022: Deadline for assigning Findings of EMNLP papers to be presented at workshops
* October 24, 2022: Workshop schedule deadline; deadline for assembly of handbook materials
* November 16, 2022: Workshop proceeding deadline; deadline for uploading presentation contents by authors
* December 7-8, 2022: EMNLP 2022 workshops and tutorials

## References
[Workshop chair duties, ACL Wiki](https://www.aclweb.org/adminwiki/index.php?title=Workshop_chair_duties)
