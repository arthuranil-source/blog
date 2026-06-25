---
title: "What Happens to Your Data When You Return a Leased Copier?"
description: "Leased copiers store every document you've ever scanned or printed on an internal hard drive. Here's exactly what happens to that data when the machine goes back."
coverImage: "https://cdn.pixabay.com/photo/2015/09/05/20/02/office-926228_1280.jpg"
coverImageAlt: "Office photocopier in a modern workplace with paper trays and control panel"
ogImage: "https://cdn.pixabay.com/photo/2015/09/05/20/02/office-926228_1280.jpg"
date: "2026-06-25"
lastUpdated: "2026-06-25"
author: "Arthur Anil"
tags: ["copier data security", "leased copier", "hard drive wiping", "data breach", "NIST 800-88", "managed print services"]
---

# What Happens to Your Data When You Return a Leased Copier?

Most businesses treat the office copier the same way they treat the coffee machine: it works in the background, and nobody thinks too hard about what's inside it. But when your copier lease ends and a technician rolls that machine out the door, something important leaves with it: a hard drive containing images of nearly every document your office has ever copied, scanned, faxed, or printed.

This is not a minor oversight. It's one of the most common and least talked-about data security risks in business. This article explains exactly what data a copier stores, what happens to it when the machine is returned, and what you need to do before it leaves your building.

---

> **Key Takeaways**
> - Modern digital copiers contain internal hard drives that store images of every document processed through the machine.
> - When a leased copier is returned, that drive goes with it — and most leasing companies do not erase it on your behalf.
> - A 2010 CBS News investigation found that copiers purchased secondhand from a warehouse contained sensitive medical records, police documents, and personal financial data still readable on the internal drives.
> - NIST Special Publication 800-88 defines the federal standard for media sanitization and applies directly to copier hard drives.
> - You are legally responsible for what's on that drive, even after the machine leaves your office.

---

## Does Your Copier Actually Store Your Documents?

Yes, and it stores a lot more than most people realize. Every modern digital copier — any machine made in the last 20 years that can scan, copy, fax, or print — contains an internal hard drive. That drive works as a temporary buffer to manage large print jobs, but it also retains images of every document the machine has processed.

[Indiana University's information security guidance on printers and copiers](https://informationsecurity.iu.edu/protect-data/printers-copiers.html) explains this clearly: digital copiers essentially function as computers, and like any computer, they store data on persistent storage media. That storage doesn't clear itself when the machine is powered off. It stays on the drive until it is actively overwritten or destroyed.

[A publication from IITR on data protection using leased copy machines](https://www.iitr.us/publications/data-protection-using-leased-copy-machines) breaks down what types of documents typically pass through an office copier over the course of a lease: tax returns, personnel records, contracts, medical forms, bank statements, legal documents, and internal strategy materials. Over a standard 3-to-5-year lease, the volume of sensitive data accumulated on that drive can be substantial.

[Sharp UK's guide on photocopier hard drive security](https://www.sharp.co.uk/news-and-events/blog/photocopier-hard-drive-security-are-you-at-risk) confirms that this applies not just to high-end enterprise machines but to the mid-range floor-standing copiers that most small and medium businesses lease. The hard drive is standard equipment, not a premium feature.

---

## What Actually Happens When You Return the Copier?

When your lease expires, you contact the leasing company, they schedule a pickup, and a technician collects the machine. From that point, the copier typically goes to one of three places: it is refurbished and re-leased to another business, it is sold on the secondary market, or it is sent to a dealer liquidator.

[MasterCopy's guide on what happens at the end of a copier lease](https://www.mastercopy.co.uk/copier-and-printer-leasing/what-happens-at-the-end-of-a-copier-lease/) notes that leasing companies are in the business of moving equipment efficiently. Their standard process is to collect the machine, test it for mechanical function, and put it back into circulation. Hard drive sanitization is not typically part of their standard return process unless it is contractually required.

[AIS's explanation of what happens to office copier data when you return or replace it](https://www.ais-now.com/blog/what-happens-office-copier-data-when-you-return-replace-it) puts it plainly: the data on that drive is not the leasing company's legal problem. It belongs to whoever created it. If sensitive documents are recoverable from the drive after the machine is returned, the liability belongs to the business that leased the copier, not the company that collected it.

This is the point most businesses miss. Handing the machine back does not transfer responsibility for the data on it.

---

## What Can Go Wrong — and Has Gone Wrong

This is not a theoretical risk. The consequences of returning a copier without wiping the drive have played out in documented, public cases.

In 2010, [CBS News reported that a company notified 409,000 people of a data breach](https://www.cbsnews.com/news/photocopier-fallout-company-notifies-409000-of-data-breach/) traced to data recovered from a returned copier's hard drive. The investigation that preceded that story involved purchasing used copiers from a warehouse in New Jersey and extracting the hard drives. The drives contained readable images of pay stubs, medical records, domestic violence complaints, and narcotics investigation files.

[CSO Online's report on the FTC's examination of copier privacy risks](https://www.csoonline.com/article/525236/ftc-examines-privacy-risks-of-copier-hard-drives.html) followed up on that investigation and noted that the Federal Trade Commission began formally examining the issue. The FTC found that businesses in healthcare, finance, and legal services were particularly exposed, given the sensitivity of the documents those industries routinely process.

[The HHS HIPAA enforcement case involving a health plan photocopier breach](https://www.hhs.gov/hipaa/for-professionals/compliance-enforcement/examples/health-plan-photocopier-breach-case/index.html) provides a concrete regulatory example: a health insurance company returned leased copiers to the leasing company without wiping the drives. The drives contained protected health information for over 300,000 individuals. The company paid a $1.2 million settlement. The HHS Office for Civil Rights made clear that HIPAA's data protection requirements extend to copier hard drives.

[GovInfoSecurity's reporting on breach alerts involving copiers](https://www.govinfosecurity.com/breach-alert-copiers-are-risk-a-2449) documents additional cases across government agencies and private organizations, consistently finding the same gap: the organization assumed the leasing company would handle data destruction, and the leasing company assumed it was the organization's responsibility.

---

## What the Law and Standards Say You Must Do

The obligation to sanitize storage media before it leaves your control is not just a best practice. It is a legal requirement under several regulatory frameworks and a defined technical standard under federal guidelines.

[NIST Special Publication 800-88 Revision 1](https://csrc.nist.gov/pubs/sp/800/88/r1/final) is the definitive federal standard for media sanitization. It defines three levels of data destruction:

- **Clear** — Overwriting data using software tools, effective against standard data recovery.
- **Purge** — Using more intensive techniques (such as cryptographic erasure or multiple-pass overwrites) to defeat laboratory-level recovery attempts.
- **Destroy** — Physical destruction of the media, making recovery impossible regardless of the methods used.

[Accountable HQ's guide to hard drive sanitization under NIST 800-88](https://www.accountablehq.com/post/hard-drive-sanitization-how-to-securely-erase-data-nist-800-88-guide) explains how these levels apply to copier drives: for most business environments, a Purge-level wipe is appropriate. For organizations handling classified or highly sensitive data, physical destruction of the drive may be required before the machine is returned.

[Jetico's explanation of NIST SP 800-88 media sanitization guidelines](https://jetico.com/blog/nist-sp-800-88-guidelines-media-sanitization-explained/) notes that many modern copiers have a built-in overwrite function in their settings menu. This is typically found under Security or Storage settings, and it runs a software-based overwrite of the drive. This satisfies the Clear level under NIST 800-88 for most classifications of sensitive business data.

[The U.S. Navy's CHIPS article on copier data security](https://www.doncio.navy.mil/chips/ArticleDetails.aspx?SectionID=72&IssueID=9) is particularly direct: any device that processes, stores, or transmits data is subject to data sanitization requirements before disposal or transfer. That includes copiers, regardless of whether the machine is being sold, returned, or scrapped.

For law firms specifically, [Pulse Technology's guide to law firm copier security and client data](https://www.pulsetechnology.com/blog/law-firm-copier-security-client-data) highlights that attorney-client privilege obligations create an additional layer of responsibility. A data breach traced to a returned copier could expose a firm to bar complaints in addition to regulatory penalties.

---

## What You Should Do Before Returning Any Leased Copier

The process is straightforward. It requires attention, not technical expertise.

**Step 1: Use the copier's built-in overwrite function.** Almost every commercial copier manufactured after 2005 includes this. Access the machine's administrator settings (your IT team or the copier manufacturer's documentation can guide you), find the data overwrite or storage erase option, and run it. [Commercial Copier Leasing South Florida's end-of-lease security guide](https://commercialcopierleasingsouthflorida.com/end-of-lease-data-security-wiping-copier-hard-drives-before-they-leave/) provides a walkthrough of this process for the most common copier brands.

**Step 2: Request a certificate of data destruction.** When using a third-party IT asset disposal company, always request written documentation confirming the drive has been wiped. [Excess IT Hardware's guide to end-of-lease data security](https://excessithardware.com/end-of-lease-it-equipment-data-security/) notes that reputable ITAD vendors provide this as standard and that the certificate serves as evidence of due diligence if a regulatory inquiry ever arises.

**Step 3: Review your lease agreement before the machine leaves.** [Novatech's guide on what to do when your copier lease is expiring](https://novatech.net/blog/what-to-do-when-your-copier-lease-is-expiring) recommends reading the data security provisions in your lease carefully. Some leasing agreements include a hard drive retention clause, which means you can keep the physical drive when the machine is returned. If that option exists, keep the drive and arrange for its separate destruction.

**Step 4: Consider a hard drive removal or destruction add-on.** Many copier vendors offer end-of-lease data destruction as a paid service. [Buyerzone's guide to returning leased copiers](https://www.buyerzone.com/office-equipment/digital-copiers/ar-returning-leased-copiers/) recommends confirming in writing what data destruction service, if any, is included in your return terms — and purchasing it separately if it isn't.

[For the Record Magazine's coverage of copier data security in healthcare](https://www.fortherecordmag.com/archives/0114p12.shtml) and [a research paper from Marshall University's forensics program](https://www.marshall.edu/forensics/files/Bobka-Research-Paper-160803.pdf) both document cases where organizations assumed their vendor handled destruction, only to discover later that no action had been taken. Don't assume — confirm in writing and get documentation.

---

## Frequently Asked Questions

### Does every copier have a hard drive?

Every digital copier manufactured in the last two decades contains internal storage. This includes floor-standing multifunction devices, desktop all-in-ones, and networked printers with scanning capability. The drive is required for the machine to manage print queues and document processing. Per [Indiana University's security guidance](https://informationsecurity.iu.edu/protect-data/printers-copiers.html), you should assume any device that can scan or copy is storing data until proven otherwise.

### Is the leasing company responsible for wiping the drive?

No, in most cases. Unless your lease contract explicitly states that the leasing company will perform certified data destruction and provide documentation, that responsibility belongs to you. The HHS HIPAA enforcement cases and [the FTC's examination of copier privacy risks](https://www.csoonline.com/article/525236/ftc-examines-privacy-risks-of-copier-hard-drives.html) both confirmed that the organization leasing the machine is accountable for the data on its drives.

### What standard should I follow when wiping a copier drive?

[NIST Special Publication 800-88 Revision 1](https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-88r1.pdf) is the applicable federal standard. For most businesses, a software-based overwrite (Clear or Purge level) using the copier's built-in function is sufficient. Organizations handling regulated data (healthcare, legal, financial) should use Purge-level sanitization and obtain a written certificate of destruction.

### What if the copier's built-in overwrite doesn't work?

If the built-in function fails or the machine is too old to have one, contact a certified IT asset disposal provider. They can remove and destroy the drive physically, which satisfies [NIST 800-88's Destroy standard](https://blog.fcelect.com/nist-data-sanitization-itad-practices/) and is the safest option for any device where software-level sanitization cannot be confirmed.

---

## Conclusion

Returning a leased copier is a routine administrative task that carries a non-routine risk. The machine leaving your office almost certainly contains a hard drive with years of sensitive documents stored on it, and in the vast majority of cases, nobody wipes that drive unless you specifically arrange for it.

The steps to protect yourself are not complex: run the built-in overwrite before return, request written confirmation of destruction, and check your lease agreement for hard drive retention options. What's complex is the exposure if you skip them — regulatory penalties, breach notification requirements, and the reputational damage that comes with a preventable data incident.

Treat the copier the same way you'd treat a laptop at end of life. You wouldn't hand back a company laptop without wiping it. The same standard applies here.

**Before your next lease return:**
- Locate the data overwrite function in the copier's admin settings
- Run a full storage erase before the pickup date
- Request written documentation from your vendor confirming destruction
- Review the data security terms in your lease agreement
- Consult [NIST SP 800-88](https://csrc.nist.gov/pubs/sp/800/88/r1/final) if you handle regulated data

[INTERNAL-LINK: copier lease end checklist → complete end-of-lease equipment return guide with compliance documentation templates]

---

## Sources

- IITR, "Data Protection Using Leased Copy Machines," retrieved 2026-06-25, https://www.iitr.us/publications/data-protection-using-leased-copy-machines
- HHS, "Health Plan Photocopier Breach Case," retrieved 2026-06-25, https://www.hhs.gov/hipaa/for-professionals/compliance-enforcement/examples/health-plan-photocopier-breach-case/index.html
- Indiana University Information Security, "Printers and Copiers," retrieved 2026-06-25, https://informationsecurity.iu.edu/protect-data/printers-copiers.html
- U.S. Navy CHIPS, "Copier Data Security," retrieved 2026-06-25, https://www.doncio.navy.mil/chips/ArticleDetails.aspx?SectionID=72&IssueID=9
- Buyerzone, "Returning Leased Copiers," retrieved 2026-06-25, https://www.buyerzone.com/office-equipment/digital-copiers/ar-returning-leased-copiers/
- CSO Online, "FTC Examines Privacy Risks of Copier Hard Drives," retrieved 2026-06-25, https://www.csoonline.com/article/525236/ftc-examines-privacy-risks-of-copier-hard-drives.html
- Sharp UK, "Photocopier Hard Drive Security: Are You at Risk," retrieved 2026-06-25, https://www.sharp.co.uk/news-and-events/blog/photocopier-hard-drive-security-are-you-at-risk
- CBS News, "Photocopier Fallout: Company Notifies 409,000 of Data Breach," retrieved 2026-06-25, https://www.cbsnews.com/news/photocopier-fallout-company-notifies-409000-of-data-breach/
- Marshall University, Bobka Research Paper on Copier Forensics, retrieved 2026-06-25, https://www.marshall.edu/forensics/files/Bobka-Research-Paper-160803.pdf
- NIST, Special Publication 800-88 Revision 1: Guidelines for Media Sanitization, retrieved 2026-06-25, https://csrc.nist.gov/pubs/sp/800/88/r1/final
- Professional Solutions, "Old Computer and Copier Data Security for Physicians," retrieved 2026-06-25, https://www.profsolutions.com/webres/File/physicians/OldComputerCopier.pdf
- GovInfoSecurity, "Breach Alert: Copiers Are a Risk," retrieved 2026-06-25, https://www.govinfosecurity.com/breach-alert-copiers-are-risk-a-2449
- MasterCopy, "What Happens at the End of a Copier Lease," retrieved 2026-06-25, https://www.mastercopy.co.uk/copier-and-printer-leasing/what-happens-at-the-end-of-a-copier-lease/
- AIS, "What Happens to Office Copier Data When You Return or Replace It," retrieved 2026-06-25, https://www.ais-now.com/blog/what-happens-office-copier-data-when-you-return-replace-it
- Commercial Copier Leasing South Florida, "End of Lease Data Security: Wiping Copier Hard Drives Before They Leave," retrieved 2026-06-25, https://commercialcopierleasingsouthflorida.com/end-of-lease-data-security-wiping-copier-hard-drives-before-they-leave/
- Novatech, "What to Do When Your Copier Lease Is Expiring," retrieved 2026-06-25, https://novatech.net/blog/what-to-do-when-your-copier-lease-is-expiring
- Pulse Technology, "Law Firm Copier Security and Client Data," retrieved 2026-06-25, https://www.pulsetechnology.com/blog/law-firm-copier-security-client-data
- Excess IT Hardware, "End of Lease IT Equipment Data Security," retrieved 2026-06-25, https://excessithardware.com/end-of-lease-it-equipment-data-security/
- NIST, SP 800-88 R1 Full Publication PDF, retrieved 2026-06-25, https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-88r1.pdf
- Accountable HQ, "Hard Drive Sanitization: How to Securely Erase Data — NIST 800-88 Guide," retrieved 2026-06-25, https://www.accountablehq.com/post/hard-drive-sanitization-how-to-securely-erase-data-nist-800-88-guide
- Jetico, "NIST SP 800-88 Guidelines for Media Sanitization Explained," retrieved 2026-06-25, https://jetico.com/blog/nist-sp-800-88-guidelines-media-sanitization-explained/
- FC Elect, "NIST Data Sanitization and ITAD Practices," retrieved 2026-06-25, https://blog.fcelect.com/nist-data-sanitization-itad-practices/
- For the Record Magazine, "Copier Data Security in Healthcare," retrieved 2026-06-25, https://www.fortherecordmag.com/archives/0114p12.shtml
