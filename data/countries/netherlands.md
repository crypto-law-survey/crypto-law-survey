**Version 27.0, February 2013**

**© Bert-Jaap Koops**

Licensed under Creative Commons Attribution Share Alike 4.0 International.

SPDX-License-Identifier: CC-BY-SA-4.0

## [The Netherlands]{#nl} \[[Sources](cls-srce.htm) 3, 4, 5, 7\]

[**1. Export/ import controls**]{#nl_imp}\
[Wassenaar](#co) rules, including the (pre-December 1998) General
Software Note. (The regulation was to be adapted according to the
December 1998 Wassenaar changes before April 1999.) The applicable
regulations are the 1962 Law on Import and Export (*In- en uitvoerwet*),
the Decree on Export of Strategic Goods and its Annex (*In- en
uitvoerbesluit strategische goederen*), and the 2006 Regulation on
penalisation of unallowed transfer of software and technology of
strategic goods by electronic media, faxes or telephone (*Regeling
houdende strafbaarstelling van ongeoorloofde overdracht van
programmatuur etc.*). All Dutch laws can be found at
[wetten.overheid.nl](http://wetten.overheid.nl).

The licensing authority is the *Afdeling Exportcontrole en
Sanctiebeleid* of the Ministry of Economic Affairs (see
[address](cls-addr.htm)). Technical details of license applications are
reviewed by the *Nationaal Bureau voor Verbindingsbeveiliging*. For more
information, see the Ministry\'s general [export
controls](http://www.rijksoverheid.nl/onderwerpen/exportcontrole-strategische-goederen)
page. 

[**2. Domestic laws and regulations**]{#nl_dom}\
[*Decryption command (law enforcement)*\
If encrypted information is found in a computer during a house
search,]{#nl_decr} the police can order anyone who can reasonably be
supposed to know the means of encryption to decrypt the information
(article 125k section 2 Dutch Code of Criminal Procedure (DCCP)). The
command cannot be given to a suspect, and persons with a right to
non-disclosure can refrain from complying (article 125k para. 3 DCCP).
(Through an oversight of the legislator, the former provision covering
these privileges, art. 125m-old DCCP, was abolished on 1 January 2006
(in the Data Delivery Act, see below) without being replaced,
temporarily - and unintentionally - abolishing the privilege against
self-incrimination in case of decryption orders for 8 months, until it
was repaired by the Computer Crime II Act (*Staatsblad* 2006, 300), in
effect as of 1 September 2006, introducing art. 125k para. 3.)

If encrypted information is found in data delivered to the police on the
basis of data-delivery orders (artt. 126nc-nf, 126uc-uf and 126zk-zn
DCCP), the police can order anyone who can reasonably be supposed to
know the means of encryption to decrypt the information; the command
cannot be given to a suspect, and persons with a right to non-disclosure
can refrain from complying (art. 126nh, 126uh and 126zp DCCP). These
provisions were introduced together with the data-delivery powers in the
Data Delivery Act (*Wet bevoegdheden vorderen gegevens*), *Staatsblad*
2005, 390, in force since 1 January 2006; art. 126zp was introduced by
the Extension of Terrorism Investigation Act (*Staatsblad* 2006, 580)
which allows terrorism investigations without probable cause. The Data
Delivery Act was based on the Mevis Committee on Investigatory Data
Gathering in the Information Society with its May 2001
[report](http://www.minjust.nl/c_actual/rapport/gegevens.pdf) (in
Dutch). According to the report, the proposed data-delivery orders would
include an indication of the way in which the data are to be handed
over, which implies that the data have to be produced in plaintext (see
p. 82).

If encrypted communications were intercepted through wiretapping, the
police can similarly order anyone who can reasonably be supposed to know
the means of encryption to decrypt the communication (art. 126m para. 6,
126t para. 6 and 126zg para. 5 DCCP). The command cannot be given to a
suspect, and persons with a right to non-disclosure can refrain from
complying (paras. 7 and 8). 

Failure to comply with any of these orders is punishable with up to
three months\' imprisonment (art. 184 Dutch Criminal Code).

[*Decryption command (telecom providers)*\
In case of a lawful wiretap, telecoms providers]{#nl_telecom} are
required to undo encryption they themselves have applied, according to
article 2 under e of the Wiretapping of Public Telecommunications
Networks and Services Decree (*Staatsblad* 1998, 642, as adapted by the
Decree of 5 June 2001, *Staatsblad* 2001, 262, available at
[www.overheid.nl/op/](http://www.overheid.nl/op/)).  

[*Decryption command and powers (security services)*]{#nl_dec_sec}\
The Intelligence and Security Services Act 2002 (*Wet op de inlichtingen
en veiligheidsdiensten 2002*, *Staatsblad* 2002, 148, available in Dutch
at [www.overheid.nl/op/](http://www.overheid.nl/op/)), grants a power to
the national-security services to request decryption. Anyone who has
knowledge of the decryption of encrypted data (encountered by security
services when they hack computers (article 24, section 3) or intercept
telecommunications (article 25, section 7)) is required to provide all
necessary cooperation to decrypt upon written request by the head of the
service. Failure to comply with the request is punishable with up to six
months\' imprisonment if it was not intentional, and with up to two
years\' imprisonment if the not-complying was intentional (art. 89).

The services also have the power to install technical provisions in
order to disable encryption of the data stored or transmitted in the
computers they hack (article 24, section 1 at b). Moreover, the
intelligence and security service are granted the power to disable
encryption of data, telecommunications, or data transfers (article 25,
section 1, article 26, section 1, and article 27, section 1).

**3. Developments in cryptography regulation**

[**1994 pre-draft law**]{#nl_1994}\
In March 1994, a Dutch predraft law on cryptography leaked out, the
drift of which was a prohibition of having, using, or trading strong
cryptography. Those with a \"legitimate concern\" could apply for a user
license or a trade authorization. One condition for granting a license
was giving information to an administration agency; the text did not
state whether this information concerned only the algorithm or also all
the keys used.

See the text of the
[Voorontwerp](http://dejoode.org/law/voorontwerp.html) and [Memorie van
Toelichting](http://dejoode.org/law/memorie.html) (in Dutch).

After many protests from those who would be affected by the proposed
regulation, it was withdrawn. The Dutch authorities are currently
studying on alternatives to handle the issue. Although the draft
regulation will not be continued in its present scope, it shows how much
the national-security and judicial authorities fear wide dissemination
of strong cryptography.

At a December 1996 public debate on cryptography, representatives from
the Ministries of Economic Affairs, Transport (responsible for
telecommunications) and the Interior clearly were in favour of the use
of a key-escrow scheme, in line with (their interpretation of) the OECD
discussions. Such a scheme would initially be voluntary and left to
market self-regulation. However, the Ministry of the Interior official
(responsible for national security) stated that, although he did not
think primarily of legislation, in the long run, use of non-escrowed
encryption could give rise to (criminal) suspicion by law-enforcement,
thus effectively mandating escrowed encryption.

**Extension of d**[**ecryption command (law
enforcement**]{#nl_dec_inv}**)**\
Initially, the draft Computer Crime Act II (version of January 1998)
also proposed to extend the power of the police to demand decryption to
be given to suspects, in case of grave evidence against the suspect and
if this is urgently necessary for finding the truth. After protests from
the legal community against this infringement of the privilege against
self-incrimination, this provision was deleted from the draft.

In 2011, however, a discussion on ordering suspects to decrypt
resurfaced in Parliament. The Minister of Security and Justice promised
to look at the UK legislation and to look into the compatibility with
the privilege against self-incrimination (see Letter of 10 June 2011, TK
32500-VI nr. 106, [in
Dutch](https://zoek.officielebekendmakingen.nl/kst-32500-VI-106.html)).
A report commissioned by the Ministry, published in November 2012
(available [in
Dutch](http://www.wodc.nl/onderzoeksdatabase/decryptiebevel-kinderpornografie.aspx),
summary [in
English](http://www.wodc.nl/images/ob305-summary_tcm44-484496.pdf)),
concluded that a decryption order to suspects is not incompatible with
the privilege against self-incrimination, provided that the law and
practice contain sufficient legal safeguards; the report identified
various options in which a decryption order to suspects could be shaped,
with varying forms and degrees of sanctioning non-cooperation. It
recommended that the decryption order could better be shaped according
to the rules for hearing suspects than according to the rules of seizure
of objects (as it is currently shaped in the law), but left it open for
political decision-making whether or not non-compliance should be
sanctioned and if so, what type and degree of sanction should be
applied. The Minister has subsequently announced, in a letter of 27
November 2012 (TK 33400-VI, nr. 68, [in
Dutch](https://zoek.officielebekendmakingen.nl/kst-33400-VI-68.pdf)) an
intention to propose a Bill to introduce a decryption order for suspects
in cases of child pornography or terrorist crimes, which can be given
only in written form, with authorisation from an investigating judge.
Non-cooperation would be sanctioned with a punishment that is
\"substantially higher than the punishment for not following a lawfully
given official order\" (which carries up to three months\'
imprisonment) - the choice for this sanctioning would be motived in the
Bill to follow.

[**Trusted Third Parties policy**]{#nl_ttp}\
A document on TTPs, *Nationaal TTP-project*, was submitted to parliament
on 3 June 1999 (TK 26 581)
([text](http://www.minvenw.nl/dgtp/sctgifs/930731649-1.doc) in Dutch).
This sets a framework for TTPs, proposing a number of preconditions for
TTPs who want to be part of a national TTP Chamber. For TTPs offering
confidentiality services, there is a precondition of \"lawgal access\",
but the document is not particularly clear on what this entails. There
is not a particular requirement for confidentiality TTPs to store or
recover private user keys.

For legal access, a \"partnership approach\" of government and industry
should develop a \"set of instruments acceptable to all parties\" that
ensures government access to encrypted data. This has been attempted in
a project \"Legal Access\" (*Rechtmatige toegang*), in which several
large companies, ministries and security services participated. The
project initially suggested that TTPs offering confidentiality services
would be required to operate in such a way that they could provide
access to their subscribers\' keys or plaintext (see the coordination
group\'s March 2001
[minutes](http://www.bof.nl/tappen/TTPnotulenmaart2001.pdf) in Dutch,
basing themselves on the [technical
report](http://www.bof.nl/tappen/RapportageTWRT.pdf) (in Dutch)).
However, given the economic consequences, it was found to be unfeasible
to establish a self-regulatory mechanism or to require confidentiality
TTPs to store keys. The government therefore decided to refrain from
measures for the time being, in the memorandum *Lawful access: options
deciphered* of 9 December 2002 (TK 26581, nr. 2, available at
[www.overheid.nl/op/](http://www.overheid.nl/op/)).\
Given this outcome, the earlier government threat of legislation
(according to the 1998 TTP document, \"If industry does not participate
sufficiently actively in developing said set of instruments, the
government will emphatically consider to fulfil the need for legal
access with further legislation\") will probably not be acted upon in
the near future.\
The [Mevis Committee
report](http://www.minjust.nl/c_actual/rapport/gegevens.pdf) (see above)
recommends that TTPs be required primarily to decrypt themselves, not to
hand over decryption keys (p. 83).

The overall TTP policy is being implemented in a project called TTP.NL,
with representatives of government and industry, which performs several
pilot projects. See for information in Dutch
[ECP.NL](http://www.ecp.nl/trust/ttp.htm).

**Policy statements emphasising the importance of cryptography**

The government\'s policy document \"Legislation for the electronic
highway\", of 12 February 1998 (TK 25 880), affirms that one of the
premises to be balanced in establishing law enforcement powers is that
the use of cryptography will remain free.

The government Memorandum *Vulnerability on the Internet* (*Nota KWINT*,
TK 26643, nr. 30) of July 2001 states that the government could
stimulate the use of cryptography by serving as a role model and use
cryptographic solutions in its own e-government security policy (p.
27). 

Back to the [Table of Contents](index.html#toc)
