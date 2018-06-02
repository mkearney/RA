
# Research Assistants

A repository for organizing my ideas and materials for research
assistants

## Fall 2018

### Project: Political/news media screen names

#### Politician screen names

  - Compile lists of Twitter screen names (professional and personal)
    for the following:
      - All current/past Senators
      - All current Representatives
      - All current/past governors
      - All current/past cabinet members (at least Pres, VP, SOS)

#### News reporting screen names

  - Compile lists of Twitter screen names (professional and personal)
    for the following:
      - All major news organizations
      - All major news programs
      - Current/past popular political reporters

#### Political pundit screen names

  - Compile lists of Twitter screen names (professional and personal)
    for the following:
      - All major political pundit organizations
      - All major political pundit programs
      - Current/past popular political pundits
      - All major political satire programs
      - Current/past popular political satire hosts

#### Political lobbying screen names

  - Compile lists of Twitter screen names (professional and personal)
    for the following:
      - All major political lobbying organizations
      - Current/past popular lobbying officials/organizers/spokespeople

### Data

  - Link to Google spreadsheet:
    <https://docs.google.com/spreadsheets/d/1mvGdz2rONx1ToH_Kc8Cq6GA1MFtljL7ZZawV5TR8CqU/edit?usp=sharing>
  - Data fields
      - `full_name` Name of organization/program/person
      - `screen_name` Screen name of organization/program/person
      - `personal` Logical, indicating whether the account is a
        “personal” (non-official) account
      - `type` Category describing the type of account. Must be one of
        following:
          - `politician`
          - `reporting`
          - `pundit`
          - `lobbying`
      - `subtype` Category describing the sub-type of account. Must be
        one of following:
          - `cabinet` Current/former member of US presidential cabinent
          - `senator` Current/former US Senator
          - `representative` Current/former US Representative
          - `governor` Current/former US Governor
          - `organization` Organization or company
          - `program` Media program
          - `person` An actual person
      - `cabinet_position` Category describing the cabinet position if
        applicable. Must be one of following:
          - `President`
          - `Vice President`
          - `White House Chief of Staff`
          - `Secretary of State`
          - `Secretary of Agriculture`
          - `Secretary of Commerce`
          - `Secretary of Defense`
          - `Secretary of Education`
          - `Secretary of Energy`
          - `Secretary of Health and Human Services`
          - `Secretary of Homeland Security`
          - `Secretary of Housing and Urban Development`
          - `Secretary of the Interior`
          - `Secretary of Labor`
          - `Secretary of Transportation`
          - `Secretary of the Treasury`
          - `U.S. Trade Representative`
          - `Attorney General`
          - `Director of National Intelligence`
          - `Director of the Central Intelligence Agency`
          - `Director of the Office of Management and Budget`
          - `Representative of the United States to the United Nations`
          - `Director of the Office of Management and Budget`
          - `Administrator of the Environmental Protection`
          - `Administrator of the Small Business Administration`
      - `state` Senator/Representative/Governor state e.g., Missouri,
        Hawaii, Oregon, Virginia, etc.
      - `parent_org` Name of parent organization (if obvious) e.g., the
        parent of Fox News Politics is Fox news.
      - `medium` Category describing the type of media e.g., TV, radio,
        internet
