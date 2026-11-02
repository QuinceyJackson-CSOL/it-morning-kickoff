# Sample output (fictional data)

> **IT Kickoff, Tue, Mar 10**
> 5 items: 2 now, 2 today, 1 FYI. 1 SLA breached. 11 automated alerts skipped.

## Start here
1. Reply to ticket #1042 (offboarding). The first-response SLA was missed.
2. Fix Sam's VPN access before his 10 AM client call.
3. Send Priya the Adobe license approval link.

---

## NOW

**TICKET #1042 · Disable account for J. Doe · from HR · 3 days old**
`SLA BREACHED` `WAITING ON YOU`
The account deactivation request came in with no description. It's marked Pending, but IT hasn't replied yet.
**Likely fix:**
1. Confirm the cutoff time and the manager's name with HR.
2. At the cutoff, disable the account in Entra and revoke sessions.
3. Remove the user from NetSuite and Adobe.
4. Convert the mailbox to a shared mailbox and give the manager access.
5. Lock the device in MDM.

*Runbook: Employee Off-board Checklist*
**Draft:** "Hi Jamie, I've got this. Can you confirm the last day, the cutoff time, and their manager? I'll take care of everything at that time and update this ticket."

**SLACK DM · VPN not connecting · Sam R. · 40 min ago**
`BLOCKING SOMEONE`
Sam gets an "authentication failed" error on the VPN after resetting his password yesterday. He has a client call at 10.
**Likely fix:**
1. The VPN client probably saved his old password. Have him clear the stored credentials and sign in again.
2. Check the Entra sign-in logs for a conditional access block.

**Draft:** "Morning Sam. Your VPN app is probably still holding your old password. Can you quit it, sign in again with the new one, and let me know? If that doesn't work I'll jump on a call before 10."

## TODAY

**EMAIL · Adobe license for new designer · Priya K. · yesterday 4:10 PM**
`DUE TODAY`
Priya needs an Adobe seat for a new hire who starts tomorrow, and the app owner's approval isn't on file yet.
**Likely fix:**
1. Ask Priya to submit the access request ticket.
2. Get the app owner's approval on that ticket.
3. Assign the seat.

*Runbook: IT Access Management*

**TICKET #1047 · Monitor flickering · Alex T. · Medium · 1 day old**
Alex's external monitor flickers when it's connected through the dock.
**Likely fix:**
1. Swap the cable.
2. Update the dock firmware.
3. Test a direct connection.

## FYI

**#it-team** · The team decided to move laptop refreshes to Q3. The vendor quote is due Friday.

---
*Nothing was sent or changed. All drafts are waiting for your approval.*
