# Posted Invoice Approval

In Business Central, the approval flow for purchase invoices is placed before posting by default. This is intended to be logical, but from an accounting perspective, it is a problem.

The solution is the **Posted Invoice Approval** app. The invoice is posted immediately and is therefore visible in your reporting. However, release for payment only occurs after approval.

## Approve Posted Purchase Invoice

The approver will see in the start page of BC, that there is an approval request:

![Approval request](../images/approve-posted-purchase-invoice/approval-request.png)

![Approval actions](../images/approve-posted-purchase-invoice/approval-actions.png)

The approver can now approve the invoice. The On Hold code will be removed and status of the posted purchase invoice will be set from Pending Approval to Released.

### Approve
The approver can now approve the invoice. The On Hold code will be removed and status of the posted purchase invoice will be set from Pending approvqal to Released
 
### Reject
The approver can also Reject the approval request.
The moment the approver rejects the posted purchase invoice, the status will be set from Pending Approval to Open. The On Hold code will be set to DA (based on the Posted Invoice Approval Setup).

[:arrow_left:](../README.md) [Back](../README.md)
