# Cadence

A course platform where learners buy courses and, in some cases, ask for their money back.

## Language

### Refunds

**Refund Request**:
A learner's ask to get their money back on a purchase, which the team reviews by hand. A purchase has at most one. It is Requested until someone decides, then Approved or Declined, and the decision is final.
_Avoid_: Reversal, Cancellation, Reversal request, pending request, open request

**Refund**:
The money going back to the learner for an Approved Refund Request, one per request: always the full Refundable Amount, never part of it. The learner keeps access to the course until the Refund is Issued.
_Avoid_: Reversal, Cancellation, partial refund

**Pending Refund**:
A Refund whose money has not yet been confirmed as sent.
_Avoid_: using "pending" for a Refund Request awaiting a decision

**Issued Refund**:
A Refund whose money has been confirmed as sent back to the learner. This is the moment the learner loses access to the course.
_Avoid_: completed refund, paid refund

**Failed Refund**:
A Refund whose money could not be sent. The Refund Request stays Approved, because the decision has not changed, and the same Refund can be retried, which makes it Pending again. Learners are shown a Failed Refund as Pending.
_Avoid_: declined refund

**Refundable Amount**:
Exactly what the learner paid for the purchase, after any discount, coupon or purchasing-power price.
_Avoid_: list price, course price

**Team Licence**:
One purchase that covers several seats for a team. It can only be refunded while none of its seats has been claimed.
_Avoid_: team purchase, bulk purchase

**Refund Window**:
The fourteen calendar days after a purchase during which a learner may make a Refund Request; the fourteenth day counts in full.
_Avoid_: cancel window, cancellation period

**Refund Eligibility**:
Whether a purchase may have a Refund Request made against it, judged once at the moment the request is made: inside the Refund Window, under two hours of video watched, under half the course's lessons completed, no claimed Team Licence seat, and no earlier Refund Request on the purchase.
_Avoid_: cancellation offer
