# Updating process for Stream data standards

The update process for Stream data standards was agreed by all participants at the third Stream Data Standards Workstream meeting on 15th January 2024.

## Changes provided via Pull Requests (PR)

It was agreed that changes would be suggested using the [GitHub Pull Request (PR)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) tooling. 

PRs are used in a GitHub repository to suggest changes for the content within that repository.

A PR will be created for every change once the Data Standards are agreed.

## Allowing changes from outside Stream

It was agreed that the repository would allow and actively encourage PRs to be generated from external repositories rather than via changes to the repository directly.

This decision provides for organisations and people external to Stream who want to suggest changes to be able to do so.

## Adapt and adopt the GOV.UK "Merge a Pull Request" process

It was agreed that Stream would adapt and adopt the "Merge a Pull Request" process outlined at [https://docs.publishing.service.gov.uk/manual/merge-pr.html](https://docs.publishing.service.gov.uk/manual/merge-pr.html).

### Stream process for merging a pull request

1. The `main` branch is the current version of the Stream data standards adopted<sup>[\[1\]](#process-ref-1)</sup> by the Stream Steering Group (SG) - [link to `main` branch (Steering Group approved)](https://github.com/icebreakerone/stream-data-standards/)
2. The `recommended` branch is the version of Stream data standards approved<sup>[\[1\]](#process-ref-1)</sup> by the Stream Technology Advisory Group (AG) - [link to `recommended` branch (Advisory Group approved)](https://github.com/icebreakerone/stream-data-standards/tree/recommended)
3. The `working` branch is where the next version of the data standards is worked on - [link to `working` branch](https://github.com/icebreakerone/stream-data-standards/tree/working)
4. GitHub Pull requests (PRs) are the change request process used to manage updates.
5. Changes to the data standards will be provided via a PR to the `working` branch.
6. Any PRs not merging to the `working` branch will be rejected.
7. Any PR must have at least 1 review from repository administrators before being merged onto the `working` branch. 
8. To ensure that there is a separation of duties a PR into the `working` branch should not be accepted by the person who created the PR or anyone from their organisation. If a change is accepted and promoted by the same individual or organisation due to necessity or a lack of reviewers being available, this should be highlighted in the PR so that the AG review process is fully aware.
9. The GitHub review UI should be used to discuss changes, mark a PR as approved or requiring changes<sup>[\[2\]](#process-ref-2)</sup>
10. The GitHub UI should be used to merge the PR<sup>[\[2\]](#process-ref-2)</sup>
11. Before an AG meeting, if there are accepted PRs/changes to the `working` branch, a new PR to promote that version of the `working` branch to the `recommended` branch will be created.
12. The AG should review the changes and will approve or reject the changes.
13. If there is an approval for the `working` changes in the AG, the `recommended` branch will be updated to that version, and a PR to promote the new `recommended` branch to the `main` branch will be created.
14. The SG will be notified of the changes, and if there are no objections, the change will be accepted at the next meeting.

<sup><a name="process-ref-1">[1]</a></sup>
The process of approval and adoption, e.g. a formal vote or acceptance if there are no objections or similar, is at the discretion of the AG and SG respectively. If no definite decision is recorded but the changes have been provided to an AG or SG meeting, the changes will be deemed to have been accepted.

<sup><a name="process-ref-2">[2]</a></sup>
The Stream data standards GitHub PR review interface is: [https://github.com/icebreakerone/stream-data-standards/pulls](https://github.com/icebreakerone/stream-data-standards/pulls).

A visual representation of the repository branching, PR, and review process is shown here:

![Overview of Stream data standards change process](./assets/change-process.png)

## Repository administrators

It was agreed that the Stream Advisory Group responsible for technology would have the authority to name and manage those who are responsible for managing and accepting Pull Requests and those who are repository administration.

The repository administrators will also be agreed by the Advisory Group.

It is expected that the Advisory Group will assess the technical expertise and/or water industry knowledge of these individuals so that they will be able to understand and accept any change requests.
