## Notes on Exhibit B (v 1.2)

### Introduction

Version 1.2 of this document differs from 1.1 by noting a proposed change with respect to Essential Patents suggested by the [IP-flow document](https://java.net/downloads/jsr358/Meeting%20Materials/IP-flow-v8.pdf). Taking this change into account brings the proposal closer to the views expressed by several members at a recent Working Group meeting that the new Exhibit B should be as similar as possible (perhaps identical) to the JSPA.

### The current JSPA

The current JSPA says that with respect to Contributions that you make to a JSR you grant Royalty-Free (RF) licenses a) to your copyrights and trade-secrets in your contributions and b) for any Essential Patents (patents "whose infringement cannot be avoided in a technically feasible manner when implementing the Specification") related to your contributions. You can not opt out of your obligation to license Essential Patents related to your Contributions.  

You are also obliged to license Essential Patents for all JSRs even when these patents do not relate to a Contribution that you make (that is, these could relate to contributions made by others to a JSR for which you serve on the Expert Group, or to contributions made by others to a JSR that you have no involvement with at all). Your obligation in these cases is to license the patents on FRAND (fair, reasonable, and non-discriminatory) rather than RF terms; in other words, you can charge for the license. You can opt out of your obligation to license these Essential Patents if you disclose them before Public Review.

NOTE: The [IP-flow document](https://java.net/downloads/jsr358/Meeting%20Materials/IP-flow-v8.pdf) we've been working on proposes a change with respect to Essential Patents not related to Contributions for Expert Group members. It says:

> "Expert Group members make royalty-free grants with respect to their Essential Patents even as these relate to material contributed by others. Grants with respect to material that they did not Contribute may be revoked if they disclose the relevant patents and withdraw from the Expert Group prior to publication of the spec for a JCP milestone (eg, Public Review, Proposed Final Draft…) If a milestone passes without disclosure and withdrawal then the EG member is obligated to license Essential Patents that bear on the spec as it was at that milestone."

In the remainder of this document I will assume that this proposed change has been put into effect.

In summary, there are four distinct IP grants in the current JSPA:  

1) Copyright and trade secrets in Contributions that a member makes to an EG (whether or not they are a formal member of the EG)  
2) Patents that are associated with a Contribution that a member makes to an EG (whether or not they are a formal member of the EG)  
3) Essential patents (not associated with a Contribution) that are related to a JSR for which a member participates in the EG  
4) Essential patents (not associated with a Contribution) that are related to a JSR for which the member does not participate in the EG

### The _strengthened Exhibit B_  

Our proposed solution for employed individuals who wish to join as full members is that their employers should sign a "strengthened Exhibit B". (The current Exhibit B simply releases the employee from any obligations he/she may have to assign to the employer IP relevant to a particular JSR; the employer makes no IP commitments at all. Note that the employee's own IP commitments will be defined in the JSPA itself.)

We want this Exhibit B to require the employer to make IP commitments that are comparable to those made by full corporate members, but that are different from the commitments made by JSPA signatories. (If the IP term were identical in the two cases then there would be no reason for an employer not to simply join as a corporate member.) In addition, we want the differences between the Exhibit B and the full JSPA to provide an incentive for a corporation to choose corporate membership over "sponsoring" its employees as individual Full members.  

We must therefore look for ways in which we can distinguish between the strengthened Exhibit B and the full JSPA. Such distinctions might be in the input (the IP commitment that the signatory makes) or in the output (the benefits that they receive in return for their commitments).

### Possible distinctions between Exhibit B and the full JSPA

During our discussions in the Working Group we considered the following distinctions:

*   Exhibit B might require only a copyright commitment and not a patent commitment.
*   Distinguish between RF and (F)RAND commitments.
*   Distinguish between the terms of Essential Patent grants for JSRs where the employee is a member of the EG and those for "all JSRs".
*   Limit the rights of Exhibit B signatories to declare and withhold Essential Patents.
*   Distinguish between the benefits accruing to those who make IP commitments.

### A new Exhibit B

On the input side, let's consider each of the four separate IP grants listed above.  

> In the current JSPA items 1 and 2 require RF commitments for anything that is actively contributed. I don't believe that we should weaken these commitments in the new Exhibit B.  
>   
> For item 3, since we are already proposing a change to the JSPA to make all Essential Patent grants by EG members RF no further distinction can be made between the JSPA and Exhibit B.  
>   
> For item 4 we might state that only JSPA signatories incur this obligation. (This would tend to make the Exhibit B option more attractive than the JSPA option.) For the record, the other two options in this area are a) no difference between Exhibit B and the JSPA and b) Exhibit B signatories must license "all" Essential Patents on RF terms while JSPA signatories are obliged only to license on FRAND terms. (It's possible that this last suggestion would be so onerous that very few employers would be willing to sign the strengthened Exhibit B, thereby defeating the whole purpose.)
> 
> For items 3 and 4 we might distinguish between the right that the patent-owner has to disclose and withhold patent grants.
> 
> > One possibility would be to state that if an Exhibit B signatory declares and withholds an Essential Patent associated with a JSR for which an employee is a member of the EG then the employee must withdraw from that EG (no such requirement is or would be placed on JSPA signatories).
> > 
> > If we do require Essential Patent grants from Exhibit B signatories for all JSRs (not just for those where employees are on the EG) then we could impose a similar penalty here and say that any withholding of an Essential Patent would require all employees to withdraw from all all EGs (which would in effect mean - and perhaps we should enforce this - that all current employee memberships would be canceled and no employees of that corporation would be permitted to join in the future). In effect, this would mean that the only way for such a corporation to withhold a patent would be to withdraw completely from the JCP.
> > 
> > To make this distinction even stronger we might prohibit Exhibit B signatories from disclosing and withholding Essential Patents at all unless they (that is, all their employees) withdraw from the JCP.

On the output side we want to somehow weaken the benefits that Exhibit B signatories would get in comparison with JSPA signatories. Since everyone (not just JCP members) gets the right to implement JCP specifications (so long as the implementations are compatible) I'm not sure how to discriminate on the output side of the equation.  

### A proposed new Exhibit B

The new Exhibit B should be per-person but not per-JSR, and should cover any JSR that the named employee participates in. This would obligate the employer to make the following IP commitments:  

*   RF grants of copyright, trade-secrets, and patents with respect to Contributions made by the employee.  

*   RF grants with respect to Essential Patents not related to Contributions for any JSR in which the employee is a member of the Expert Group. The employer can opt out of this obligation by disclosing the patent before Public Review, but on doing so the employee must resign from the Expert Group.

*   Alternative #1: if a patent is disclosed and withheld the employee must resign from the JCP.
*   Alternative #2: if a patent is disclosed and withheld all employees of the organization must resign from the JCP.

*   (There would be no obligations with respect to Essential Patents for JSRs in which the employee is not a member of the EG.)

I think this is strong enough that we would be satisfied that an employer was not dodging IP commitments, yet different enough from the full JSPA that it makes sense for it to exist at all. (Obviously it's weaker in the sense that there are no obligations for JSRs in which the member doesn't participate, but I think we can live with that.)