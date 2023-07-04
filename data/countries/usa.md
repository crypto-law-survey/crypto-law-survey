**Version 28.0, July 2023**

**© Bert-Jaap Koops**
**Portions © Analog Devices, Inc. **  

Licensed under Creative Commons Attribution Share Alike 4.0 International.

SPDX-License-Identifier: CC-BY-SA-4.0

# United States of America

## 1. Export / Import Controls

### Import

There are no import restrictions on cryptography.

### Export

The US has signed the [Wassenaar](wassenar.md) Arrangement, but does not implement the (pre-December 1998) General Software Note and generally maintains stricter controls.

#### Export Administration Regulations (EAR)

Cryptography export used to be controlled by the International Traffic
in Arms Regulation (]{#ear}[ITAR](#itar)). At the end of 1996,
cryptography export was transferred to the [Export Administration
Regulations](http://www.access.gpo.gov/bis/ear/ear_data.html) (EAR) of
the Department of Commerce, 15 C.F.R. Parts 730-774 (see in particular
sections 740.13, 740.17 and 742.15). The export policy was relaxed to
favor export of data-recovery cryptography. This initiative was
announced in a [statement by the Vice President](http://www.epic.org/crypto/key_escrow/clipper4_statement.html) of 1 October 1996, and further elaborated in a November 15, 1996 executive order and memorandum, and in the Commerce Department draft EAR of December 30, 1996. The Department of Justice is now included in crypto export decisions. (Incidentally, the Commerce Department has \"borrowed\" three export control and crypto specialists from the FBI and NSA to help process license applications.)

Making available cryptography on the Internet or a BBS is considered
export, unless appropriate measures are taken to prevent foreigners from
accessing the cryptography.

The export rules distinguish between five categories of \"encryption
items\" (EI).

1.  Certain *mass-market* encryption software may be released from EI
    controls after a one-time review.
2.  *\"Data recovery\"* crypto (meaning that government can access keys
    or plaintext with a lawful warrant) will be eligible for an export
    license to non-embargoed countries. The procedures for data-recovery
    licenses were simplified in September 1998, when also \"recoverable
    products\" were released for export (a recoverable product means
    that an operator can access plaintext without the user noticing).
3.  After a one-time review, (up to) *56-bit cryptography* can be
    granted a six-month export license, provided the exporting business
    commits itself to incorporating a data recovery feature in its
    products within the next two years. This provision was changed in
    December 1998, when all 56-bit crypto was released for export after
    a one-time review, with no requirement of data recovery.
4.  All *other* encryption items may be eligible for encryption
    licensing arrangements; items not authorized under a licensing
    arrangement will be considered on a case-by-case basis.
5.  Encryption *\"technology\"* may be licensed for export on a
    case-by-case basis.

In August 1997, a 25 July interagency [draft Encryption
Items Rule](http://jya.com/bxa-ei-rule.htm) modifying the EAR was
published on the Internet, although the Department of Commerce declined
to check its authenticity. It would implement the government\'s key
recovery policy, and clarify several issues, e.g., that electronic
export to Canada is not controlled, the personal-use exemption (see
below), that support documentation is not required for exports of
technology or software (and removing this requirement for export to most
Eastern European countries), and that export of non-key recovery
financial-specific cryptography is allowed if it can by design only be
used for financial applications. The regulation would also require Web
server operators that allow people to download encryption software to
seek an advisory opinion from the Bureau of Export Affairs. See also an
[article](http://jya.com/bxa-nyt.htm) by Peter Wayner on the draft.

The Bureau of Export Administration (BXA) (now: Bureau
of Industry and Security, BIS) has reviewed the export controls to
determine whether they should be modified, rescinded or extended. On 8
October 1997, it released a [statement](http://jya.com/bxa100897.txt)
\"seeking comments on how existing foreign policy-based export controls
have affected exporters and the general public.\" On 15 January 1998, it
published an [interim rule](http://bxa.fedworld.gov/bxainfo.html#wass)
revising the Commerce Control List, necessary to implement the
(pre-December 1998) Wassenaar Arrangement. The interim rule also
imposed new reporting requirements on persons that export certain items
to non-Wassenaar countries.

Two major reviews of the export controls were announced in July and in
September 1998 by BXA. The 7 July announcement, which was implemented in
an [interim rule](http://jya.com/bxa092298.txt) of 22 September 1998,
introduced a licensing policy for **banks and financial institutions**
(notably, brokers, credit-card companies, and securities firms).
Non-voice crypto products can be exported by banks and financial
institutions after a one-time review, with no data-recovery requirement,
to 45 countries (members of the Financial Action Task Force or countries
that have money-laundering laws) (Anguilla, Antigua, Argentina, Aruba,
Australia, Austria, the Bahamas, Belgium, Barbados, Brazil, Canada,
Croatia, Denmark, Dominica, Ecuador, Finland, France, Germany, Greece,
Hong Kong , Hungary, Iceland, Ireland, Italy, Japan, Kenya, Luxembourg,
Monaco, the Netherlands, New Zealand, Norway, Poland, Portugal, St.
Vincent and the Grenadines, St. Kitts and Nevis, Seychelles, Singapore,
Spain, Sweden, Switzerland, Trinidad and Tobago, Turkey, the UK, the US,
and Uruguay). To other countries, their export-license applications will
be viewed with a \"presumption of approval\".

On 16 September 1998, a major relaxation of export controls was
announced, which was implemented in a 31 December 1998 [interim
rule](http://jya.com/bxa123198.txt). This entailed the following.

-   All crypto products of up-to **56 bits** are released for export
    after a one-time review, except to the (currently seven as defined
    by the US) [terrorist countries](#us_terror). This includes DES,
    56-bit RC-2/4/5, 56-bit CAST. Also, asymmetric crypto of up to 1024
    bits is released for export. For export to military or government
    end-users, semi-annual post-facto reporting is required.
-   Export to **subsidiaries** of US companies is permitted (except to
    those located in the seven terrorist countries) under license
    exception. For export to strategic partners, \"favorable treatment\"
    under license will be extended.
-   Export to **health, medical, and insurance** companies (in the
    strict sense) is permitted to the same 45 countries as export by
    banks and financial institutions is allowed (see above). Biochemical
    and pharmaceutical producers excluded from this permission.
-   Export to **online merchants** is allowed, under license exception,
    for \"export of client-server applicaitons (e.g., SSL) and
    applications tailored to on-line transactions\" to online merchants
    located in the 45 countries of the bank list (see above). The export
    is \"limited to those that facilitate secure electronic transactions
    between merchants and their customers.\" Export to other countries
    receive a policy of approval under export licensing arrangements.
-   \"**Recoverable** products\" (which allow recovery of the plaintext
    without assistance or knowledge of the end user) can be exported to
    foreign commercial firms for internal company proprietary use only,
    located in most of the 45 countries listed above, with a semi-annual
    post-export reporting requirement of end users.
-   For exporting **key-recovery** products, the review of foreign
    key-recovery agents is eliminated.

After the President's Export Council Subcommittee on
Encryption advised in \"[Liberalization
2000](http://cryptome.org/LIB42.htm)\" to ease the export controls, the
goverment
[announced](http://www.pub.whitehouse.gov/uri-res/I2R?urn:pdi://oma.eop.gov.us/1999/9/16/15.text.1)
further relaxation of export controls on 16 September 1999. (At the same
time as this announcement, the goverment announced the Cyberspace
Electronic Security Act ([CESA](#us_cesa99)) 1999 to meet the perceived
effects of the export changes on law enforcement and national security.)
The changes were to be implemented by 15 December 1999, but were
subsequently postponed. The [new
regulations](http://www.epic.org/crypto/export_controls/regs_1_00.html)
were finally published on 12 January 2000 (the [press
release](http://204.193.246.62/public.nsf/docs/60D6B47456BB389F852568640078B6C0)
is less specific but much more readable). The major components of the
updated policy are the following.

-   Any crypto of any key length can be exported under a license
    exception, after a technical review, to non-government end users in
    any country except the seven [\"terrorist countries\"](#us_terror).
    Exports to governments can be approved under a license.
-   Retail crypto (i.e., crypto which does not require substantial
    support and is sold in tangible form through retail outlets, or
    which has been specifically designed for individual consumer use) of
    any key length can, after a technical review, be exported to any
    recipient in non-terrorist countries.
-   Unrestricted crypto source code (like most \"open source\" software)
    and publicly available commercial source code (like \"community
    source\" code) can be exported to any end-user under a license
    exception without a technical review. BXA (BIS) must be given a copy
    or the URL of the source code. All other source code can be exported
    under license exception after a technial review to any
    non-government end-user. One may not, however, knowlingly export
    source code to a terrorist country, although source code may be
    posted on the WWW for downloading without the poster having to check
    whether it is downloaded from a terrorist country.
-   Any crypto can be (re)exported to foreign subsidiaries of US firms
    without a technical review. Foreign nationals working in the US no
    longer require an export license to work for US firms on encryption.
-   The regulations implement the December 1998 [Wassenaar](#Wassenaar)
    changes (notably, export of 56-bits and 64-bits (for mass-market
    products) crypto to non-terrorist countries).
-   Post-export reporting is required for exporting certain products
    above 64 bits to non-US entities.

Since 19 October 2000, a further liberalization of export controls is
effective, triggered by changes in the EU export regulations (see the
Federal Register Vol. 65, No. 203, pp. 62600-10). The
liberalization was announced on 17 July 2000. A license exception is
introduced for export of any crypto product to *any* end user (so, the
distinction between government and non-government end users is dropped)
in the 15 EU countries, Australia, Czech Republic, Hungary, Japan, New
Zealand, Norway, Poland, and Switzerland. Also, US exporters can ship
products immediately after filing a commodity classification request,
without waiting for the technical-review results or the previously used
30-day delay period.

On 6 June 2002, a further liberalization was published
([Federal
Register](http://frwebgate.access.gpo.gov/cgi-bin/getdoc.cgi?dbname=2002_register&docid=fr06jn02-6.pdf)
Vol .67, No. 109, p. 38855). Mass-market crypto with key length
exceeding 64 bits can now be exported after a 30-day review by the
Bureau of Industry and Security (BIS) (without having to report after
export, and without national-security review). To EU countries and the 8
other countries (Australia, Czech Republic, Hungary, Japan, New Zealand,
Norway, Poland, Switzerland), mass-market crypto can be exported
immediately after the review request has been registered with BIS. \
Publicly available source code can be exported to most destinations
after notification. \
The rule also clarifies that no review or notification is required for
export to US companies and subsidiaries for internal company use; for
products with short-range wireless encryption; and for items with
limited encryption use. \
See the [fact
sheet](http://www.bis.doc.gov/Encryption/EncFactSheet6_17_02.html) of
the rule at BIS.

On 9 December 2004, BIS published a further
\'streamlining\' of export procedures. A uniform 30-day review period
was now implemented for most encryption items that need review.
Moreover, the \'license-free zone\' to which mass-market crypto can be
exported immediately after a review request has been registered, was
expanded with the new EU member states (effectively adding Cyprus,
Estonia, Latvia, Lithuania, Malta, Slovakia, and Slovenia).\
The word \'retail\', which caused confusion because it was used beside
\'mass-market\', was deleted from the regulations.
\'Publicly-available\' crypto software placed on the Internet under the
relevant notification procedures can be modified without additional
notification, provided it remains at the same URL. Finally, procedures
for beta-test software and procedures for increasing key lengths of
previously reviewed and authorized products have been simplified.\
See the [fact
sheet](http://www.bis.doc.gov/Encryption/EncFactSheet12_02_04.htm) of
the 9 December 2004 rule at BIS.

On 7 January 2011, a minor amendment was made to the EAR ([Federal
Register](http://www.gpo.gov/fdsys/pkg/FR-2011-01-07/pdf/2010-32803.pdf)
Vol. 76, No. 5, p. 1059). Publicly available mass-market encryption
object code software (with symmetric key length exceeding 64 bits), and
publicly available encryption object code of which the corresponding
source code falls under License Exception TSU (i.e., when the source
code is publicly available), are no longer subject to the EAR. The
amendment includes some minor specific revisions.

The \"terrorist countries\" are: Cuba, Iran, Iraq, Libya, North Korea,
Sudan, and Syria.

See [BIS\' Wassenaar](http://www.bis.doc.gov/Wassenaar/) and BIS\'
[encryption](http://www.bis.doc.gov/Encryption/Default.htm) page. See
also the encryption excerpts of [BXA\'s 1997 Annual
Report](http://jya.com/bxa97-encry.htm).

### Personal-use exemption

In February 1996, the ITAR rules were amended as regards personal use of
cryptography. Temporary export of products for personal use was exempted
from the need of a license, provided the exporter take normal
precautions to ensure the security of the product, including locking the
product in a hotel room or safe. The product must not be intended for
copying, demonstration, marketing, sale, re-export, or transfer of
ownership or control. In transit, the product must remain with the
exporter\'s accompanying baggage. The exporter must keep records of each
export for five years. Export to embargoed countries (e.g., Cuba, Libya,
Syria) is prohibited. Under the new EAR, the ITAR personal use exemption
is replaced by license exception TMP and BAG (see the
[EAR](http://www.access.gpo.gov/bis/ear/ear_data.html) at 15 CFR 740.4
and at 740.14 and the [original ITAR
version](http://jya.com/itar021696.txt)). The Department of Commerce
announced in February 1997 it would revise the new regulations to, among
others, clarify the personal use exemption for laptop computers.

### Export Administration Act

The Export Administration Act expired in August 1994, but it was
extended by Executive Order 12924 by the president with the authority
under the International Emergency Economic Powers Act ([50 USC
1701ff](http://cryptome.org/50usc-ch35.htm)). [The president most
recently extended the state of emergency in an]{#subcom}
[order](http://jya.com/eo081199.htm) of 10 August 1999. On 9 August
1999, Senators Gramm and Enzi published a [draft Export Administration
Act of 1999](http://www.senate.gov/~enzi/eaa.htm) to reauthorize the
EEA, which would maintain controls, except for items easily available
abroad.\
Michael Froomkin (in [It came from Planet
Clipper](http://www.law.miami.edu/~froomkin/articles/planet_clipper.htm#POSTSCRIPT))
argues that the government has no authority to steer industrial crypto
policy through export regulation, and that the subsequent orders to
extend the EAA can hardly be justified with a reference to a state of
emergency this long.

#### Export case law

-   In August 2001, two men were arrested and accused of attempting to
    illegally export encryption devices to China ([news
    report](http://ap.tbo.com/ap/breaking/MGAJ2GYKZQC.html)).
-   In February 2002, the Commerce Department fined a San Diego firm
    \$95,000 for illegally exporting 128-bit encryption software to
    South Korea ([news
    report](http://www.linuxsecurity.com/articles/government_article-4509.html)).

#### Export Council Subcommittee

In April 1997, the
President\'s Export Council Subcommittee on Encryption was established
to advise the Secretary for Export Administration on the implementation
of crypto export policy; it consists of approximately 25 members from
the exporting community and government agencies.

### ITAR

The [International Traffic in Arms
Regulation](http://www.epic.org/privacy/crypto/export_controls/itar.txt)
(ITAR) restricted export of \"dual-use\" cryptography (that is,
cryptography that can serve both civilian and military purposes) by
placing it on the Munitions List. For (relatively strong) products that
can encipher information, an export license was usually issued only for
use by foreign branches of American enterprises and for use by financial
institutions. \"Weak\" cryptography (e.g., with a certain maximum
key-length) could also be exported.

Export of cryptography that served only authentication or integrity
purposes was already ruled by the Export Administration Regulations.
Some types of public-domain software were decontrolled and on the
Commerce Control List.

In 1995, the Administration proposed a mitigation of the export
controls. Cryptography using keys up to 64 bits (as opposed to the
current maximum of 40 bits) would be exportable, provided it implements
key-escrow. Criteria for exportable cryptography were discussed at two
meetings in September and December 1995; criteria for the escrow agents
were handed out at the December meeting.

### Initiatives to relax export controls

Several initiatives, as yet unsuccessful, have been taken, both in
Congress and by the public, to try to mitigate the cryptography export
restrictions.

### Karn, Bernstein, and Junger cases

A federal district court in Washington, DC, on March 22, 1996 rejected
the claims of *Phil Karn*, stating that the case presented a political
question for the two elected branches to decide. It held that the export
restrictions did not violate the First Amendment. The defence appealed;
on 6 November 1996, the Department of Justice filed a [brief on
appeal](http://www.venable.com/oracle/oracle8.htm). On 21 January 1997,
the appeal court remanded the case to the district court in light of the
[transfer](#ear) of the export controls to the Department of Commerce;
it did not reach the constitutional issues. In August 1997, the
Department of Commerce ruled that certain programs Karn sought to export
were controlled by the EAR and subject to prior licensing. Karn
challenged this classification in a law suit against the DoC; in March
1998, the government moved to dismiss this law suit. On 18 February
1999, the D.C. District Court
[granted](http://people.qualcomm.com/karn/export/lbo_ruling.html)
Karn\'s request for discovery and an evidentiary hearing. However,
following the January 2000 [revisions](#us_exp9909) of the export
regulations, which effectively made publicly available source code
freely exportable, Karn allowed his case to be dismissed as moot. See
[more information](http://people.qualcomm.com/karn/export/index.html) on
this case.

Contrary to the 1996 Karn decision, a Northern California district
court, in a [December 18, 1996
decision](http://www.eff.org/pub/Legal/Cases/Bernstein_v_DoS/) in the
case of *Daniel Bernstein*, who seeked the ability to export his
encryption algorithm, judged the export regulations to be too
restrictive. The disctrict judge found the licensing system an
unconstitutional prior restraint on free speech - having ruled earlier
that crypto source code was protected by the First Amendment (see the
[decision of April 15,
1996](http://www.eff.org/pub/Legal/Cases/Bernstein_v_DoS/Legal/960415.decision),
in which she denied the government\'s motion to dismiss the case). The
judge called the licensing system a \"paradigm of standardless
discretion\", given its lack of decision time limits, of standards for
denial and of appeal provisions. The ruling does not relate to object
code. On December 30, 1996, Bernstein\'s lawyers asked the government to
delay enforcement of the new [export rules](#ear) until they are
reviewed for constitutionality.\

On 25 August 1997, the federal district court affirmed its earlier
decision, declaring that the Export Administration Regulations and all
rules promulgated thereunder insofar as they apply to cryptography are
in violation of the First Amendment on the grounds of prior restraint
and are, therefore, unconstitutional. The judge enjoined the government
from further enforcement of the regulations, including prosecution of
\"anyone who uses, discusses or publishes or seeks to use, discuss or
publish \[Bernstein\'s\] encryption program and related materials.\" The
government, on 28 August 1997, requested a stay of the Court\'s order
pending appeal, which was granted for the most part; Bernstein could,
however, publish his program on the Internet after 8 September. See the
[de cision of August 25,
1997](http://www.eff.org/pub/Legal/Cases/Bernstein_v_DoS/Legal/970825_decision.html).\

On [6 May
1999](http://www.eff.org/pub/Legal/Cases/Bernstein_v_DoS/Legal/19990506_circuit_decision.html),
the Court of Appeals for the Ninth Circuit held (two to one) that the
EAR are an unconstitutional prior restraint on free speech in violation
of the First Amendment, arguing that source code is expressive speech
entitled to First Amendment protection. Judge Nelson dissented. The
government filed a
[motion](http://www.eff.org/pub/Legal/Cases/Bernstein_v_DoS/Legal/19990621_rehearing_motion.html)
for reconsideration on 21 June 1999, which was
[granted](http://www.mercurycenter.com/business/top/058160.htm) on 30
September. An 11-judge \"en banc\" panel of the Court was to re-examine
the case on 21 March 2000, but, as requested by Bernstein on 3 March,
the Court of Appeals on 12 April remanded the case back to the district
court for reconsideration in light of the January 2000
[revisions](#us_exp9909) of the export regulations. Eventually, however,
due to repeated assurances by the DoJ attorney Coppolino that the
government would not enforce several portions of the regulations, the
case was dismissed. So, in October 2003, Bernstein
[announced](http://cr.yp.to/export/2003/10.15-bernstein.txt) that the
case had come to an end (for now).\
See the [Bernstein archive](http://export.cr.yp.to).

In August 1996, law professor *Peter Junger* filed suit to challenge the
ITAR regulations, saying they restricted his ability to teach a
cryptography course, as foreign students are attending his classes; he
wants to publish his class materials on the WWW server. Following the
Bernstein decision (see above), Junger filed an amended complaint
against the EAR regulations. On 2 July 1998, in *[Junger v.
Daley](http://jya.com/pdj11.htm)* (N.D. Ohio, 1:96-CV-1723), the US
District Court for the Northern District Court of Ohio dismissed
Junger\'s claim, arguing that encryption source code is not sufficiently
expressive to merit First Amendment protection. Therefore, crypto export
is not protected conduct under the First Amendment, and export
regulation passes constitutional muster. On appeal, this decision was
reversed. In [Junger v.
Daley](http://pacer.ca6.uscourts.gov/cgi-bin/getopn.pl?OPINION=00a0117p.06),
2000 FED App. 0117P (6th Cir.) of 4 April 2000, the Court of Appeals for
the Sixth Circuit stated that computer source code merits First
Amendment protection, since it is a means of expression among
cryptographers: \"for individuals fluent in a computer programming
language, source code is the most efficient and precise means by which
to communicate ideas about cryptography\". Thus, the case was remanded
to the District Court to further consider the crypto export regulations
(as [revised](#us_exp9909) in January 2000) under the Constitution.

See various [documents](http://jya.com/pdj.htm) in this case, and
[another page](http://samsara.law.cwru.edu/comp_law/jvd/).

### Congress Bills

Three bills were proposed in 1996 to ease export controls. [Senator
Leahy\'s bill]{#leahy}, proposed on 5 March 1996, the [Encrypted
Communications Privacy
Act](http://www.eff.org/pub/Privacy/ITAR_export/Crypto_bills_1996/s1587_96.bill)
(S. 1587), reintroduced 27 February 1997 (S. 376), would, among others,
relax export controls, allowing generally available or public-domain
crypto to be exported. At the same time, Representative Goodlatte
introduced a similar bill, [Security And Freedom through Encryption
(SAFE)
Act](http://www.eff.org/pub/Privacy/ITAR_export/Crypto_bills_1996/hr3011_96.bill)
of 1996 (H.R. 3011), reintroduced on 12 February 1997 (H.R. 695). On 30
April 1997, the House Subcommittee on Courts and Intellectual Property
unanimously approved the SAFE bill. On 14 May 1997, the House Judiciary
Committee also unanimously approved the SAFE bill, after adopting three
amendments (one to the criminal provision (ensuring that it only
criminalizes crypto use with the intention to cover up a federal
felony), one to correct a technical oversight, and one to direct the
Attorney General to compile and maintain data on the instances in which
cryptography hampered the investigation). On 24 June 1997, the House
International Relations Subcommittee on International Economic Policy
and Trade approved the SAFE act. The House International Relations
Committee approved the bill on 22 July 1997, rejecting an amendment to
reinstate strict controls if relaxation would turn out to harm national
security. The House National Security Committee radically amended the
Bill to include the Secretary of Defense in export decisions
(Weldon/Dellums amendment), whereas the House Permanent Select Committee
on Intelligence replaced the language of the bill with domestic controls
(see below) as well as strengthening export controls (Goss/ Dicks
amendment). The House Commerce Committee, on 25 September 1997, rejected
an amendment by Oxley/Manton to strengthen export controls, and adopted
a version by Markey and White to remove export controls. Given the many
conflicting versions of the bill, the SAFE Act was not put to a vote,
especially since the chair of the House Rules Committee, Solomon, stated
to only move the Act to the floor if it contains (Oxley/Manton)
mandatory key escrow. (See [below](#safeprotect) on the re-introduced
bill.)

In May 1996, [Senator Burns]{#burns} launched a bill, [Promotion of
Commerce Online in the Digital Era (Pro-CODE) Act of
1996](http://www.eff.org/pub/Privacy/ITAR_export/Crypto_bills_1996/s1726_96.bill)
(S. 1726), reintroduced 27 February 1997 (S. 377). The bill would relax
export controls for generally available or mass-market cryptography. The
1997 bill would additionally establish an Information Security Board to
give law-enforcement agencies special access to the development of new
plans for privacy-enhancing technologies.

The Kerrey-McCain bill, Secure Public Networks Act ([see
below](#kerrey)), introduced June 1997, would allow export of 56-bit
non-key recovery cryptography under a license. Key recovery cryptography
would be exportable regardless of key length, under a license. An
inofficial draft amendment circulating in the government by August 1997
would somewhat relax the export provisions of the bill (export of crypto
with a recovery feature, regardless whether it is activated, would be
granted; an Advisory Board would recommend to the President whether
larger than 56-bit crypto could be decontrolled; and the power to
prohibit any exports \"contrary to US security interests\" would be
dropped). On 4 March 1998, the senators announced a new, largely
similar, version of their bill.

The [Computer Security Enhancement Act]{#CSEA} of 1997 (HR 1903) would
require the Commerce Department, upon request, to take into account the
foreign availability of comparable crypto in deciding the export of
crypto products. The Act was cleared in the House on 16 September 1997.

On 12 May 1998, senators Ashcroft and Leahy introduced the [E-PRIVACY
Act](http://www.epic.org/crypto/legislation/eprivacy.html) (\"Encryption
Protects the Rights of Individuals from Violation and Abuse in
Cyberspace\"). This would relax export controls, lifting the
restrictions for exporting generally available crypto products after a
one-time review by the Secretary of Commerce; this also valid for
products if a like product of similar strenght is commercially available
outside the US from a foreign supplier, which is to be determined by an
Encryption Export Advisory Board. The same holds for \"interface
mechanisms for interaction with other encryption products\" which do not
themselves provide encryption capabilities. For other crypto, an export
advisory board would make recommendations on its exportability.

On 25 February 1999, Rep. Goodlatte reintroduced the Security And
Freedom through Encryption Act (**SAFE**) (H.R. 850). The bill would
limit export license requirements for generally-available or
public-domain cryptography to a one-time, 15-day technical review.
Export would be allowed for more specialized products to the 45
countries on the \"financial export\" list (see [above](#us_bxa_9809))
or if a similar product is available abroad without export restrictions.
The SAFE Act was approved by the Commerce Committee on 23 June 1999
(with amendments) and by the International Relations Committee on 13
July 1999 (with amendments tightening certain provisions). The Permanent
Select Committee on Intelligence amended and approved the bill on 15
July; the amendments will be viewed as suggestions only, since the
Committee has no jurisdiction over the bill. The Armed Services
Committee substantially amended and approved the bill on 21 July 1999;
an amendment would permit the president, unsubjected to judicial review,
to block export if it is contrary to national-secyrity interests.
Subsequently, the bill went to the Rules Committee to reconcile the
competing versions into one that will be presented to the full House.

On 14 April 1999, Sen. McCain introduced the Promote Reliable On-Line
Transactions to Encourage Commerce and Trade (**PROTECT**) Act of 1999
(S. 798). This bill would allow unlimited crypto export to member states
of NATO, OECD, and ASEAN, and limit export to other countries to 64-bit
key-length crypto. An Encryption Export Advirosy Board would
periodically research foreign availability of cryptography and advise
amendments accordingly. The Bill passed the Commerce, Science, and
Transportation Committee on 23 June 1999.

On 9 August 1999, Senators Gramm and Enzi published a [draft Export
Administration Act of 1999](http://www.senate.gov/~enzi/eaa.htm) to
reauthorize the EEA, which would maintain controls, except for items
easily available abroad and mass-market items. On 27 July 1999, as an
alternative to the [SAFE](#safeprotect) Act, Rep. Goss introduced the
*Encryption for National Interests Act* (H.R. 2616), which would, among
others, remove key recovery as a factor in any export controls, and
allow exports of up to 64-bit symmetric crypto (level to be increased
every six months).

See for more information the [Pro-crypto Legislation
Archive](http://www.eff.org/pub/Privacy/ITAR_export/Crypto_bills_1996/).

On 5 September 1997, the [California]{#California} legislature passed a
resolution asking for a revision of federal crypto export controls,
supporting the proposed SAFE Act (the original version, see above).

### Reports

The Department of Commerce recommended easing export controls after a
joint
[study](http://www.epic.org/privacy/crypto/export_controls/commerce_study_summary.txt)
with the National Security Agency found that the export restrictions
harm US business.

In June 1996, the National Research Council released its long-awaited
[study on cryptography
policy](http://www.nap.edu/readingroom/books/crisis/). It recommended
that export controls be progressively relaxed, but not eliminated.
Products providing confidentiality at a level that meets most general
commercial requirements should be easily exportable; for today, this
would mean allowing export of 56-bit symmetric encryption products.
Export of stronger cryptography (i.e., today, using more than 56 bits)
should be exportable on an expedited basis to a list of approved
companies if the proposed user agrees to provide the US government
access to decoded information.

According to a draft paper [Enabling Privacy, Commerce, Security and
Public Safety in the
GII](http://www.epic.org/crypto/key_escrow/white_paper.html), the
government is working toward a policy that will readily license export
of key-escrow systems, once the needed infrastructure and
government-to-government agreements are in place.

### More information

See for more information and links the [Cryptography Export Control
Archives](ftp://ftp.cygnus.com/pub/export/export.html) and John Young\'s
[Arms Control Essays](http://jya.com/acda.htm).

## 2. Domestic laws and regulations

### DMCA

The [Digital Millennium Copyright
Act](http://thomas.loc.gov/cgi-bin/bdquery/z?d105:h.r.02281:) (Public
Law 105-304, H.R. 2281, also called WIPO Copyright Treaties
Implementation Act) was approved on 12 October 1998 by the House and
signed by the President on 29 October 1998. It creates penalties for
circumventing copyright-protection systems. Although limited exemptions
for circumventing such systems for the purposes of cryptography research
were included in the Act, cryptographers were still concerned that
crypto research and the development of cryptanalytic tools would be
hindered. (Compare EPIC\'s
[testimony](http://www.epic.org/privacy/copyright/epic-wipo-testimony-698.html).)
The *[Rulemaking](http://www.loc.gov/copyright/1201/anticirc.html) on
Exemptions from Prohibition on Circumvention of Technological Measures
that Control Access to Copyrighted Works* of the Copyright Office,
effective from 28 October 2000 until 28 October 2003, contains two
exemptions (related to filtering and malfunctioning software).\
Compare EFF\'s archive of [DMCA
cases](http://www.eff.org/IP/DMCA/#dirs).

### Case Law

In the case of [*United States* v
*Scarfo*](http://lawlibrary.rutgers.edu/fed/html/scarfo2.html-1.html),
the US District Court for the District of New Jersey held on 26 December
2001 that the federal wiretapping law and the Fourth Amendment allow the
use of a \"key logger\" that intercepts a passphrase to an encrypted
file, provided that the system does not operate while the computer is
communicating with other computers. Because of a plea agreement, there
will be no appeal in this case. See EPIC\'s [Scarfo
page](http://www.epic.org/crypto/scarfo.html).

In the case of *United States* v *Boucher* (2009 WL 424718 (D.Vt.)), the
District Court of Vermont found that an order to provide decrypted files
did not violate the privilege against self-incrimination. Boucher had
been stopped by Customs and had his laptop searched. Finding a file
named \"2yo getting raped during diaper change\" which could not be
opened, the customs agent asked Boucher to show all downloaded images on
the computer, upon which Boucher navigated to the \"Z\" drive which the
agent searched, finding what looked like child-porn files. The laptop
was seized, but afterwards the Z drive could not be accessed without a
password. Boucher was ordered by a grand jury subpoena to provide the
password. The Court held that in such circumstances, the Fifth Amendment
did not apply, since the act of producing the unencrypted files was not
testimonial on the basis of the \"foregone conclusion\" doctrine; it
would not reveal the \"existence or location\" of documents that were
unknown to the government (since the agent had seen relevant files on
the Z drive), nor would it authenticate the documents, since he had
already admitted to owning the laptop and shown files on the Z drive to
the agent. Therefore, the defendent must provide an unencrypted version
of the Z drive.

The District Court overturned the opinion by the Magistrate Judge in the
lower court (2007 WL 4246473 (29 November 2007)), who had held that a
password that protects encrypted files falls under the Fifth Amendment
privilege, since it exists in the suspect\'s mind and handing it over
would provide testimonial evidence, in particular, the fact that the
suspect knows the password and has control over the encrypted files. Cf.
Susan Brenner\'s [blog
post](http://cyb3rcrim3.blogspot.com/2007/12/court-upholds-using-fifth-amendment-to.html)
on the magistrate ruling.

In *United States v Gavegnano*, 2009 WL 106370 (4th Cir. Jan. 16, 2009),
the Court also held that obtaining the password to encrypted files was a
\"foregone conclusion\". Gavegnano used a laptop provided to him by his
government employer, which was seized upon suspicion of child
pornography. When requested, he gave the password to the encrypted
computer, and he was convicted for child pornography found there. On
appeal, Gavegnano argued that his Fifth Amendment had been violated.
This appeal failed on the basis of the \"foregone conclusion\" doctrine
\"because the Government independently proved that Gavegnano was the
sole user and possessor of the computer\" and hence giving the password
was not testimonial.

In *United States v Kirschner*, 2010 WL 1257355 (E.D. Mich. Mar. 30,
2010), the defendant was ordered to appear before the grand jury and to
provide \"all passwords used or associated with the . . . computer . . .
and any files\" (rather a fishing expedition). In such a case, ordering
a decryption key or password is similar to revealing the combination to
a wall safe, which requires the defendant to communicate knowledge.
Following the precedent of *United States v. Hubbell*, 530 U.S. 27
,(2000), this is testimonial. Since the prosecution had only promised
immunity for the act of giving the password, but not for resulting
evidence, the order to give passwords violated the Fifth Amendment,
since also information that may lead to incriminating evidence is
privileged even if the information itself is not inculpatory.

In *United States v Fricosu* (D.CO. Jan. 23, 2012) (No.
10-CR-00509-REB), the defendant was ordered on the basis of the All
Writs Act to provide the decrypted contents of her laptop that was
seized in her bedroom, providing immunity for the act of decryption but
not for any resulting evidence. Since the circumstances of the case
provided sufficient evidence that the laptop belonged to Fricosu and
that she was able to access the decrypted contents, and the government
knew the existence and location of the computer\'s files, the privilege
against self-incrimination did not apply, and the court ordered Fricosu
to hand over an unencrypted version of the laptop\'s hard disk (with
immunity for the authenticating act of providing the data, so that the
government needs to prove the fact that Fricosu had access to the files
based on other evidence).

John Doe was suspected of spreading child pornography. Certain parts of
the seized laptops and external hard disks were inaccessible; Doe
refused to provide the unencrypted contents of the disks before a grand
jury, and was convicted for contempt of court. In appeal, the Court of
Appeals for the 11th Circuit acquitted Doe (*United States v John Doe*,
*In re Grand Jury Subpoena Duces Tecum* (11 Cir Feb. 23, 2012)). The
disks were encrypted with TrueCrypt (an encryption programme that aims
to provide [\'plausible
deniability\'](http://en.wikipedia.org/wiki/Deniable_encryption)), and
the forensic investigators were not able to convince the court that
there was actually anything hidden in the unreadable parts of the disks.
Thus, it has not been demonstrated \"that the Government knows whether
any files exist and are located on the hard drives\" and the \"foregone
conclusion\" doctrine does not apply. Since the decryption order only
provided immunity for the act of decryption but not for resulting
evidence, the Fifth Amendment was violated.

## 3. Developments in cryptography regulation

### Escrowed Encryption Standard (Clipper)

In 1993, the Clinton Administration announced the Escrowed
Encryption Initiative (EEI), usually referred to as the Clipper
Initiative, after its first implementation in the Clipper chip. A
classified, secret-key algorithm, SKIPJACK, has been implemented in an
Escrowed Encryption Standard (EES). The reported basic idea of the EEI
is to provide citizens with a safe cryptosysem for securing their
communications without threatening law enforcement. The EES procures law
enforcement access by means of a Law Enforcement Access Field (LEAF)
that is transmitted along with each encrypted message; the field
contains information identifying the chip used. Law enforcement agencies
wire-tapping communications encrypted with EES can decipher tapped
messages by obtaining the two parts of the chip\'s master key that are
deposited with two escrow agencies (National Institute of Standards and
Technology and the Treasury Department\'s Automated Systems Division),
provided they have a court order for the tapping.

Following criticisms on the choice of escrow agents, the government came
up with commercial key escrow (\"Clipper II\"), a scheme in which the
escrow agents can be independent organizations chosen by cryptography
users.

The EES is a voluntary standard to be used in telephone communications.
Privacy advocates fear that the government may declare escrowed
encryption obligatory once it has captured a sufficient portion of the
market. The EES has been generally rejected, though.

In March 1997, the Department of Defense announced that the NSA,
developer of the Fortezza card (implementing the key-escrow system of
the EES), would no longer implement the EES; instead, it would work to
adopt key recovery as promoted by the US government (see below).

### Key Management Infrastructure

In its May 1996 draft paper [\"Enabling Privacy, Commerce, Security and
Public Safety in the
GII\"](http://www.epic.org/crypto/key_escrow/white_paper.html)(referred
to by opponents as Clipper III), the government proposes the
establishment of a key management infrastructure (KMI) that incorporates
key escrow. Participation in the KMI would be voluntary, and choice of
encryption algorithms would be free. A Policy Approving Authority would
certify Certification Authorities (CAs); it would also be responsible
for setting CA performance criteria to meet law enforcement\'s needs.
Users should escrow keys with an Escrow Authority (either the CA or an
independent EA) before they can get a public-key certificate.
Self-escrow is considered an acceptable option, if the corporate CAs can
meet necessary performance requirements, including independence from the
rest of the organization and handing over keys to law enforcement.

On December 5-6, 1996, a [Technical Advisory
Committee](http://csrc.nist.gov/tacdfipsfkmi/) (website no longer
available) to Develop a Federal Information Processing Standard (FIPS)
for the Federal KMI held its first meeting. A [report of the
meeting](http://jya.com/fipsmeet.htm) expressed doubt on the viability
of the process, due to the difference of opinion between business and
government on the need for a key-recovery standard. Various subsequent
meetings were held in 1997 and 1998. In mid-1998, the Committee
announced it could not reach an agreement on a final FIPS
recommendation. The charter of the TACDFIPSFKMI was renewed in August
1998 to conintue work on the requirements for key-recovery products. It
released a report on proposed key-recovery standards, for which comments
could be submitted until 4 November 1999 (website no longer available).

### NRC report

The June 1996 National Research Council study [Cryptography\'s role in
Securing the Information
Society](http://www.nap.edu/readingroom/books/crisis/), which was
requested by Congress, favors widespread encryption. It says the
government should promote widespread commercial use of cryptography. The
government can explore key escrow systems for its own use, but it should
not push others to use it; even if the current many unresolved questions
regarding key escrow were resolved, adoption of escrowed encryption (or
of any other standard) should be voluntary.

### Broad Encryption Policy

The 1 October 1996 [statement by the Vice
President](http://www.epic.org/crypto/key_escrow/clipper4_statement.html),
covering export controls, also refers to domestic crypto use. The
temporary relaxation of export controls is part of a broader encryption
policy, which claims to be broadly consistent with the [NRC
recommendations](#us_4_nrc). Domestic use of key-escrow cryptography
will be voluntary, and the choice of an encryption system remains free.
The government will, however, promote key-escrow cryptography by
expanding the purchase of key-escrow products for itself, promoting
key-escrow cryptography in international discussions, and stimulating
the development of innovative key-escrow products and services. The
Administration will also seek legislation to facilitate commercial
key-escrow, including liability issues for releasing keys.

### Crypto Ambassador

On November 15, 1996, the government appointed ambassador Aaron as
\"special envoy for cryptography\". He will promote international
cooperation and coordinate US contacts with foreign governments on
encryption matters. On 18 June 1997, the Electronic Privacy Information
Center (EPIC) filed a lawsuit to seek public disclosure of the travel
records of ambassador Aaron. EPIC acquired the travel records in January
1998.

### Annual report on criminal crypto use

A 2 October 1996 law (HR 3723) includes an amendment requiring the US
Sentencing Commission to report annually on the use of computer
encryption to conceal criminal activity. Likewise, by law S. 1769 signed
on 2 May 2000, section 2519(2) (b) (iv) of title 18 U.S.C. requires the
Department of Justice to generally report on law-enforcement encounters
with encrypted communications in the execution of wiretap orders. The
President\'s
[Statement](http://www.pub.whitehouse.gov/uri-res/I2R?urn:pdi://oma.eop.gov.us/2000/5/4/4.text.1)
specifies that only general aggregate data on the total number of crypto
encounters will be provided.

### Draft Key Recovery Legislation

At the end of March 1997, a [Draft Key Recovery
Legislation](http://www.cdt.org/crypto/970312_admin.html) dating from 12
March was published: the \"Electronic Data Security Act of 1997\". The
Act would promote a Public Key Infrastructure with key recovery by
registering (private or (foreign) government) Certification Authorities
(CAs) and (private or government) Key Recovery Agencies (KRAs). A
registered CA may only issue a public key certificate if the user
provides a registered KRA with sufficient information to allow timely
plaintext recovery by law-enforcement or national security. KRAs - both
registered and unregistered - shall disclose recovery information to
government agents with a warrant or upon receipt of a written
authorization by the Attorney General. After complaints that use of a
written authorization without judicial review could violate the Fourth
Amendment, in May 1997, the government amended the draft law to clarify
that the same legal criteria would apply for disclosing recovery
information as for wiretapping. The facts of release of recovery
information to government agencies may not be disclosed. Those who
intentionally undermine certain provision of the Act (such as issuing
public key certificates to persons while knowing they do have not
provided sufficient information to a KRA) are subject to civil
penalties; the penalties are limited for registered CAs and KRAs. 

Such
activities are also criminally punishable with up to five years\'
imprisonment. Likewise, the use of encryption in furtherance of the
commission of a criminal offense can be punished with six months\' to
five years\' imprisonment (having used key recovery which is reasonably
available to the government is an affirmative defense). People packaging
encryption products must label them to inform the user whether the
product uses registered KRAs. Finally, the President shall conduct
negotiations with other countries on the mutual recognition of
registered KRAs. The draft legislation affirms that use of any
encryption shall be lawful except as provided in the Act or other law
(which currently means any encryption use is lawful except in
furtherance of a crime), and that use of the key recovery infrastructure
is voluntary. The government is no longer seeking a sponsor for the
draft bill.

The government's [Framework for Global Electronic
Commerce](http://www.whitehouse.gov/WH/New/Commerce/) restates the
(voluntary) key recovery approach. [In a 4 March 1998 letter to Senatory
Daschle, Vice-President Gore reiterated the government\'s commitment to
encouraging voluntary key recovery; it reaffirmed that the
administration will not pursue mandatory key recovery. Rather, the
government will pursue a dialogue between industry and law
enforcement.]{#kerrey}

### Cyberspace Electronic Security Act of 1999

On 16 September 1999, together with the announcement of [export
relaxation](#us_exp9909), the goverment
[proposed](http://www.pub.whitehouse.gov/uri-res/I2R?urn:pdi://oma.eop.gov.us/1999/9/16/16.text.1)
a draft Cyberspace Electronic Security Act of 1999. This contains
provisions on law enforcement accessing crypto keys stored with third
parties, but there is no requirement for users to use key-recovery
crypto. The FBI\'s Technical Support Center will be given \$80 million
over four years, to help law enforcement \"in responding to the
increasing use of encryption by criminals\". Moreover, to ensure \"that
sensitive investigative techniques and industry trade secrets remain
useful\", there will be protections \"from unnecessary disclosure in
litigation and criminal trials involving encryption\", which indicates
that the prosecution should not have to detail how they obtained
decrypted information; such protection should, however, be consistent
with fully protecting defendants\' rights to a fair trial.\
An earlier version of this bill suggested the power to alter \"hardware
or software that allows plaintext to be obtained even if attempts were
made to protect it through encryption\", effectively allowing the
goverment to perform secret break-ins and alterations in computers. This
was not reiterated in the final draft.

### Advanced Encryption Standard

NIST]{#aes} has approved an [Advanced Encryption
Standard](http://csrc.nist.gov/CryptoToolkit/aes/) (AES), FIPS 197, the
successor of DES.\
Minimum acceptability requirements, evaluation criteria, and submission
requirements were discussed at a 15 April 1997 workshop. The object of
NIST was to create a standard with significant advantages over
triple-DES. The standard should use a strong algorithm, regardless of
the legal climate, with a (possibly variable) large key length (at least
128 bits). On 12 September 1997, NIST put out a call for candidate
algorithms. Fifteen proposals were narrowed down to five, of which on 2
October 2000 Rijndael was selected as the draft FIPS. A notice was
published in the Federal Register on 28 February 2001, opening a 90-day
public-comment period. After incorporating minor changes from submitted
comments, Rijndael was officially approved and announced in the [Federal
Register]{href\"http:="" csrc.nist.gov="" cryptotoolkit="" aes=""
frn-fips197.pdf\"=""}, becoming effective on 26 May 2002.

### Domestic Security Enhancement Act 2003 (Patriot II)

A draft Domestic Security Enhancement Act 2003 (Patriot II) of 9 January
2003 leaked out in February 2003 (see the
[text](http://www.dailyrotten.com/source-docs/patriot2draft.html), also
in [pdf](http://www.pbs.org/now/politics/patriot2-hi.pdf)). Section 404
would criminalize the knowing and wilful use of crypto to conceal a
federal crime, with a punishment of up to 5 years for first offenses or
10 years for second or subsequent offenses. The explanatory report
suggests that these \"additional penalties are warranted to deter the
use of encryption technology to conceal criminal activity\". The bill
has not been submitted to Congress.

### Congress Bills

On 16 June 1997, Senators Kerrey, McCain, and Hollings introduced a bill
largely similar to the government draft key-recovery legislation, the
[Secure Public Networks
Act](http://www.cdt.org/crypto/legis_105/mccain_kerrey/billtext.html)
(S. 909). It has similar provisions on registration of CAs and KRAs, on
criminalization of encryption in furtherance of a criminal offense, on
release of recovery information (under broader conditions than the June
amendment to the government bill), on international negotiations, and on
the voluntary nature of the infrastructure. Additionally, it would
require government use and government funding of encryption products to
be based on key recovery crypto, establish an Information Security
Board, and provide a waiver authority for the president in cases
affecting national security. The bill was approved by the Senate
Commerce Committee on 19 June 1997, including several amendments. See
[more information](http://www.cdt.org/crypto/legis_105/mccain_kerrey/)
on the bill by CDT.

An [inofficial proposed amendment](http://jya.com/fbi-tad-s909.htm) to
the Secure Public Networks Act, circulating in the government by the end
of August 1997, would prohibit the manufacture, distribution, sale or
import of non-key recovery cryptography (not its use or possession). The
draft amendment contains several other changes, e.g., dropping the
requirement for CA registration that the CA ensures recovery information
to have been escrowed. In a 3 September 1997 Senate subcommittee
hearing, FBI Director [Freeh backed](http://jya.com/fbi-gak.txt) this
draft legislation, but saying that key recovery should be mandatory, not
voluntary; Commerce Undersecretary Reinsch commented that this was not
the administration\'s policy. According to Jim Bidzos, President Clinton
at a private dinner in September 1997 also stated not to support the
domestic encryption controls being considered in Congress. In February
1998, Kerrey and McCain were said to circulate a somewhat revised
version of their bill, requiring a court order for law enforcement
access, and dropping the link between digital-signature-key
certification and key recovery. [On 4 March 1998, the senators announced
a new version of the bill, which retains the establishment of an
advisory board to decide upon easing export restrictions; in the new
version, the board would consist of eight industry and four government
representatives.]{#goodleah}

Representative Markey introduced a bill on 19 June 1997, the
[Communications Privacy and Consumer Empowerment
Act](http://www.house.gov/markey/privacy.htm) (H.R. 1964). The bill
would prohibit restrictions on the use or sale in interstate commerce of
encryption software, regardless of the medium used or length of
encryption key. Further, the government would be prohibited from
conditioning certificates of authority or certificates of authentication
upon any key escrow system.

Goodlatte\'s SAFE Act ([see above](#lgb_bills)), aimed at relaxing
export controls, was substantially amended by the House Permanent Select
Committee on Intelligence, effectively imposing mandatory key escrow
(the Goss/Dicks amendment). The House Commerce Committee, on 25
September 1997, rejected a similar amendment (Oxley/Manton); instead, it
adopted an amendment by Markey and White to create a National Electronic
Technologies (NET) Center, a federal information clearinghouse on
encryption, which is to assist law enforcement by examining techniques
to facilitate the efficient access to plaintext. Also, the amendment
doubled the penalty for using encryption in furtherance of a felony.
Goodlatte\'s prohibition of mandatory key escrow was maintained by the
Commerce Committee. The SAFE did not make it to a vote in the House,
given the many competing versions, and given that the chair of the House
Rules Committee, Solomon, had declared to only move the Act to the floor
if it contained a mandatory key escrow provision. The SAFE act was
reintroduced in 1999, see below.

The Leahy bill affirms the right of
citizens to use encryption without restrictions in the US (except in
furtherance to a felony to impede law enforcement). The Burns bill ([see
above](#burns)) also affirms the right to freely use encryption;
besides, it would limit the authority of the federal government to set
standards for encryption products used by businesses and individuals,
particularly standards which result in products with limited key lengths
and key escrow. [The E-PRIVACY Act (]{#markey}[see
above](#us_E-PRIVACY)) would similarly prohibit the government from
mandating key escrow or key recovery.

The Leahy bill would penalize the use of
encryption in furtherance to a felony, if the encryption is intended to
obstruct investigation. It creates a framework for key escrow agents,
including strict requirements for law enforcement access; anyone is free
to use non-escrowed cryptography. On June 27, 1995, Senator Grassley
introduced the Anti-Electronic Racketeering Act (S.974), which, if
enacted, would virtually ban encryption. Only the use of escrow-like
software would be an affirmative defense for those prosecuted for using
cryptography. The bill doesn\'t seem to have much support at present.

The [E-PRIVACY
Act](http://www.epic.org/crypto/legislation/eprivacy.html) of Ashcroft
and Leahy, introduced on 12 May 1998, would also penalize using
cryptography to conceal incriminating information in the commission of a
federal felony with 5-10 years\' imprisonment. Like the Markey/White
amendment to the SAFE act (see section above), the bill would create a
NET Center to assist law enforcement. The bill would prohibit the
government from mandating key escrow or key recovery.

On 25 February 1999, Rep. Goodlatte reintroduced the Security And
Freedom through Encryption Act (**SAFE**) (H.R. 850) (see
[above](#safeprotect) for Congressional developments). SAFE would
safeguard everyone\'s right to use cryptography, prohibit the government
from mandating key recovery, and it would penalize crypto use to conceal
criminal conduct. The Commerce Committee, on 23 June 1999, amended the
act, making it a crime not to comply with a decryption order, with
penalties of up to ten years. The Permanent Select Committee (which does
not have jurisdiction over the bill), on 15 July 1999, added a provision
to permit law enforcement to gain access to decryption information with
a warrant.

On 14 April 1999, Sen. McCain introduced the Promote Reliable On-Line
Transactions to Encourage Commerce and Trade (**PROTECT**) Act of 1999
(S. 798) (see [above](#safeprotect) for Congressional developments). The
bill prohibits the government from mandating key recovery. It does not
contain a provision to criminalize the use of crypto to cover up a
crime.

On 27 July 1999, Rep. Goss introduced the *Tax Relief for Responsible
Encryption Act of 1999*(H.R. 2617), which would offer a 15% tax credit
for the costs of developing and producing recoverable cryptography
(i.e., systems which can provide the government with plaintext without
the user\'s knowledge). Also on 27 July 1999, as an alternative to the
[SAFE](#safeprotect3) Act, Rep. Goss introduced the *Encryption for
National Interests Act* (H.R. 2616), which would, among others, allow
domestic use of all crypto, not mandate key recovery, and require a
court warrant for accessing encrypted data or communications.

See the [EFF Privacy, Security, Crypto, Surveillance
Archive](http://www.eff.org/pub/Crypto/) and the [EPIC Key Escrow
Page](http://www.epic.org/crypto/key_escrow/).
