 wiredpeers — Manager Guide @page { size: A4; margin: 18mm 16mm; } html, body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; color: #1f2937; font-size: 11pt; line-height: 1.5; } body { margin: 0; } h1 { font-size: 26pt; margin: 0 0 4pt; color: #111827; } h2 { font-size: 16pt; margin: 22pt 0 6pt; color: #111827; border-bottom: 1pt solid #e5e7eb; padding-bottom: 3pt; page-break-after: avoid; } h3 { font-size: 12pt; margin: 12pt 0 4pt; color: #111827; page-break-after: avoid; } p { margin: 4pt 0; } ul, ol { margin: 4pt 0 6pt 18pt; padding: 0; } li { margin: 2pt 0; } .subtitle { color: #6b7280; font-size: 11pt; margin-bottom: 14pt; } .cover { display: flex; align-items: center; gap: 14pt; padding: 0 0 10pt; border-bottom: 2pt solid #7c3aed; } .cover-logo { width: 56pt; height: 56pt; color: #7c3aed; flex: 0 0 auto; } .cover-text { flex: 1; } .cover h1 { font-size: 26pt; margin: 0 0 2pt; color: #111827; line-height: 1; } .cover .brandline { color: #6b7280; font-size: 9pt; letter-spacing: 0.4pt; text-transform: uppercase; margin-bottom: 4pt; } .cover .role { display: inline-block; background: #f5f3ff; color: #6d28d9; font-size: 9pt; font-weight: 600; padding: 2pt 8pt; border-radius: 999px; margin-top: 4pt; } .toc { background: #f9fafb; border: 1pt solid #e5e7eb; border-radius: 4pt; padding: 10pt 14pt; margin: 14pt 0 18pt; } .toc ol { margin: 4pt 0 0 18pt; } .tip { background: #ecfdf5; border-left: 3pt solid #10b981; padding: 6pt 10pt; margin: 6pt 0; font-size: 10pt; border-radius: 0 4pt 4pt 0; } .note { background: #fff7ed; border-left: 3pt solid #f59e0b; padding: 6pt 10pt; margin: 6pt 0; font-size: 10pt; border-radius: 0 4pt 4pt 0; } .warn { background: #fef2f2; border-left: 3pt solid #ef4444; padding: 6pt 10pt; margin: 6pt 0; font-size: 10pt; border-radius: 0 4pt 4pt 0; } code { background: #f3f4f6; padding: 1pt 4pt; border-radius: 3pt; font-size: 10pt; } .module { page-break-inside: avoid; } figure { margin: 14pt auto; max-width: 360pt; text-align: center; page-break-inside: avoid; } figure svg { display: block; width: 100%; height: auto; border: 1pt solid #e5e7eb; border-radius: 6pt; background: #ffffff; box-shadow: 0 1pt 2pt rgba(15, 23, 42, 0.04); } figcaption { font-size: 9pt; color: #6b7280; margin-top: 6pt; font-style: italic; line-height: 1.4; } footer { margin-top: 24pt; padding-top: 8pt; border-top: 1pt solid #e5e7eb; color: #6b7280; font-size: 9pt; text-align: center; } table { width: 100%; border-collapse: collapse; margin: 8pt 0; font-size: 10pt; } th, td { border: 1pt solid #e5e7eb; padding: 5pt 8pt; text-align: left; vertical-align: top; } th { background: #f9fafb; font-weight: 600; } strong { color: #111827; }

a product of xelerate.tech

wiredpeers
==========

Manager Guide — running expenses and performance for your team

For managers

**Contents**

1.  What's different for managers
2.  Expenses — approving your team's spend
3.  Expenses — events & oversight
4.  Performance — your team at a glance
5.  Performance — running a review for a report
6.  Goals & 1:1 feedback
7.  Tickets — raising and working tickets
8.  Day-to-day checklist
9.  Tips & troubleshooting

1\. What's different for managers
---------------------------------

As a manager you keep everything an employee does (your own goals, feedback, expenses, tickets) and gain two extra responsibilities:

*   **Expense approvals** for the people who report to you.
*   **Performance oversight** — viewing each report's goals, feedback, and progress in a cycle, and initiating reviews on their behalf.

The app surfaces these in two new places:

*   A **Pending Approvals** tab inside **Expenses**, with a red counter badge in the sidebar when items are waiting.
*   A **My Team** section in the sidebar (list and tree views of your direct and indirect reports).

wiredpeers Dashboard Goals Feedback My Team Expenses 3 Tickets New for managers: • My Team — direct reports • Pending badge on Expenses • Approve / Reject actions inside each expense • Feedback toolbar on each report

The sidebar gains a _My Team_ entry and a counter on Expenses when approvals are pending.

2\. Expenses — approving your team's spend
------------------------------------------

### Where to find pending approvals

1.  Open **Expenses** from the sidebar.
2.  Click the **Pending Approvals** tab (its badge shows the number waiting on you).
3.  Approvals are grouped by **event** (a trip, project, off-site, etc.) so you can review related expenses together.
4.  Use the search box to filter by description.

### Review and decide

1.  Click a row to open the full expense detail.
2.  Check the **amount**, **category**, **description**, and the attached **receipt**.
3.  Click **Approve** to send it on for reimbursement, or **Reject** to push it back.
4.  If you reject, you **must give a reason** — that text is shown to the employee so they can correct and resubmit.

For Portuguese invoices, the submit form already validates the buyer NIF against the event company's NIF when a photo is taken — so an expense that made it to your queue with a mismatched NIF means the employee uploaded a PDF (which isn't scanned) or the QR couldn't be read. Double-check those manually.

Expense · Train ticket to client office Submitted by Alex Rivera · May 18, 2026 Event Client visit — Lisbon, May 2026 Category Transport Amount €42.50 Description Train ticket to client office, return same day. 📄 receipt.pdf Reject Approve

Expense detail with manager actions. Rejection opens a small dialog asking for a reason.

Only the **direct manager** of the submitter can approve or reject. If you think you should be able to act on an expense and can't, check the org hierarchy with Admin.

### What happens after you decide

Status

Meaning

Visible to

Submitted

Waiting for your decision.

You + finance

Approved

Goes to finance for reimbursement.

Submitter, you, finance

Rejected

Closed; your reason is shown.

Submitter, you

Reimbursed

Finance has paid out.

Submitter, you, finance

3\. Expenses — events & oversight
---------------------------------

Events group related expenses (a trip, a conference, a client engagement). Managers and admins can **create events** so the team has somewhere to file their expenses against.

### Create an event

1.  Open **Expenses** → **Events**.
2.  Click **New Event**.
3.  Give it a name, dates, and any default category restrictions.
4.  Save. Your team can now select it when submitting expenses.

### Review spend per event

*   Open any event from the Events tab to see the full list of expenses filed against it, their total, and per-status breakdown.
*   You can **approve / reject** from inside the event view too, useful for clearing a whole trip's expenses in one pass.

When you're about to travel as a team, create the event first and share its name — it saves everyone time at submission.

4\. Performance — your team at a glance
---------------------------------------

**My Team** is your control room for performance.

### List view

*   One card per direct report with their name, role, and a quick summary for the selected cycle.
*   Use the **cycle dropdown** at the top to switch between cycles (e.g. Q1 2026, Q2 2026).
*   Click a card to open the report's detail page.

### Tree view

*   Shows the full org tree under you (direct + indirect reports).
*   Useful for skip-level visibility and understanding how the team is structured.

My Team Cycle: Q2 2026 ▾ AR Alex Rivera Senior Engineer Goals 3 / 4 ✓ Feedback received 5 Self-review Done MS Maria Silva Designer Goals 2 / 3 Feedback received 2 Self-review Pending TP Tom Pereira PM Goals 4 / 4 ✓ Feedback received 6 Self-review Done

List view of your direct reports for a chosen cycle. Click a card to drill in.

5\. Performance — running a review for a report
-----------------------------------------------

Opening a report shows everything you need to do a fair, well-informed review.

### What you see on a report's page

*   **Profile** — name, role, manager line.
*   **Goals tab** — every goal for the selected cycle with status & notes.
*   **Feedback received** — peer and self-assessment entries, with the right visibility rules.
*   **Pending / completed requests** — what's still owed in this cycle.
*   **Manager Actions toolbar** at the top with three buttons.

### The Manager Actions toolbar

1.  **Give Feedback** — open the feedback form for this report (uses the manager form configured for the cycle). You can mark your feedback as visible to the report if you want to share it.
2.  **Request Peer Feedback** — pick peers and a form; they'll receive the request and a notification (used in standard cycles).
3.  **Request 1:1 Feedback** — quick continuous-feedback request, useful outside a formal cycle (used in continuous cycles).

Alex Rivera Senior Engineer · reports to you Give Feedback Request Peer Feedback Request 1:1 Feedback Goals Feedback Requests • Ship feedback module · Done • Improve incident response time · In progress

A report's page: Manager Actions toolbar plus tabs for goals, feedback and requests.

Send peer-feedback requests _early_ in the cycle — peers need time to write thoughtful answers, and you need their input before writing your own review.

6\. Goals & 1:1 feedback
------------------------

### Reviewing a report's goals

*   Open the report → **Goals** tab.
*   You can see (but not edit) their goals. Use 1:1s to agree changes — the employee updates them.

### Giving continuous (1:1) feedback

*   Outside of formal review cycles, use **Request 1:1 Feedback** or click **Give Feedback** directly on a report's page.
*   1:1 feedback is great for capturing a moment (project retro, missed milestone, big win) while it's fresh.

7\. Tickets — raising and working tickets
-----------------------------------------

Tickets are how anyone in the company asks another team (IT, People Team, Facilities, …) for help. As a manager you'll use them in two ways:

*   **As a requester**, exactly like an employee — to open a ticket for yourself or on behalf of a report.
*   **As an agent**, if an admin has added you to a _ticket team_ (e.g. you run People Ops and you're on the _People Team_). Agents are the people who actually work the tickets.

Being a manager doesn't automatically make you an agent. Agent access is granted by an admin via the **Agent** flag on your user account, plus membership in one or more ticket teams.

### Creating a ticket

1.  Open **My Tickets** in the sidebar.
2.  Click **Create Ticket**.
3.  Pick the **team** (where should this land?), a clear **title**, a **description**, and a **priority**.
4.  Attach files if it helps (screenshots, logs).
5.  Click **Create** — the team's agents see it immediately.

Use ticket priorities sparingly. Reserve **Urgent** for things actually blocking work; otherwise pick **Normal**.

### Tracking your own tickets

*   The **My Tickets** view lists every ticket you opened, plus filters for _Open_ and _Closed_.
*   Click a row to see status, the assigned agent, and the comment thread. Add comments to reply or share new info.
*   When the agent moves the ticket to a _Final_ status (e.g. _Resolved_, _Closed_) it drops out of the Open filter automatically.

### Working tickets as an agent

If you're an agent, a new **Team Tickets** entry appears in the sidebar showing every ticket assigned to your team(s).

1.  Open **Team Tickets** — use the filters at the top to narrow by team, status, priority, or assignee.
2.  Click an unassigned ticket and **Assign to me** (or assign it to another agent on the team).
3.  Use the **Status** dropdown to move it through the workflow (e.g. _Open → In Progress → Waiting on Requester → Resolved_). The exact set of statuses is configured by an admin per team.
4.  Reply via the comment thread. Mention the requester to make sure they get notified.
5.  When done, move the ticket to a **Final** status — it stays searchable but no longer shows up in open counts.

Team Tickets · People Team 12 open · 3 waiting on requester · 2 urgent Open All priorities Assignee: any #412 New laptop for Maria Silva Urgent · Unassigned Assign to me #410 Offboarding paperwork — Tom Pereira Normal · In Progress · You #408 Update org chart on intranet — Waiting on Requester

Team Tickets view: pick an unassigned ticket, claim it, then drive it to a final status.

Tickets you are _assigned_ show up in **My Tickets** too (under an _Assigned to me_ filter). You don't need to keep both tabs open — the sidebar badge will nudge you when something needs attention.

8\. Day-to-day checklist
------------------------

*   📌 **Daily** — check the sidebar badge on Expenses; clear blockers.
*   📌 **Weekly** — open **My Team**, scan cards for cycles, nudge anyone with overdue self-reviews.
*   📌 **Cycle kickoff** — confirm goals are set for every report; send peer-feedback requests in the first week.
*   📌 **Cycle close** — review all feedback, write your manager assessment, share with each report in a 1:1.

9\. Tips & troubleshooting
--------------------------

*   **Can't see an expense / report** you expected? Check the org hierarchy with Admin — visibility is driven by the `manager-of` relationship.
*   **Rejected by mistake?** Ask the employee to resubmit; rejections are final on a given expense record.
*   **Cycle dropdown is empty?** The admin hasn't activated a cycle yet, or you have no reports in that cycle.
*   **No Team Tickets entry?** You need both the **Agent** flag on your account and membership in at least one ticket team — ask an admin.
*   **Need a form that doesn't exist?** Forms are managed by Admin — request one via a ticket to the People Team.

 wiredpeers · Manager Guide · xelerate.tech
