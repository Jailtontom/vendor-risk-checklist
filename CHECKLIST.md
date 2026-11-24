# Vendor Risk Checklist for Community Banks and Credit Unions

*Version 1.4 · November 2026 · Jailton de Andrade Raimundo · Tech Finance Advisor (techfinanceadvisor.com)*

## Why this checklist

Community banks and credit unions depend on a small number of technology providers for core processing, digital banking and payments. When one provider fails, many institutions can be affected at once: in late 2023, a ransomware attack on a single technology provider (it began on November 26, 2023, according to the NCUA) disrupted services at roughly 60 credit unions. Large banks have dedicated vendor-management teams; most small institutions do not.

This checklist turns the U.S. interagency third-party risk guidance (2023), the agencies' guide for community banks (2024), the 2026 proposed update and the September 2026 joint statement on core service providers into 42 practical questions: 37 organized by the six stages of a provider relationship, plus five for providers that use AI. It also covers accessibility for customers who are blind, deaf or hard of hearing, or have speech disabilities.

## How to use it

- Use it before signing, at renewal, and once a year for your highest-risk providers (core, digital banking, payments).

- A "no" is not a failure: it is a gap to discuss with the provider, document, and track until closed.

- Scale the effort to the potential harm: not every provider needs every question.

- Question numbers changed in version 1.4. If you are following an earlier reference (for example, a letter or article citing version 1.3), see MAPPING.md for where each version 1.3 question is now.

- A control that exists is not the same as evidence you can rely on: for your highest-risk providers, check whether the evidence behind each answer supports the decision you are making (to sign, renew or keep relying on the provider).

## 1. Planning

- [ ] **1.** Which customer data, systems and payment flows will this provider touch?

- [ ] **2.** If this provider is down for one business day, what stops working for customers?

- [ ] **3.** How many realistic alternative providers exist, and what would it cost (time, money, conversion work) to switch if we had to leave in three years?

- [ ] **4.** Does this service depend on other providers (cloud, data centers, telecommunications, subcontractors), and do any of our other critical providers depend on the same ones?

- [ ] **5.** Who inside the institution will own this relationship, and do they have the time, skills and training to manage it without depending on the provider's own staff?

- [ ] **6.** Is the level of oversight we plan proportionate to the potential harm?

- [ ] **7.** Can customers who are blind, deaf or hard of hearing, or have speech disabilities complete key tasks with this service (open an account, pay, get support), including support channels beyond voice such as chat, text and relay services?

## 2. Due diligence and selection

- [ ] **8.** Will the provider share recent independent security reports (for example, SOC 2 Type II) and penetration test summaries, and do the reports' scope, coverage period and exceptions actually cover the services we use?

- [ ] **9.** How many security incidents and outages has the provider had in the last 24 months, and how were they handled?

- [ ] **10.** Which components of the product are at or near end of support, and what is the upgrade roadmap?

- [ ] **11.** Is the provider financially stable enough to support us for the full contract term?

- [ ] **12.** Which subcontractors (fourth parties) will handle our data, and where?

- [ ] **13.** Can we talk to two or three peer institutions of similar size that use this provider?

- [ ] **14.** For customer-facing products, does the provider publish an Accessibility Conformance Report (VPAT/ACR) stating which WCAG version and level it meets (for example, WCAG 2.1 or 2.2 AA), and have the screens been tested with screen readers and keyboard-only navigation, ideally by people with disabilities?

## 3. Contract

- [ ] **15.** Does the contract state clearly that the institution owns its data, and can we export all of it, at any time, in a documented and usable format, at a defined cost?

- [ ] **16.** Are deconversion fees and exit assistance defined in advance, not left open?

- [ ] **17.** Are SLAs measurable (availability, response and recovery times) with consequences if missed?

- [ ] **18.** How fast must the provider notify us of a security incident or major outage?

- [ ] **19.** Are pricing and billing clear enough that we can reconcile every invoice line to a service we receive, and is there a limit on back-billing (retroactive charges for items missing from prior invoices)?

- [ ] **20.** Can other providers integrate with the platform through documented APIs, without excessive fees or restrictions?

- [ ] **21.** Do we have audit rights, and will the provider cooperate with regulators?

- [ ] **22.** Does the contract require customer-facing products to meet a defined accessibility standard, with a deadline to fix accessibility defects, and are statements, notices and disclosures available in accessible formats (screen-reader-friendly documents, large print, captioned video)?

## 4. Oversight and accountability

- [ ] **23.** Have the board and senior management set a clear, practical risk appetite for outsourcing (with simple risk-based limits, such as how much of a critical activity can depend on a single provider), and do they know which provider relationships carry the highest risk?

- [ ] **24.** Is there a single, current inventory of providers, with the risk level, a documented reason for that level, and an owner for each one?

- [ ] **25.** How often are high-risk relationships reviewed, and who signs off?

- [ ] **26.** Are issues found with a provider tracked until they are closed, and if a material issue stays open, who has authority to accept it, based on what evidence, and until when?

## 5. Ongoing monitoring

- [ ] **27.** Do we track availability against the agreed SLA every month, with our own measurements?

- [ ] **28.** Do we track incident notification times and root-cause reports from the provider?

- [ ] **29.** Have recovery and failover been tested in the last 12 months, and did the actual recovery time and data loss meet our own requirements (RTO and RPO)?

- [ ] **30.** Do we review new end-of-support components and security advisories that affect us?

- [ ] **31.** Do invoices still reconcile with the services we receive?

- [ ] **32.** Have the provider's subcontractors, ownership or financial condition changed, and is there a defined trigger to revisit the original risk assessment when they do?

- [ ] **33.** Do we track accessibility complaints and defects, and does each new release keep the agreed accessibility level?

## 6. Termination and exit

- [ ] **34.** Have we ever tested a full data extract, and are the data and interfaces documented well enough for another team or provider to load and rebuild them without the provider's help?

- [ ] **35.** Is there a written transition plan with timelines, responsibilities, customer communication, and how long old and new systems can run in parallel?

- [ ] **36.** What happens to our data at the provider after exit (return, deletion, confirmation)?

- [ ] **37.** Could we exit in an emergency (provider failure or major breach), not only at renewal?

## 7. Providers that use AI

*Skip this section if the provider does not use AI or machine-learning models in the services we buy.*

*Before you start: request written answers and available supporting evidence. If the provider cannot answer an important question, document the limitation, who accepts the resulting risk, and when the decision should be reconsidered.*

*Also check internally: whether our own staff independently check that AI outputs are accurate and valid before relying on them in decisions or workflows, especially where the provider's disclosures or our contract leverage are limited.*

- [ ] **38.** Does the provider use AI or machine-learning models in the service we buy, which decisions or outputs do they affect (for example, credit, fraud, customer service, monitoring), and can the system take actions, such as freezing an account, denying a transaction, changing a customer record or initiating a payment, without our staff approving each one?

- [ ] **39.** Is any of our customer data used to train or improve the provider's models, or shared with the company that supplies the model (a fourth party), and can we opt out in the contract?

- [ ] **40.** Can the provider explain what its AI outputs mean, their important limitations, and how they affect our decisions? If the service is used in credit decisions, can it provide the information we need to identify the specific reasons for an adverse action?

- [ ] **41.** Can the provider give us a summary of its relevant testing (accuracy, bias and drift), significant findings, limitations and corrective actions, and tell us how often that testing is repeated?

- [ ] **42.** Will the provider notify us before a change that materially affects our service, customers or risk exposure (such as replacing the model or its supplier), as distinct from routine updates? If the AI becomes unavailable or produces unacceptable results, do we have a practical fallback or escalation process?

*Why this section: the federal banking agencies' revised model risk guidance (OCC Bulletin 2026-13, April 17, 2026) applies to vendor and third-party products even when the bank has limited access to code, data or methodology; it does not cover generative or agentic AI and is directed mainly at institutions with significant model-risk exposure. GAO-25-107197 (May 19, 2025) found that AI in financial services can lead to biased lending decisions, data-quality issues and privacy concerns, and that NCUA cannot examine technology service providers. CFPB Circular 2022-03 confirms that creditors must give specific reasons for adverse action even when they use complex algorithms. These questions are practical due-diligence prompts, not specific regulatory mandates.*

*Acknowledgment: Section 7 reflects professional feedback from Neil P. Osnato (Founder, Persistence Analytics Group LLC). This acknowledgment is not an endorsement, regulatory certification or independent validation of the checklist.*

## Practitioner feedback

> “A thoughtful and practical resource, particularly for smaller institutions that may not have dedicated third-party risk teams.” — Neil P. Osnato, Founder, Persistence Analytics Group LLC

> “It's a helpful, practical starting point for community banks and credit unions, especially with the lifecycle structure, accessibility coverage, and current guidance touchpoints. […] It's already a strong resource for smaller institutions!” — Jonathan Blair, MISM, MMSC, independent risk management practitioner

*Shared as professional feedback. It is not an independent certification or endorsement of the checklist's regulatory completeness.*

## Acknowledgments

Version 1.2 incorporates suggestions from Neil P. Osnato, Founder, Persistence Analytics Group LLC, Decision Assurance™, on questions 4, 9, 31, 35 and 38 and on the "How to use it" section. Section 7 of version 1.3 (questions 46–50) also reflects his professional feedback. These are version 1.3 numbers; in version 1.4 the same questions, with unchanged wording, are 4, 8, 26, 29, 32 and 38–42 (see MAPPING.md).

Version 1.4 thanks Jonathan Blair, MISM, MMSC, independent risk management practitioner, for professional feedback (not an endorsement) that shaped two additions: a risk appetite for outsourcing, now part of question 23 (Q28 in version 1.3), and an internal check on AI outputs in the introduction to section 7. The documented reason for each provider's risk level (question 24) reflects a point raised by a third-party risk management practitioner. Any remaining errors are the author's.

## Disclaimer

This checklist is a free, non-binding operational aid based on public U.S. interagency guidance. It is not legal advice and does not replace an institution's own risk assessment. Free to use and share with attribution (CC BY 4.0).

## Sources

- Interagency Guidance on Third-Party Relationships: Risk Management (June 2023).

- Third-Party Risk Management: A Guide for Community Banks (Federal Reserve, FDIC and OCC, May 2024).

- NCUA, Cybersecurity and Credit Union System Resilience, report to Congress (June 2024).

- Proposed Third-Party Risk Management Guidance, 91 FR 58536 (September 15, 2026): federalregister.gov/documents/2026/09/15/2026-18859

- Joint Statement on Community Banks' Engagement with Core Service Providers (September 11, 2026): federalreserve.gov/newsevents/pressreleases/files/bcreg20260911a3.pdf

- U.S. Department of Justice, Guidance on Web Accessibility and the ADA (March 2022): ada.gov/resources/web-guidance

- Office of the Comptroller of the Currency, Bulletin 2026-13, revised model risk management guidance (April 17, 2026).

- U.S. Government Accountability Office, GAO-25-107197, Artificial Intelligence: Use and Oversight in Financial Services (May 19, 2025).

- Consumer Financial Protection Bureau, Circular 2022-03, adverse action notification requirements and complex algorithms (May 2022).

## Version history

*Question numbers in each entry refer to that version's numbering.*

- 1.4 (November 2026): shortened from 50 to 42 questions by combining eight pairs of overlapping questions; added a risk appetite for outsourcing (question 23), a documented reason for each provider's risk level (question 24) and an internal check on AI outputs (section 7 introduction), based on practitioner feedback; renumbered the questions. The wording of the questions refined in versions 1.2 and 1.3 with practitioner feedback is unchanged. See MAPPING.md for the full version 1.3 → 1.4 table.

- 1.3 (November 2026): added section 7, "Providers that use AI" (questions 46–50), with a note on its regulatory scope, based on practitioner feedback.

- 1.2 (November 2026): refined questions 4, 9, 31, 35 and 38 and added a note on evidence to "How to use it", based on practitioner feedback; added practitioner feedback and acknowledgments.

- 1.1 (November 2026): corrected the date of the 2023 incident and added two sources.

- 1.0 (November 2026): first public version.
