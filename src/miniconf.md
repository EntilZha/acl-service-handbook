# Miniconf for Conference Website

Miniconf has been used by several ACL conferences.
This guide shows future organizers how to use adapt prior iterations of acl_miniconf for future conferences and was written while adapting the EMNLP 2020 site for ACL 2023.

In this guide, the `conference` site refers to the webpage with important dates, registration, and organizers. This page is available long before the conference, e.g., for ACL 2023 https://2023.aclweb.org/, but does not contain the proceedings. The `virtual` site refers to what is built with miniconf, and hosts the site that participants will use during the conference.

## Setup

1. Create a new GitHub repository, which is where the conference site will reside
2. Clone the prior conference site, e.g., https://github.com/EntilZha/acl-miniconf
3. Push the prior conference site to the empty github repository. Do not create a fork. Github does not allow issues on forks and several other Github features are disabled on forks.


## What to change?

To update the site, be sure to change these files appropriately:

### Conference Theming

- `sitedata/config.yml`: Contains general links and resources (e.g., conference logo)


### Hand-Curated Files

For things like committee members, it is easier to create these files by hand (e.g., by pull request), rather than auto-generate them.

- `sitedata/committee.yml`: This file can be copied from the corresponding file on the conference site. For example, from here https://github.com/acl-org/acl-2023/blob/main/_data/authors.yml