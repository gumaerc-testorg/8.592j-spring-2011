---
content_type: page
description: This section provides a lecture outline on sequence alignment with links
  to related materials and detailed lecture notes.
draft: false
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
parent_title: Lecture Notes
parent_type: CourseSection
parent_uid: 9e7f1aa8-38db-6648-8063-791ee60d518e
title: Significance of Alignments
uid: 11af0f00-dc54-78ce-d85a-e3567d5d0eb2
video_metadata:
  youtube_id: null
---
1. {{% resource_link "0b4795ff-a6e6-4dd1-a515-384c504cbb09" "Sequence alignment" %}}
    - Inputs:
        - *Explicit*—Two sequences {a1, a2, …., am} and {b1, b2, …., bn} (e.g. query and database)
        - *Implicit*—A scoring procedure, e.g. pairwise scores s(ai,bj) and gap costs
    - Alignment algorithm: global, local, gapped, gapless (dynamic programming, applet)
    - Output: matching (sub)sequences with an overall score S . ({{% resource_link "49bf0c8d-6b0f-48b7-b13b-32168eb6e5c0" "example" %}})
    - Significance: What is the probability of getting a score S by chance?
2. Statistics of gapless local alignments:
    - Random walks of scores as a function of matching length
    - {{% resource_link "8e742a8a-645b-4c41-8589-5c712a2c882f" "Extreme Value Distributions" %}}, the {{% resource_link "98aff4b8-cece-43de-8dc3-9e9949b98275" "Gumbel distribution" %}}
    - Tails of distribution in a {{% resource_link "1d43db65-299f-476e-a620-0b029765a5e2" "gapless alignment" %}}
    - The Karlin-Dembo formula
3. Gapped alignments and Statistical Physics
    - Transfer Matrix method for {{% resource_link "2beac425-7fb3-4a1e-9e14-bbfd495262fa" "Directed Paths in Random Media (PDF)" %}}

- {{% resource_link "612ad719-0a46-4e2f-b03e-6972dbb1f6e9" "Tutorial by Ralf Bundschuh" %}} on Sequence Alignment (and {{% resource_link "94bcdcd6-a742-490b-8abf-71044edc69bf" "associated paper" %}})

({{% resource_link "7432aff1-a1e8-4331-5134-3a618946f2e3" "Detailed Lecture Notes (PDF)" %}})