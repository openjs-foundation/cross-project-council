# Node.js Membership Travel Fund

## Purpose

To establish and administer a fund for members of the Node.js Foundation to travel and spread knowledge about and support Node.js 
ecosystem and the Foundation. 

### [Current Year Fund](https://github.com/nodejs/admin/blob/master/TravelFunds/2019.md)

### [2018 funds](https://github.com/nodejs/admin/blob/master/TravelFunds/2018.md)

## Requirements

* Candidates must be an individual member of the Node.js Foundation. [The membership status can be checked on the foundation website](https://identity.linuxfoundation.org/user/login?destination=user/me). Due to privacy, the Individual Members list is not public. 
This team will verify the requester is on the Individual Members list before funds are disbursed.
  * Exception: For the Collaborator Summits, members of JS Foundation
    projects may submit funding requests.
* Those requesting funds must indicate that they do not have funding available from another source, such as an employer or 
the event itself that might cover costs for presenters.

## Process

Requests must be made prior to the start of travel. Requests submitted once travel is complete will not be approved. 

It is strongly recommended that you submit your request far enough in advance to get approval before making relevant expenditures. 
Review of requests will take at least 72 hours and may take considerably longer. Note, with limited funds available, approval is not 
guaranteed. If a request is rejected, reimbursement will not be issued.The Foundation cannot pre-pay for travel expenditures. 
It is recommended to write a report after the trip.

## Visa Tips

For all events, 3rd party or hosted Foundation events, it is recommended to apply for a visa at least 6 months prior to an event. 

### For Industry Events 

If you need a visa for the country in which the Node.js event you are attending is being held, 
[see the document on preparing for a visa application](https://github.com/nodejs/admin/blob/master/travel-visas.md). 

### What The Foundation Can Do To Help: 

The Foundation [provides guidance on preparing your visa application](https://github.com/nodejs/admin/blob/master/travel-visas.md), 
including information on visa processing times and a checklist of items that a visa application could require.

For Foundation-hosted events, Node.js Foundation provides a visa letter by The Linux Foundation (does not guarantee visa approval). 
Click [here](https://events.linuxfoundation.org/events/node-js-interactive-2018/attend/visa-request/) to request a visa letter.

### What the Foundation Cannot Do: 

Please note that unless the Foundation is specifically hosting the event, we cannot help with visa letters. 
The Foundation is also not able to contact consulates. When the Foundation has done this in the past, our efforts have been unsuccessful 
and/or we’ve lacked the expertise to be effective.  

For additional information on preparing your visa application or requesting a visa letter, please email 
[visainfo@nodejs.org](mailto:visainfo@nodejs.org).

## Requesting Travel Funds 

* Open a pull request that adds an entry to the appropriate year's file
  * Include as many fields as possible:
    * The name of the event you plan to attend.
    * The location, dates of the event and where you will be traveling from.
    * The presentation you intend to give, if applicable.
    * The size of the stipend you wish to receive.
      * In the pull request description, explain how you calculated your
        stipend. For example, include estimates for airfare, hotel, other
        transportation, and so on. The total amount should be your stipend
        request.
      * In the PR description, mention @nodejs/tsc and @nodejs/community-committee.
    * Once the final amount spent is known, update the table again with that information.
    * Certain details of your request (such as the column for date sent to finance) may be unknown initially; these can be filled in and updated during the process of reconciliation.

## Approval

A request is approved when all of the following criteria are met:

* The pull request has been open for at least 72 hours.
* The request has approval from at least two members of @nodejs/tsc and two members of @nodejs/community-committee. 
(People who are members of both committees may only be counted for one or the other. 
Therefore, any request will always require at least four approvals.)
* No members of either @nodejs/tsc or @nodejs/community-committee have objected to the request.
* The pull request has been merged. Any member may merge once other prerequisites have been met.

If a request is blocked by an objection from a member of @nodejs/tsc or @nodejs/community-committee, then the only way for the request 
to be approved is for that committee to decide to approve the request using whatever decision-making process the committee uses when 
consensus is not reached. (For example, for the TSC, there is a voting process to make decisions when consensus cannot be reached.)

An appointed treasurer from either the @nodejs/tsc or @nodejs/community-committee (or both) will liaise with a member of 
the Node.js Foundation on a regular basis to review the status of the travel fund. In the event that any pending 
requests might not be approved because of available funds, a separate issue will be raised. Generally speaking, however, 
members shouldn't need to worry about the status of the fund itself.

As examples, the purpose of prior sponsored travels includes attending TC39 meetings, 
attending [Node.js collaboration summits](https://github.com/nodejs/summit), and 
mentoring [Code and Learn](https://github.com/nodejs/code-and-learn).

### Considerations for approval of a request

#### Impact
* Preference is given to events hosted or sponsored by the Node.js Foundation. For example, 
Node.js collaboration summits and Diagnostics summits should be given precedence because they bring together members of the 
Foundation to help the Foundation projects advance. 
* Preference is given to speakers and panelists of a conference. Speaking and doing panels at a conference generates a more 
significant impact than attending. However, individuals applying for the travel fund to speak or participate in panels should confirm 
that the event organizers cannot cover the travel expenses before submitting a request.

#### Outreach
* Preference is given to underserved communities. More specifically, within a subject the foundation is trying to promote awareness 
about (e.g. general knowledge about the foundation) there are people, communities, and geographies where that knowledge is not very 
widespread. This is where preference will be given. For instance, an event in San Francisco would be less attractive than an event of 
the same size in Kansas City.

#### Cost
* The larger the stipend the more critically the travel fund admins will consider the request and application. 
The budget for this program is a finite resource.

#### Equity
* Preference is given to individuals who cannot receive travel funding from their employers or individuals who have not 
previously received a stipend.

## Reimbursement

So that we can reimburse you more quickly, we strongly encourage you to use
[Expensify](https://expensify.com) to organize and submit your receipts.  Please
see our [guide to creating and configuring a free Expensify
account](./reimbursement_process.pdf).

Here are the highlights of the process:

* A free [Expensify](https://www.expensify.com/) account is sufficient.
* You can use the Android and iOS apps to capture receipts while you are
  traveling.  If you do not use the app, you will need to upload photos of your
  receipts after you return.
* When you add an expense, please use local currency so that it matches the
  amount on the receipt.
* Once you have uploaded your receipts, please add them to a report and submit
  it with [operations@openjsf.org](mailto:operations@openjsf.org) on cc, and the
  Memo field set to "YOURNAME - TRIPNAME".

When we receive your report, we will send you a form via DocuSign to collect
your payment details.  At that point, you're done.

### Alternate process

If you decide not to use Expensify, the reimbursement process is manual and may
take longer for us to process.  You can email a zip file of your receipts and
the completed [Expense Report](./expense-report-template.xls?raw=true), renamed
as ExpenseReport-OpenJS-EVENTNAME-YOURNAME-YYYYMM.xls, to
[operations@openjsf.org](mailto:operations@openjsf.org).  Please send the file
as a spreadsheet, not as a PDF.  We will send it back to you for signature in
DocuSign.

### Important:

* Expense reports must be submitted within 30 days of event date. Any reports submitted after 30 days may not be reimbursed.
* Disbursements are generally processed within 30 days. 
* We are unable to pre-pay for expenses. 
* Due to privacy, the Individual Members list is not public. This team will verify the requester is on the Individual Members list before funds are disbursed. The community manager or a member of the Node.js Foundation team within the Linux Foundation will report 
back amounts consumed from the travel allocation on a monthly basis to the Chairs. A member of the Node.js Foundation team within the Linux Foundation will report monthly on travel funds allocated to the Chairs.

## Trip report

After the trip, it's recommend to write a report, and add a link in the document
that contains their request. The report may include topics such as:

1. Purpose of this travel.
2. Sessions and/or talks they attended and/or gave, and a summary of those.
3. Conversations that they think are appropriate to document in a public space
  (with consent from other indivisuals involved in the coversation).
4. What they have achieved in the events, e.g. if they have written code
   or done other work for the project in the event with the others, or if
   they have collected useful feedback from the community.
5. Future work items that come out of the event.

## 2018 Board of Directors Allocation
The request from Technical Steering Committee and the Community Committee for a 2018 joint travel fund was 
approved in the amount of $60,000. The $60,000 was fully utilized in 2018. 

## 2019 Board of Directors Allocation

The request from Technical Steering Committee and the Community Committee for a 2019 joint travel fund 
was approved in the amount of $60,000. 

Please direct any questions or concerns about the travel fund to [travelapprovals@nodejs.org](mailto:travelapprovals@nodejs.org). 
