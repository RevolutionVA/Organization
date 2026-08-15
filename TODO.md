# TODO

Open items for RevolutionVA's public record. Each one names the source of the obligation so it's
clear which are required and which are best practice.

---

## 1. Adopt a new Conflict of Interest Policy — **required**

**Status:** the *signed acknowledgments* exist; the *Policy itself* does not.

Erik Olson, Kevin Griffin and Linda Nichols each executed a "Conflict of Interest Policy Statement"
on November 30, 2015 (same DocuSign envelope as the Bylaws), confirming *"I have received a copy of
the Conflict of Interest Policy."* The referenced Policy is not in Google Drive, the shared drives,
or anywhere else scanned.

Why it matters:
- **Bylaws Article XIII** — the Board *shall* establish and maintain a Conflict of Interest Policy.
- **Bylaws § 16.4(e)** — the Corporation *shall keep a copy* of it.
- **Bylaws §§ 5.1, 5.2, 11.6, 14.1(iii)** all condition director/officer transactions, compensation and indemnification on compliance with it.
- The **2025 Form 990, Part VI line 12a** currently answers **No** to "Did the organization have a written conflict of interest policy?" That contradicts the Bylaws and the signed statements.

Action: continue searching for the historical policy, including in the Form 1023 materials described
in item 4, but adopt a fresh policy regardless so the operative rules are clear and current. Use the
IRS sample policy in the Form 1023 instructions, Appendix A, as a starting point, publish it at
`governance/conflict-of-interest-policy.md`, have current directors re-execute acknowledgments,
and correct line 12a on the next 990.

## 2. Whistleblower policy — **not required, recommended**

**Do we need it?** No — neither the IRS nor Virginia requires a 501(c)(3) to have one, and
answering "No" on Form 990 Part VI line 13 is permitted. It is asked because it is treated as a
governance best practice, and funders and grantmakers do read that line.

One caveat worth knowing: the Sarbanes-Oxley whistleblower-retaliation provision (18 U.S.C. § 1513(e))
applies to **all** organizations, nonprofits included. Retaliating against someone who reports a
federal offense is unlawful whether or not a policy exists. A written policy doesn't create the
obligation, it just makes the reporting path clear.

Decision: the Board intends to adopt one as part of governance formalization. Publish it at
`governance/whistleblower-policy.md` after Board and legal review.

## 3. Document retention and destruction policy — **not required, recommended**

Same posture as item 2. Form 990 Part VI line 14 currently answers **No**; that is permitted.

Caveat: the Sarbanes-Oxley document-destruction provision (18 U.S.C. § 1519) also applies to all
organizations — destroying records to obstruct a federal investigation is unlawful regardless of
policy. Separately, **Bylaws § 16.1 already requires permanent retention of minutes** and
**§ 16.4** already requires keeping five specific records, so part of a retention schedule is
effectively mandated by the Bylaws.

Decision: the Board intends to adopt one, aligned to what § 16.4 already requires, permanent
retention of core governance and tax records, at least seven years for routine supporting financial
records, and a legal-hold process. Publish it at `governance/document-retention-policy.md` after
Board and legal review.

## 4. Obtain a copy of Form 1023 — **required to keep, required to disclose**

The exemption application is not on file anywhere.

- **Bylaws § 16.4(d)** requires the Corporation to keep a copy.
- **IRC § 6104(d)** makes Form 1023 subject to public inspection, on the same footing as the Form 990s.
- It very likely contains the missing Conflict of Interest Policy as an attachment (item 1).

Action: request a copy from the IRS using **Form 4506-B** (*Request for a Copy of Exempt Organization
IRS Application or Letter*). There is no fee. Note that the reinstatement application after the
auto-revocation may have been a **Form 1023-EZ**, in which case the IRS copy will be thinner and
will not carry attachments — worth checking which was filed.

## 5. Adopt restated Bylaws under the RevolutionVA name

The operative Bylaws are titled *"Bylaws of RevolutionConf"* and use that name throughout; the
corporate name changed in 2016. The Markdown transcription at `governance/bylaws.md` reads
"RevolutionVA" for clarity, but **the executed PDF controls** — so today the published version and
the operative version differ cosmetically.

Restating also gives the Board a chance to reconcile two live discrepancies:
- Board size: Articles § 7(b) allows 1–15 directors; Bylaws § 2.1 says 1–7.
- Article XIII's Conflict of Interest Policy requirement vs. item 1 above.

The Board is developing a broader restatement covering board composition, founding-director rights,
rotating terms, officer elections, meeting procedures, financial controls and related governance
matters. Proposed rules remain non-operative until formally adopted. Linda Nichols will review the
proposal before it goes to Pierce Legal. The currently operative Bylaws permit amendment by majority
Board resolution (§ 19.1); the restated package proposes a higher threshold for future amendments.

## 6. Start keeping and publishing Board minutes — **required**

**Bylaws § 16.1** requires permanent minutes of all Board meetings and all actions taken without a
meeting. No minutes were found anywhere in the scanned material. The Board must also meet at least
once per year (§ 3.1).

Action: record minutes going forward in `board/minutes/YYYY-MM-DD.md`. State plainly that formal
historical minutes were not kept. Do not invent, backdate or present reconstructed narratives as
historical minutes. Earlier facts may be documented as present-day history or resolutions with the
date of documentation clearly stated.

## 7. Complete the board roster

`board/README.md` still needs the current service start dates. The current officers have confirmed
the operative roster: Kevin Griffin is President and Secretary/Treasurer; Linda Nichols is Vice
President; they are the only current directors. The 2025 Form 990 reported different officer titles,
so future filings should use the current roles.

## 8. Decide how to publish the Form 990s

Tax years 2020–2025 are available. The returns are "Open to Public Inspection" and there is no
Schedule B, so no donor information is at stake. But the accountant's client copies contain material
that must not be published as-is:

- **Form 8879-TE** — carries the preparer's EFIN/PIN and is marked *"Do not send to the IRS. Keep for your records."* Remove entirely.
- **Preparer PTIN** on the signature block.
- **A director's home address**, which appears twice on the 2025 return (Part I line F, principal officer; Part VI line 20, books and records custodian).
- Two-Year Comparison, Tax Projection Worksheet, Tax Return History and workpapers — internal preparer output, not part of the public return.

Two options:
- **(a)** publish Form 990 + Schedule A + Schedule O only, with the home address replaced by the Chesapeake mailing address; or
- **(b)** don't host PDFs at all — link to IRS Tax Exempt Organization Search and ProPublica Nonprofit Explorer.

Either way: ask the accountant to use the organization's mailing address for the principal officer
and books-and-records fields on future returns.

## 9. Update the disclosure answers on the next Form 990

Once this repository is live, the next return can change:

| Line | Today | After |
|---|---|---|
| Part VI, line 18 (how documents are made available) | "Upon request" only | check **"Own website"** |
| Part VI, line 19 / Schedule O | "990 AVAILABLE UPON REQUEST" | point to this repository |
| Part VI, line 12a (conflict of interest policy) | No | Yes, on completing item 1 |
| Part VI, line 13 (whistleblower policy) | No | Yes, on completing item 2 |
| Part VI, line 14 (document retention policy) | No | Yes, on completing item 3 |

## 10. Verify Virginia SCC standing

Kevin Griffin confirms that Pierce Legal is the registered agent. Verify the current SCC record,
confirm that the annual report is current, and retain the most recent report as required by Bylaws
§ 16.4(c). The last registered-agent paperwork found in the document scan dates from 2022 and names
Pierce McCoy, PLLC, so the public record and retained files should be reconciled.

## 11. Extend code of conduct coverage

[`RevolutionVA/code-of-conduct`](https://github.com/RevolutionVA/code-of-conduct) currently holds
`hrdevfest-coc.md` and `revconf-coc.md`. The Board intends to add an organization-wide Code of
Conduct and nondiscrimination commitment that RevolutionVA programs, events and online spaces
inherit by default. RevolutionVA provides event-specific sponsorship to **BSides Hampton Roads** but
does not operate it; the repository must not describe BSides as a RevolutionVA-run program or imply
that RevolutionVA controls its Code of Conduct.