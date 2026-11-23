# Find a case by the work you do

Start with a decision you recognize. Each case uses fictional records you can inspect before you act. After you try it, the sponsor question gives you a way to judge whether the proposed change would earn its keep.

**Operations and finance**

- [Buying parts for production](#buying-parts-for-production) · Agentic Process Safety
- [Answering a customer about a shipment](#answering-a-customer-about-a-shipment) · Commerce Reliability Kit
- [Handing a safety repair to the next shift](#handing-a-safety-repair-to-the-next-shift) · Autonomous EHS Management
- [Checking a change to the leave portal](#checking-a-change-to-the-leave-portal) · HR ERP
- [Timing payments ahead of a funding meeting](#timing-payments-ahead-of-a-funding-meeting) · Financial Digital Twin
- [Preparing a client invoice](#preparing-a-client-invoice) · Professional Service Automation

**Healthcare and exchange operations**

- [Tracking a specialist’s reply](#tracking-a-specialists-reply) · Asclepius
- [Choosing what a study team may receive](#choosing-what-a-study-team-may-receive) · Healthcare Data Exchange
- [Verifying a withdrawal at the gateway](#verifying-a-withdrawal-at-the-gateway) · healthcare-policy

**Platforms and assurance**

- [Coordinating a customer credit across teams](#coordinating-a-customer-credit-across-teams) · CorpOS
- [Answering a customer about release approval](#answering-a-customer-about-release-approval) · SOC-2
- [Investigating a disputed tool decision](#investigating-a-disputed-tool-decision) · FidusGate

[Reviewing a changed release artifact](#reviewing-a-changed-release-artifact) is a written case from the archived Corporate/Site Harness.

A **Published demo** runs in a browser. A **Review preview** is a browser build of the version awaiting review. Each preview includes its own technical guide. A **Draft PR** opens the GitHub change for review. The opening views below show the version described in each entry.

## Buying parts for production

**Agentic Process Safety.** A buyer needs 24 bearings for Thursday’s assembly. Finance approved the spend, but stock, quote validity and the age of that approval can change while the order waits. A late order can stop the line. A second order can leave the plant paying twice.

**Your decision.** What should the purchasing agent be allowed to do when it reaches the supplier with that approval?

**Who would fund it?** The supply-chain lead can compare a rule in the purchasing system with a four-week agent pilot running alongside it. Which catches stale orders, and how much buyer time does each take?

[Published demo](https://safetymp.github.io/Agentic-Process-Safety/#/study) · [Published technical guide](https://safetymp.github.io/Agentic-Process-Safety/#/overview?age=60&quote=13%3A55&stock=unknown&trial=15) · [Opening view — The bearing order from purchase approval to the assembly line](demo-previews/Agentic-Process-Safety.jpg)

## Answering a customer about a shipment

**Commerce Reliability Kit.** Mina needs five lamps for her café’s opening night. North Quay sent one shipping notice. Jo at the service desk can see the order, but the packing crew recorded what went into the carton. Calling the bench takes a packer away from the next order.

**Your decision.** What can Jo tell Mina in time for her to arrange a pickup?

**Who would fund it?** The merchant operations lead can compare manual checks with a test of the checkout-to-packing connection. Count calls avoided and promises the packing evidence could actually support.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/commerce-reliability-kit/index.html) · [Draft PR](https://github.com/SafetyMP/commerce-reliability-kit/pull/6) · [Opening view — How checkout, packing and support see the same order](demo-previews/commerce-reliability-kit.jpg)

The published desk uses an unnamed shop’s partial shipment. [Published demo](https://safetymp.github.io/commerce-reliability-kit/) · [Published technical guide](https://safetymp.github.io/commerce-reliability-kit/#technical?packet=faulty&stage=capture&trial=reconciled)

## Handing a safety repair to the next shift

**Autonomous EHS Management.** After a conveyor near miss, maintenance installs a guard. Maya owns the corrective action. Alex, the safety reviewer, needs observations from people who worked the line. A closed work order tells the next shift little about how the guard performs under load.

**Your decision.** Which shift evidence would you hand Alex before asking for a closure decision? Practice gathering observations on a dock walk, then open Maya’s conveyor file.

**Who would fund it?** The plant manager can compare email, a tracker and a shared action record. Can another shift verify the evidence without sending Maya back to the floor?

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/Autonomous-EHS-Management/index.html) · [Draft PR](https://github.com/SafetyMP/Autonomous-EHS-Management/pull/171) · [Opening view — A conveyor repair crosses a shift change](demo-previews/Autonomous-EHS-Management.jpg)

The published case opens at the conveyor evidence packets. [Published demo](https://safetymp.github.io/Autonomous-EHS-Management/) · [Published technical guide](https://safetymp.github.io/Autonomous-EHS-Management/#/technical)

## Checking a change to the leave portal

**HR ERP.** Alex wants eight hours off. The manager plans shift coverage and Alex plans around the balance in the portal. QA has two revisions of a change to that balance. If the portal deducts a day too soon, Alex might cancel plans and HR must reconstruct what happened.

**Your decision.** Which request states would you test before recommending a release to the HR systems owner?

**Who would fund it?** The HR technology owner can compare a reviewer checklist, a balance regression test and a broader test pilot. Track missed balance defects alongside review time.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/HR-ERP/index.html) · [Draft PR](https://github.com/SafetyMP/HR-ERP/pull/243) · [Opening view — The same day off as seen by the employee, manager and HR](demo-previews/HR-ERP.jpg)

The published version opens at Alex’s balance review. [Published demo](https://safetymp.github.io/HR-ERP/) · [Published technical guide](https://safetymp.github.io/HR-ERP/#/technical?revision=A&state=Approved&run=A-approved)

## Timing payments ahead of a funding meeting

**Financial Digital Twin.** At Northstar, a dollar transfer has been delayed. A customer payment file and a clearinghouse call on the same cash. Treasury must give a release instruction before the funding meeting. Someone who is paid late must wait even if the day ends with enough money.

**Your decision.** When would you release the customer batch? Replay the timing to see which obligations settle by their deadlines. A separate euro case lets an independent risk reviewer challenge a 30-day liquidity figure.

**Who would fund it?** The CFO can test whether a shared review file saves time and lets a second reviewer trace the figures to the same source and date.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/Financial-Digital-Twin-Compliance/index.html) · [Draft PR](https://github.com/SafetyMP/Financial-Digital-Twin-Compliance/pull/280) · [Opening view — Northstar’s treasury and risk teams prepare for their funding meeting](demo-previews/Financial-Digital-Twin-Compliance.jpg)

The published version opens at the euro liquidity alert. [Published demo](https://safetymp.github.io/Financial-Digital-Twin-Compliance/) · [Published technical guide](https://safetymp.github.io/Financial-Digital-Twin-Compliance/workspace/)

## Preparing a client invoice

**Professional Service Automation.** A warehouse client agreed to pay a consulting team $60,000 in stages for a redesign. On Friday the delivery manager has a fresh sign-off. The project accountant already has an issued invoice and a $6,000 draft. The client’s payables clerk needs a purchase order to match the bill.

**Your decision.** Looking at the signed work, the invoice register and the client reference, would you issue, hold or cancel the draft? Try another choice on the same Friday.

**Who would fund it?** The finance partner can compare the workbook, a draft register and a parallel billing pilot. Count review time and corrections on the same projects.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/Professional-Service-Automation/index.html) · [Draft PR](https://github.com/SafetyMP/Professional-Service-Automation/pull/110) · [Opening view — Delivery, finance and client payables prepare for Friday billing](demo-previews/Professional-Service-Automation.jpg)

The default-branch application requires local setup. [Source and setup](https://github.com/SafetyMP/Professional-Service-Automation#quick-start)

## Tracking a specialist’s reply

**Asclepius.** Maya is waiting for Willow to call after her visit. Willow asked Cedar’s specialist to send a written report. Cedar also has an earlier referral for Maya. Willow’s coordinator keeps a list for the next shift. Filing the wrong letter could stop follow-up too soon. Overlooking the right one sends both clinics chasing paperwork.

**Your decision.** Does this letter answer Willow’s open request? Compare it with the other letter before marking a report received. A clinician still owns review of the report and Maya’s care.

**Who would fund it?** The education lead can compare a mentor walkthrough, a one-page guide and a practice exercise. Can learners explain a new referral a week later, and how much instructor time did it take?

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/Asclepius/index.html) · [Draft PR](https://github.com/SafetyMP/Asclepius/pull/104) · [Opening view — Willow sends Maya’s request to Cedar and waits for a specialist’s letter](demo-previews/Asclepius.jpg)

The published version opens at Willow’s report-receipt decision. [Published demo](https://safetymp.github.io/Asclepius/) · [Published technical guide](https://safetymp.github.io/Asclepius/workspace/)

## Choosing what a study team may receive

**Healthcare Data Exchange.** One row on a study roster has Anna’s record ID. The study coordinator wants a birth date to check an age requirement. The exchange data steward can inspect the requester, purpose, consent and fields. An unnecessary hold sends two teams back to the roster. An overly broad packet exposes more of Anna’s record.

**Your decision.** Which fields, if any, would you prepare for this requester? See what the coordinator could do with each packet. The study team decides eligibility.

**Who would fund it?** The exchange operations director can compare manual reviews with a checklist or a rules-assisted pilot. Sample both excess disclosures and authorized requests held up.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/Healthcare-Data-Exchange/index.html) · [Draft PR](https://github.com/SafetyMP/Healthcare-Data-Exchange/pull/186) · [Opening view — The steward’s desk and the open row on Anna’s study roster](demo-previews/Healthcare-Data-Exchange.jpg)

The published version opens at the privacy desk intake. [Published demo](https://safetymp.github.io/Healthcare-Data-Exchange/#research-request) · [Published technical guide](https://safetymp.github.io/Healthcare-Data-Exchange/#technical/research/withheld/receiver/selected)

## Verifying a withdrawal at the gateway

**healthcare-policy.** Anna has withdrawn permission for research. The steward recorded her choice. The same team may try again, and the privacy officer wants to know what the gateway will do. Its access rule and its copy of Anna’s consent can arrive separately. A premature assurance puts Anna’s privacy at risk. An unnecessary blanket hold delays other work.

**Your decision.** Can you confirm the next matching read will be denied here, or does someone still need to verify it? Inspect the receiving gateway’s record, then try the other shift file.

**Who would fund it?** The exchange operations director can weigh independent rule releases against the cost of maintaining distribution and verifying receipt. The exchange owns the rule and the companion repository mirrors it.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/healthcare-policy/index.html) · [Draft PR](https://github.com/SafetyMP/healthcare-policy/pull/16) · [Draft PR for the shared operator interface](https://github.com/SafetyMP/Healthcare-Data-Exchange/pull/186) · [Opening view — The access rule and Anna’s withdrawal take separate paths to the gateway](demo-previews/healthcare-policy.jpg)

The published exchange has a rule-publication trace. The operator decision is awaiting publication. [Published rule-publication trace](https://safetymp.github.io/Healthcare-Data-Exchange/#policy-provenance)

## Coordinating a customer credit across teams

**CorpOS.** Ada reports a missing $49 credit. Support sees her statement, Finance sees the ledger and the on-call engineer can check the billing service shared by every account. A second refund could pay Ada twice. An unnecessary restart could disrupt other customers.

**Your decision.** As platform lead, which handoff would you authorize after comparing Ada’s account with the service observations?

**Who would fund it?** The platform engineering lead can compare the ticket queue, a handoff checklist and a shadow pilot. Time how long it takes the next person to find the owner and authority for each action.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/CorpOS/index.html) · [Draft PR](https://github.com/SafetyMP/CorpOS/pull/98) · [Opening view — Support, finance and operations each see one part of Ada’s credit](demo-previews/CorpOS.jpg)

The published version opens at the billing restart handoff. [Published demo](https://safetymp.github.io/CorpOS/) · [Published technical guide](https://safetymp.github.io/CorpOS/#guide)

## Answering a customer about release approval

**SOC-2.** Eastbank uses Cedarline’s software to route deliveries from one depot. Before adding two more depots on Friday, Alex asks who checked the June update. Priya, Cedarline’s compliance lead, has repository settings and can request release records. A weak answer leaves the customer guessing about the next update.

**Your decision.** Which records would let Priya answer Alex about that particular release? Open the June record and decide what else to request.

**Who would fund it?** The compliance lead can measure whether collecting settings locally saves engineering time on repeated requests. A CPA performs the independent SOC 2 examination.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/SOC-2/index.html) · [Draft PR](https://github.com/SafetyMP/SOC-2/pull/32) · [Opening view — Eastbank considers expanding dispatch software from one depot to three](demo-previews/SOC-2.jpg)

The published version opens at the release-approval evidence desk. [Published demo](https://safetymp.github.io/SOC-2/#case) · [Published technical guide](https://safetymp.github.io/SOC-2/#technical)

## Investigating a disputed tool decision

**FidusGate.** Harbor Dispatch has a fix for duplicate appointments. While preparing it, a coding assistant requested an edit to its permissions file. Maya, the release lead, has a forwarded decision. Platform security has the archive. Dispatchers are calling crews by hand while the release waits.

**Your decision.** What can Maya put in the change ticket from the forwarded copy, the signed receipt and the file history?

**Who would fund it?** The platform security lead can compare a standard log export with a signed-receipt pilot. Count investigation time and the work of managing trusted signing keys.

[Review preview](https://raw.githack.com/SafetyMP/SafetyMP/30a6bb848cd29f30183e37206587366b98dbf6d7/docs/review-builds/FidusGate/index.html) · [Draft PR](https://github.com/SafetyMP/FidusGate/pull/181) · [Opening view — Maya’s ticket and the customer fix waiting on the investigation](demo-previews/FidusGate.jpg)

The published version opens at a disputed tool decision. [Published demo](https://safetymp.github.io/FidusGate/#/case) · [Published technical guide](https://safetymp.github.io/FidusGate/#/technical?packet=received&fixture=FG-1048&stage=signature)

## Reviewing a changed release artifact

**Corporate/Site Harness · archived written case.** A site release passed verification, then a developer changed the deliverable. The release reviewer has a record for the first version and a candidate for the second. Approving the wrong artifact could send an unverified change to the site. Does the existing evidence cover the file the team wants to ship?

**Who would fund it?** A release engineering lead can time the checks and see whether reviewers spot the substitution. At six minutes saved on each of 30 packets a month, the team recovers three hours. Two hours of monthly upkeep leave one hour toward a twelve-hour setup. At 20 packets, the time savings only cover upkeep. Those are illustrative assumptions a team can replace with its own. [Read the archived workflow](https://github.com/SafetyMP/corporate-site-harness/blob/main/docs/HOW_IT_WORKS.md)

[Portfolio home](../README.md) · [Publication and source notes](portfolio-sources.md)
