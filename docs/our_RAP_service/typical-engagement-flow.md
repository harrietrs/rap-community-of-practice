# Typical Engagement Flow

This example describes a typical lifecycle of applying RAP principles to an existing product.

It's important to remember that every team is different and so there is no _really typical_ engagement, but hopefully the below gives you an idea of what's involved.

The approach described is the [support model][1] where the RAP team leads the development as this is our most frequent approach.

> Please note that a direct engagement with the RAP team at NHS Digital is currently only available to NHS Digital teams. The below is intended to help other organisations that may be developing their own RAP capabilities and are looking for guidance.

## Initial outreach

- Hear about RAP through show-and-tells, internal advertising, slack, etc.
- Have a look over the [RAP Community of Practice](https://github.com/NHSDigital/rap-community-of-practice) pages to get a sense of what it is all about.
- Reach out to the [RAP team](mailto:datascience@nhs.net) for a chat
- Together with someone from the RAP team, walk through the [levels of RAP][2] page and consider the team's scale of ambition.

- If you are keen to proceed, pass the request to the RAP product owner for prioritisation and resourcing
- Get a start date in the calendar. Think about publication timing, team capacity, etc. to choose a good time.

## Setting the foundation

- Identify a publication/product that needs taking through RAP process
- Identify people in the publication team who will learn RAP process (PO and min 2 analysts)
- Identify people in the RAP team, or those familiar with RAP practices, to support the publication team through RAP transition
- Set up a Jira board for tracking work and confluence space for documenting learning, agreed decisions
- Teams meet and ice breaker session to get to know each other. Set out the plan for the engagement, review roles and responsibilities, lessons learned from previous projects, etc.

## Getting stuck in

- Pair up analysts from publication and RAP teams. These coding buddies will work collaboratively for the rest of the project.
- Identify the ['thin slice'][3] of the publication that we will aim to replicate in the first phase.
- Identify training needs of the publication team through conversations
- Dedicated training. The content is tailored to the specific team but a typical sequence might look like:

  - [Concept of a thin slice and how to choose the thin slice][3]
  - Access to off-the-shelf interactive training for self-led training
  - [PySpark style guide][4]
  - [Version control][5]
  - [Writing good functions][6]
  - [Unit tests][7]

- Buddy pairs work to replicate the thin slide outputs
- Set up automated code testing once the numbers are correct
- Group code review of buddy pair code as a learning exercise
- Decide how to structure code for publication as a whole
- Portion out the rest of the publication to be replicated i.e. geographical breakdowns
- Each analyst takes a portion at a time working independently to produce using RAP standards seeking buddy support as needed
- Set up QA and RS checks pre-publication

## Being transparent

- Publish code on github
- Add a link to the code repository in the publication and a link to the publication in the code repository
- Show and tell on what we have learned, documents added to github

## Close-down

- Review the codebase to confirm that all the elements of baseline RAP (or silver/gold) have been met.
- Reflect on the resources and materials available throughout the process and suggest improvements or additions.
- Do a user-research session with the RAP team to suggest improvements to the service for those who come later.
- Take some time to reflect on the process internally as a team and consider how you plan to take forward the work.

[1]: ./support-models.md
[2]: ../introduction_to_RAP/levels_of_RAP.md
[3]: ./thin-slice-strategy.md
[4]: ../training_resources/pyspark/pyspark-style-guide.md
[5]: ../training_resources/git/using-git-collaboratively.md
[6]: ../training_resources/python/python-functions.md
[7]: ../training_resources/python/unit-testing.md
