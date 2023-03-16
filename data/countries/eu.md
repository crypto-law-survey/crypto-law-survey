**Version 27.0, February 2013**

**© Bert-Jaap Koops**
**Portions © Analog Devices, Inc. **  

Licensed under Creative Commons Attribution Share Alike 4.0 International.

SPDX-License-Identifier: CC-BY-SA-4.0

## [European Union]{#eu} \[[Sources](cls-srce.htm) 5, 7, 8\]

[**1. Export/ import controls**\
Export of dual-use goods, including cryptography, is regulated by the
*Council Regulation (EC) No 1334/2000 setting up a Community regime for
the control of exports of dual-use items and technology* (*Official
Journal* L159, 30.1.2000), in force since 29 September 2000 \[see also
the Corrigendum, *Official Journal* 2000/176, 15.07.2000\]. This
replaces the earlier 1994 Council Regulation (see below). The Regulation
was amended by Council Regulation]{#eu_exp} (EC) [No
458/2001](http://www.dti.gov.uk/export.control/pdfs/councilregulations.pdf)
of 6 March 2001, OJ 7 March 2001, L65/19 (deleting the 64-bit limit for
symmetric mass-market crypto, see under [Wassenaar](#Wassenaar)), by
Council Regulation (EC) [No
2432/2001](http://www.dti.gov.uk/export.control/pdfs/dual-use-regulation-1101.pdf)
\[beware: large document\] of 20 November 2001, the  Annexes of which
replaced the Annexes to the 2000 Regulation (and by Council Regulation
(EC) [No
880/2002](http://www.dti.gov.uk/export.control/pdfs/8802002.pdf) of 27
May 2002, OJ 29 May 2002, L 139/7, which is not relevant to crypto
controls). The EU regulations follow the [Wassenaar](#Wassenaar)
Arrangement.\
In general, export within the EU is liberalised, and remaining export
licensing procedures are simplified.

-   Export to *other EU countries* is entirely liberalised, with the
    exception of some highly specialised products, such as cryptanalysis
    items. For these items, member states can issue General
    Intra-Community Licenses valid for export to one or more determined
    EU countries, provided basic requirements are met, such as a
    statement of the end use of exported items. For re-exports after
    intra-EU export, an information-exchange mechanism is established.
-   For export to *Australia, Canada, Japan, New Zealand, Norway,
    Switzerland and the US*, a Community General Export Authorisation
    (CGEA) can be applied for, which is valid for export from all EU
    countries.
-   For export to *other countries*. a General National License can be
    applied for (except for cryptanalysis items), which are valid for
    export to one particular country. Otherwise, exporters have to apply
    for an individual license. For mass-market crypto software and
    hardware

**Former regulation**\
The December 1994 EU Council Regulation (EC) No. 3381/94 (amended by
Regulation (EC) 837/95 of 10 April 1995) and EU Council Decision No.
94/942/CFSP (amended by Council Decision 98/232/CFSP and EU Council
Decision 1999/193/GASP), in force since July 1995, regulated the export
of dual-use goods, including cryptography. (According to two judgements
of October 1995 by the European Court of Justice, the European Community
has exclusive jurisdiction in these matters (art. 113 EC Treaty)
\[source: Swedish government communication 1998/99:116\].)

In general, a license was needed for the export of crypto hardware and
software outside of the EU, with the exception of mass-market and
public-domain software. For a transitional period, the Regulation also
required a licence procedure for intra-Community trade of encryption
products. Export to seven \"friendly\" countries (Australia, Canada,
Japan, New Zealand, Norway, Switzerland, USA) seemed to be less
restricted.

The October 1997 Communication of the European Commission *Towards A
European Framework for Digital Signatures And Encryption* ([see
below](#EC%20Framework)) noticed that the Dual-Use Regulation left room
for national implementation and that, consequently, \"a large variety of
domestic licensing schemes and practices exist. These divergences can
lead to distortion of competition.\" The Commission was of the opinion
that the Dual-Use Regulation should be adapted in view of the
requirements of the cryptography market. It advised to:

-   progressively dismantle intra-Community controls on commercial
    encryption products (i.e. not necessarily for very advanced
    encryption);
-   launch a discussion on the scope and interpretation of certain
    provisions, such as the General Software Note (stipulating that
    public-domain software is not subject to controls);
-   deal with problems like intangible means of transmission (such as
    fax or email).

The EU discussed the December 1998 changes in the Wassenaar Arrangement
in order to implement them. ([Denmark](http://jya.com/wass-dk.htm) might
not approve of the new Wassenaar regulations.) By Council Decision
1999/193/GASP (Pub. EG Nr. L73) of 9 March 1999, in force since 18 April
1999, the export list of goods was amended. Then, mass-market crypto
could be exported within the EU on a general license, without
restrictions on key length.

The dual-use regulation was to be replaced by a new regulation by 1
January 1999, according to the *Proposal for a Council Regulation (EC)
setting up a Community regime for the control of exports of dual-use
goods and technology*, COM(1998)257final (*Official Journal* 21 December
1998, 98/C 399/01). According to the proposal, the present regime had
not sufficiently stimulated a convergence of national policies and
practices; it was complex and \"too cumbersome to be useful in
practice\". The main change for cryptography would be that for exporting
crypto products within the EU, export licenses would be replaced by a
simple notification. Also, the controls would now also include export
through intangible means. Eventually, the new regulation was not decided
upon until 22 June 2000.

See for an overview of EU export controls Simo-Pekka Parviainen\'s
[thesis](http://ethesis.helsinki.fi/julkaisut/oik/julki/pg/parviainen/)
on Cryptographic Software Export Controls in the EU, and the [documents
page](http://www.dti.gov.uk/export.control/legislation/ecreg.htm) at
UK\'s DTI. 

**2. Domestic laws and regulations**\
The European Council [Resolution of 17 January 1995 on the lawful
interception of telecommunications
(96/C329/01)](http://www.privacy.org/pi/activities/tapping/eu_tap_resolution_1995.html)
contains a requirement for network operators and service providers, if
they use encryption, to provide intercepted communications to
law-enforcement agencies \"en clair\" (which I interpret as meaning to
provide the signal as they received it, since they cannot undo
encryption by users).

**3. Developments in cryptography regulation**\
The draft *Green Book on the Security of Information Systems* (Draft
4.0, 18 October 1993), which has not been officially adopted by the
European Council, poses a case for the provision of \"Public
Confidentiality Services\" (which would offer some sort of Government
Access to Keys).

In 1996 and 1997, the European Commission was working on a draft
proposal on the establishment of a Europe-wide network of Trusted Third
Party Services (ETS). The network would be established for providing
certification services by private TTP\'s. Although primarily meant for
establishing an infrastructure for the use of public key encryption, the
proposal might also try to address the legal access problem, e.g.,
through key recovery. The studies conducted did not address key recovery
in-depth, but concentrated on issues related to establishing a
public-key infrastructure for digital signatures. The Report on the
results of 1995 TTP projects said that key recovery systems \"can
potentially provide at least part of the answer to the problems raised
by confidentiality functions.\" These \"should be investigated as a
matter of priority, in order to complete the picture of TTP
functionality.\" See the [Infosec
homepage](http://www.cordis.lu/infosec/) and [European Trusted Services
preparatory studies](http://www.cordis.lu/infosec/src/prep.htm). [See
also the]{#bonn} [KRISIS pilot
project](http://www.seven77.demon.co.uk/krisis/).

The 6-8 July 1997 Global Information Networks Conference [Bonn
Ministerial Declaration](http://www2.echo.lu/bonn/final.html) of
European Ministers (from the European Union, EFTA, Central and Eastern
Europe, and Cyprus) echoes the [OECD guidelines](#oecd). It recognizes
the importance of strong cryptography, and declares that crypto products
should be available internationally and users should have free choice,
subject to applicable law. Measures to safeguard lawful access should be
proportionate and effective. Like the OECD guidelines, this leaves ample
room for interpretation (pro or con key recovery). []{#EC Framework}

The European Union has adopted a [Green Paper on Legal Protection for
Encrypted Services in the Single
Market](http://europa.eu.int/en/record/green/gp9603/index.htm), a
discussion proposal on protecting services which are encrypted to ensure
payment of a fee (such as pay television and video-on-demand). The Green
Paper considers proposing a harmonization of national laws to prohibit
the manufacture, sale, importation, possession, and promotion of illicit
decoders, as well as unauthorized decoding. On 9 July 1997, the European
Commission proposed legislation ([directive COM (97)
356](http://www.cl.cam.ac.uk/~mgk25/ca-law/COM-97-356.pdf) (in pdf)) to
this purpose, which would also include online services with conditional
access. Some cryptographers have voiced concern that the proposal might
curb cryptanalytic research. See also Markus Kuhn\'s [critical
page](http://www.cl.cam.ac.uk/~mgk25/ca-law/) on the subject.

With the release in October 1997 of the Communication from the
Commission [Towards A European Framework for Digital Signatures And
Encryption](http://www.ispo.cec.be/eif/policy/97503toc.html), COM (97)
503, the European Commission has chosen a direction away from key
recovery. Building on its April 1997 Communication on Electronic
Commerce, this communication aims at creating a reliable European
framework for digital signatures. It also addresses confidentiality
crypto policy. It stresses the economic and societal importance of
cryptography: \"the public needs to have access to technical tools
allowing effective protection of the confidentiality of data and
communication against arbitrary intrusions. Encryption of data is very
often the only effective and cost-efficient way of meeting these
requirements.\" The Commission is concerned that restrictions on
encryption affect the right to privacy, its effective exercise and the
harmonisation of data protection laws in the Internal Market. Also,
\"divergence between regulatory schemes might result in obstacles to the
functioning of the Internal Market.\"

The Commission is wary of key recovery issues. \"Key escrow or key
recovery raise a number of practical and complex questions that policy
makers would need to solve, in particular issues of privacy,
vulnerability, effectiveness and costs. If at all required, regulation
should be limited to what is absolutely necessary. Regulation would also
need to distinguish between a multitude of possible key types (storage
keys, session keys, authentication keys, etc.).\" The Commission will
examine whether national restrictions are totally or partially
justified, notably whether they are proportionate, taking into account
the provisions on the free circulation of goods in the Internal Market,
and the requirements of the Data Protection Directive. Also, regulations
should distinguish authentication services from confidentiality
services. The Commission invites the Council of the European Union to
initiate a debate on encryption issues. (In its [Ninth
Report](http://www.parliament.the-stationery-office.co.uk/pa/cm199798/cmselect/cmeuleg/155ix/el0924.htm),
the Select Committee on European Legislation considered that this
Communication does \"not raise questions of legal or political
importance\".)

At the [RSA Data Security
Conference](http://www.news.com/News/Item/0,4,18079,00.html), January
1998, Detlef Eckhert of the European Commission (DGXIII) said that no
regulation is planned for the EU.

EU ministers of Justice and Home Affairs were reported to have agreed
that law enforcement agencies must have access to keys or plaintext, at
a conference in Birmingham, January 1998. The UK prepared a policy paper
for the EU in February 1998, stating that it may be necessary for law
enforcement to have lawful access in certain circumstances, which may be
either overt (i.e., demanding decryption) or covert (probably through
key recovery). The Council of Ministers, on 28 May 1998, decided to
monitor closely the use of cryptography by serious criminals and
terrorists; it recognised the promotion of key escrow as a possible
approach to meet law-enforcement needs. Also, law-enforcement agencies
may require access to decryption keys necessary to decrypt seized
material. The Council agreed to prepare a Resolution on Encryption and
Law Enforcement \[source: Swedish government communication
1998/99:116\].

ETSI (European Telecommunications Standardisation Institute) worked on a
standard for Trusted Third Parties. Part of the standard would relate to
lawful access to encrypted data. Great Britain was reported to have
pushed here for its Royal Holloway scheme (for key escrow) to be used as
a basis, but in early 1998, an interim draft to this purpose was
rejected by ETSI.

More recently, several other EU documents call for wider use of
encryption as a tool to protect European citizens. The [Draft
report](http://www.europarl.eu.int/tempcom/echelon/pdf/prechelon_en.pdf)
of the Temporary Committee on the Echelon Interception System of 18 May
2001 recommends \"appropriate measures to promote, develop and
manufacture European encryption technology and software and above all to
support projects aimed at developing user-friendly open-source
encryption software\" and \"The European institutions and the public
administrations of the Member States are called upon systematically to
encrypt e-mails, so that ultimately encryption becomes the norm.\"\
The Commission Communication on Improving the Security of Information
Infrastructures and Combating Computer-related Crime of 26 January 2001,
COM(2000) 890 final, affirms that the Commission will promote \"the
availability of products and services with an appropriate level of
security and encouragement of a more liberalised use of strong
encryption through a dialogue amongst all interested parties.\" The
draft Proposal for a Recommendation on security of infrastructures and
combating computer-related crime of 18 June 2001 calls for promoting
\"European research in encryption software to improve the possibility of
self-defence by consumers\".

Back to the [Table of Contents](index.html#toc)
