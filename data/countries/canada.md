**Version 27.0, February 2013**

**© Bert-Jaap Koops**

Licensed under Creative Commons Attribution Share Alike 4.0 International.

SPDX-License-Identifier: CC-BY-SA-4.0

## [Canada]{#ca} \[[Sources](cls-srce.htm) 1, 3, 4, 5, 8\]

**1. Export/ import controls**\
Canada follows (pre-December 1998) [Wassenaar](#co) regulations. The
export of items from Canada may be subject to restriction if they are
included on the Export Control List. In December 1996, Canada granted
export of 56-bit cryptography to most countries for a twelve-month trial
period; this has been extended until 30 June 1998. Mass-marker and
public-domain software is excluded from the controls.

All types of cryptography can be transported between Canada and the
United States, but cryptography imported from the US which is not
otherwise included in the Export Control List remains under US
[export](#ear) rules and cannot be exported from Canada if the US does
not allow export. Public domain and mass-market software can be freely
exported, but if it contains US-origin goods, paperwork must be filled
out.

A discussion paper by the Task Force on Electronic Commerce, from
February 1998, [A Cryptography Policy Framework for Electronic
Commerce](http://strategis.ic.gc.ca/SSG/cy00005e.html), invited
discussion over a review of Canada\'s crypto policy, including export
controls. It presented three policy options:

-   relax controls either by matching the most liberal export policies
    of other countries, or through recognition of the availability of
    similar-strength crypto products in foreign markets;
-   maintain the existing policy;
-   extend the export controls by adding mass-market and public-domain
    software, possibly with a relaxation for key recovery products.

An [analysis](http://e-com.ic.gc.ca/english/crypto/631d3.html) of the
189 responses to the discussion paper was published on 28 September
1998. Most respondents favored relaxing controls on the export of
cryptography.

Immediately following this publication, the government announced a new
cryptography policy on 1 October 1998 (available at [Industry
Canada](http://strategis.ic.gc.ca/SSG/cy00001e.html)). Industry Minister
[John Manley affirmed](http://jya.com/ca-crypto.htm) the government\'s
commitment to the Wassenaar Arrangement. However, the export controls
would take into account the practices of other countries, so that they
are not more restrictive than those of, in particular, the US, which had
relaxed exports for certain sectors in September 1998. Furthermore, the
export-permit process would be streamlined. For many products, users, or
destinations, after a one-time review, general or multi-destination,
multi-user permits would be issued.

See the relevant [sections of the Export Control
List](http://axion.physics.ubc.ca/ECL.html) and [a summary of Canada\'s
export controls on cryptographic
software](http://insight.mcmaster.ca/org/efc/pages/doc/crypto-export.html).
Cf. also Baker and Hintze\'s [comparison of US and Canada export
controls](http://www.steptoe.com/encryp.htm).

**2. Domestic laws and regulations**\
There are no domestic regulations on cryptography.

**Case-law**\
In R. v. Meron, \[2004\] P.E.I.J. No. 95, the accused was asked to
provide passwords for encrypted hard drives, but he refused to
cooperate. The case gives no further details about the context or
consequences.

In [R. v.
Beauchamp](http://www.canlii.org/en/on/onsc/doc/2008/2008canlii27481/2008canlii27481.html),
2008 CanLII 27481 (ON SC), the defence requested disclosure of hard
drives that had been seized by the police. Part of these were encrypted.
The court held that the integrity of the administration of justice
cannot be maintained by providing a copy to the defence of encrypted
files, *inter alia* because the Crown cannot exercise its discretion to
protect individuals\' privacy interest or to prevent further criminal
acts from being committed or facilitated when handing over the data.
Hence, the application for disclosure of a copy of the encrypted files
in the seized hard drives was refused.

**3. Developments in cryptography regulation**\
A discussion paper by the Task Force on Electronic Commerce, from
February 1998, [A Cryptography Policy Framework for Electronic
Commerce](http://e-com.ic.gc.ca/english/crypto/631d11.html), invited
discussion over a review of Canada\'s crypto policy. It presented
options for reviewing the domestic policy on encryption of stored data
and on encryption of real-time communications.

For domestic encryption of *stored data*, the paper suggested the
following options:

-   a laissez-faire model: continue with current policies and leave
    everything to the market;
-   a minimum standards approach: encourage crypto users to store
    back-up crypto keys or to provide business data recovery; this would
    be done by stimulating industry self-regulation, and possibly
    through using the government\'s PKI (see below) to only
    cross-certify private crypto service providers that comply with the
    minimum standards;
-   mandatory access legislation through prohibiting non-key recovery
    cryptography.

For domestic encryption of *real-time communications*, the paper
suggested the following options:

-   maintain the status quo, that is, telecom carriers are required to
    decrypt to the extent they are able to, and the only telecom
    carriers required for law enforcement and national security reasons
    to undo encryption they themselves employ are the new wireless
    providers of personal communications services and local multipoint
    communications services (the other carriers are currently not
    required to keep back-up copies of session keys);
-   obligations on all carriers: require that all federally regulated
    telecommunications carriers providing encryption services retain the
    ability to decrypt for law enforcement and national securities
    agencies on receipt of a court order; this would be extended to
    provincially regulated service providers, but would not affect
    Internet service providers;
-   mandatory controls: in addition to the second option, crypto service
    providers would be obliged to provide mandatory assistance for
    decryption, and users would be prohibited from using non-key
    recovery crypto.

An [analysis](http://e-com.ic.gc.ca/english/crypto/631d3.html) of the
189 responses to the discussion paper was published on 28 September
1998. Most respondents favored relaxing controls on the use of
cryptography.

Immediately following this publication, the government announced a new
cryptography policy on 1 October 1998 (available at [Industry
Canada](http://e-com.ic.gc.ca/english/crypto/631d1.html)). Industry
Minister [John Manley
affirmed](http://e-com.ic.gc.ca/english/releases/41d6.html) the freedom
to develop and use cryptography products. The government will not
implement mandatory key recovery or a mandatory licensing regime for
TTPs. The government does, however, encourage industry to use
key-recovery techniques for stored data, and it will use government
procurement to encourage commercial key escrow by acting \"as a model
user of cryptography\". Finally, the government proposes to make it an
offense to \"wrongfully disclose private encryption key information and
to use cryptography to commit or hide evidence of a crime.\" Moreover,
\"warrants and assistance orders also apply to situations where
encryption is encountered - to obtain the decrypted material or
decryption keys.\"

See the [summary](http://e-com.ic.gc.ca/english/fastfacts/43d7.html) of
Canada\'s crypto policy.

Back to the [Table of Contents](index.html#toc)
