**Version 27.0, February 2013**

**© Bert-Jaap Koops**
**Portions © Analog Devices, Inc. **  

Licensed under Creative Commons Attribution Share Alike 4.0 International.

SPDX-License-Identifier: CC-BY-SA-4.0

# [Belgium]{#be} \[[Sources](../sources.md) 1, 3, 5\]

## 1. Export/ import controls  
Belgium requires a license for exporting cryptography outside of the
Benelux. Belgium has signed the [Wassenaar](#Wassenaar) Arrangement,
including the (pre-December 1998) General Software Note.

## 2. Domestic laws and regulations  

### Decryption order  

The *Law on information-science crime* (*Wet van 28 november 2000
inzake informaticacriminaliteit / Loi du 28 Novembre relative à la
criminalité informatique*), [Belgisch Staatsblad / Moniteur
Belge](http://194.7.188.122/cgi/welcome.pl) 2001 - 298, of 28 November
2000 contains a decryption order (see the
[documents](http://www.lachambre.be/cgi-bin/docs.bat?l=n&dir=213) of the
Second Chamber, in Dutch and French). Article 9 creates a new provision
in the Code of Criminal Procedure, Art. 88*quater*. Para. 1 of art.
88quater allows an investigation judge (or others on his order) to order
someone whom he reasonably suspects to have special knowledge of
encryption services to give information on the working or the accessing
of the services or on how to decrypt (literally: how to get the data at
stake in intelligible form). Para. 2 of art. 88quater allows the
investigation judge to order any suitable person to decrypt herself,
within her possibility (lit.: to make accessible the data in the form
ordered by the judge).

Para. 2 stipulates that the order of para. 1 (to give the key or
password) cannot be given to suspects and people with a right to
non-disclosure. Although this seems to suggest, a contrario, that the
order of para. 2 (for the addressee to decrypt herself) *can* be given
to suspects, apparently the provision should be read that neither form
of the decryption order can be given to suspects. (The initial draft of
the law contained a provision in para. 2 that the order of para. 2 could
not be given to suspects, but that the order of para. 1 *could* be given
to suspects, since it was considered compatible with the privilege
against self-incrimination to hand over keys or passwords, referring to
the ECtHR case of *Saunders v. UK*. See *Wetsontwerp inzake
informaticacriminaliteit. Parl. St.* Kamer nrs 213/1 and 214/1,
Explanatory Memorandum, p. 27-28. At some point in the parliamentary
proceedings, the provision was changed; I have not been able to trace
when exactly, or why.)

A refusal of either order is punishable with 6 to 12 months\'
imprisonment and/or a fine of BEF26 to BEF20k. There is a secrecy duty
for professionally involved people. If the ordered persons
unintentionally cause damage to the system or data, the State is civilly
liable for this.

Article 12 of the same law has a more or less similar provision for
intercepted encrypted telecommunications, inserted as section 4 of art.
90*quater* of the Belgian CCP. Here there is no exception for suspects
or persons with a right to non-disclosure, presumably because the
provision apparently addresses telecommunication providers rather than
telecommunications users.

### Program Act  

The *Program Act* (*Programmawet / Loi-programme*) of 30 December
2001, [Belgisch Staatsblad / Moniteur
Belge](http://212.190.77.115/mopdf/2001/12/31_1.pdf#Page34) 2001 of 31
December 2001, inserts a provision, art. 109terE, para. 6,  in the *Law
on the reform of certain economic state companies* (*Wet betreffende de
hervorming van sommige economische overheidsbedrijven*) of 21 March
1991, which may become a prohibition to use cryptography in
telecommunications. The provision reads: \'The king determines (\...)
the technical and administrative measures applicable to (\...)
telecommunication-service subscribers and users, (\...) in order to
prohibit the provision of telecommunications services that prevent or
hamper the measures of the \[wiretap\] Act of 10 June 1998 (\...).\" The
provision will enter into force when the applicable Royal Decree
appears.

Compare also art. 111 of the Act: \"No-one is allowed to establish or
try to establish communications via the telecommunications
infrastructure in the Kingdom that harm the respect for the laws, the
state security, the public order or the good morals or that constitute
an insult to a foreign State.\" Violation of this article is punishable
with imprisonment of one to four years (art. 114 para. 8 Reform Law). 

However, the potential prohibition of article 109terE, para. 6, has to
be read in conjunction with another article in the same Law, art.
109terF. This was inserted on 19 December 1997 (see the [Belgisch
Staatsblad/ Moniteur Belge](http://www.just.fgov.be/) of 30 December
1997) to clear the confusion that an earlier law had caused (see below).
This article states explicitly that the use of encryption is free. The
provision of indicated encryption services to the public is subject to
prior notification (four weeks in advance) to the Belgian Institute of
Post and Telecommunications. The explanatory note states that the
explicit mention that crypto use is free was needed to indicate the
difference with the former law which wanted to subject encryption to
procedures relating to key deposits. In the 1997 law, the government
kept open the possibility of future action to gain access to coded
messages; \"this problem will be reviewed later, having regard to the
development of the technology or of potential abuse of encryption by
mafia organizations or terrorists\".

### History  

In January 1996, Belgium found itself having a law which might
prohibit the use of unescrowed encryption. The law was passed in
December 1994 as part of a larger law and went unnoticed at the time.
The law adds a condition under which telecoms equipment may be seized,
namely in case of end equipment which renders tapping ineffective.

According to this law, crypto systems had to be agreed by the Belgian
Institute for Posts and Telecommunications (BIPT), which some
interpreted as an obligation to deposit keys there. However, a BIPT
spokesman said that \"government does not know the consequences of the
law\". The law was not enforced, but Belinfosec (Belgium Information &
Security) had apparently prepared a report proposing further
specifications and enacting clauses. The regulation had to be further
implemented by Royal Decrees. The Ministry of Justice stated they did
not intend to prohibit encryption as a rule. The law was interpreted by
some as allowing a phone to be disconnected when it uses (hardware)
cryptography end equipment.

Two legislation proposals, by Hatry (in
[French](http://www.senate.be/docs/lex/1/1-343/1-343-1_fr.html) or
[Dutch](http://www.senate.be/docs/lex/1/1-343/1-343-1_nl.html)) and
Bribosia/Maximus (in
[French](http://www.senate.be/docs/lex/1/1-352/1-352-1_fr.html) or
[Dutch](http://www.senate.be/docs/lex/1/1-352/1-352-1_nl.html)) were
submitted to drop the debated provisions of the 1994 law. The proposed
law of Mmes. Bribosia and Maximus additionally tried to solve the law
enforcement problem by requiring everyone who would be able to help in
decrypting to do this, provided the help is necessary for the
investigation.

## 3. Developments to regulate cryptography  

None.

Back to the [Table of Contents](index.md)
