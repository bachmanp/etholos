Selectively share covid-19 test results in a healthcare-commerce solution. Updated 1.1 design based on additional requirements gathered by May 2021. 

As of May 2021 all these URLS  are in different stages of agile scrum.

<li>https://pahisp.org        (general information on  FHIR DSTU4 implementation guide for vaccination credentials, data segmentation for privacy security tags, and alignment to other efforts such as the more mature Mitre/VCI Smart on FHIR Smartcards, Good Health Pass requirements, Linux Public Health development, European Policy and Use cases.</li>
<li>https://covidcleared.org  (developer technology website and minimum viable prototype) Essentially building a vaccination credential app different ways and networking it using different authentication and authorizations technologies, updated as I learn more past the ISO X.500 perspective.</li>
<li>https://covid-19certificate.org (Test environment for identity integration of vaccine credentials) using Open Source</li>
<li>vaccpassport.crypto (web 3 on ethereum blockchain) TBD Prototype to bootstrap project infrastructure by selling NFT's of unique Directory entries based or DID based verified identity used to create vaccination credentials compatible with international standards</li>
<li>https://cequs.com (basic on page information on c=US IP and current owners)</li>

<h3>Current development efforts so far include:</h3>

A c=US version of EU covid-19 certificates (formerly DGC, or "digital green certificates") focused on 3 EU compatible certificates designed for  a European tourism use case based on "freedom to travel" in the Schengen zone. Collaboration via Slack on Linux Public Health and learning various open source Identity Efforts and DHS piloting, funding, and interoperability testing of advanced Identity technology. For example a Mattr plug fest demo  https://www.youtube.com/watch?v=fEBNGj377Vc

EU covid-19 certificates are targeted to EU citizens based on requirements debated in the EU Parliament. EU citizens have certain defined privacy rights eforced by GDPR and national data controllers which are primarily geared to IT systems in which companies are responsible to data controllers. In talks with the IAPP there are issues regarding the former EU-US safe harbor type certifications of US data gathering, national security and data sharing relative to data flows to and from Europe. These data and privacy requirements do not align and relative to privacy requirements in the U.S. a lack of a national privacy law means that individual states have different approaches to vaccination credentials recently making their use illegal in certain states. 

Since the risks are very dynamic it is recommended that any production implmentation get legal and privacy design advice from sources that are experts in European law and privacy where intelligence agencies such as the NSA and public health agencies such as CDC have so far failed to contribute workable design requirements for bio-surveillance programs that remain classified. Like comperable efforts in the airline industry, we in the security industry have to sort out what is actual security and what has been termed "security theater" https://en.wikipedia.org/wiki/Security_theater make people feel more secure without actually meeting risk requirements. It can be inferred that there are multiple channels of information for vaccine credentials, as well as multiple applications at different levels, some of these channels may be confidential due to the nature of regarding pandemics as national security threats.

<h3>Building a scalable risk and threat model</h3>

From lockdowns to vaccines, to ID enabled vaccination documentation the entire world has responded to the pandemic in different ways since Dec 2019. Research into the effects of coronaviruses of course goes back the earlier SARS and MERS outbreaks in which there were lessons learned. From an identity and app perspective, the first wave was a set of contract tracing apps that had varying levels of usefulness. Before that were the concept of "Immunity Passports" back in April of 2020, with the idea that naturally aquired immunity would allow more freedoms from lockdowns. Since so much has happend in over a year, these ideas are still fresh, and developing and various approaches have been tried out and widely covered in news media. THe interoperable vaccine credential, immunity credential, or covid-19 test credential is the latest iteration of this process which has been huge in scope. The virus profoundly affects social interactions and vaccines are allowing us to resume patterns that did not exist during the lockdowns. Good Health Pass has a lot of good questions regarding requirements for an effective interoperable system which to some extent have dependencies on identity systems that are generally designed to be interoperable, but also to provide reduced complexity to users, can be complex in regards to how privacy and security is maintained.

This is because there is a logical different classification of response between naturally occuring disease outbreaks due to viri and weaponized biological agents that have their own history and are thus internationally sanctioned. Our US disease interventions address both scenarios, as well as other casues of mortality and morbidity and this has been a long topical fictionalized subject in books, movies, and games. Zombies have a huge popular following. Fiction and mythology can be an important source of requirements since the spread of various diseases has created cultural responses. While security has been done as theater, theater itself very early on played an important response to governments responding to disease with very little actual technology such as we have now. As valid cultural constructs it is important to place the current situation in historical contexts and also future Science, or Spectulative Fiction contexts that have been imagined. Ignoring those inputs and focusing narrowly on various information sources limits our potential responses to what is known currently, and thus loses context. This is really at the heart of good requirements to see where there are tradeoffs.

X-Keyscore and which should be addressed by the PLCOB, https://plcob.gov, https://nsa.gov but in fact there are classified artifacts in regards to any immunization data sharing design in terms of side channel data flows that remain classified. The rationale for this classification can be easily seen from recent history regarding covid-19 history. WHO never conclusively proved the source of the coronavirus zoonotic crossover from animal (perhaps bat to pangolin) sources to infections in Wuhan, This became rapidly politicized, as to the source and US Government reaction to the pandemic, (including the existing Pandemic Emergency Response Plan dating back to the Bush Administration) of the pandemic. So some immunization resources and as such response stockpiles were geared towards bio-terrorism response (such as Anthrax) which comes with classified elements, as opposed to a well known international pandemic in which the WHO looked at different possible scenarios that took place in Wuhan, including an unknown deliberate or accidental release of a covid virus from the Wuhan biosafety lab, or a natural crossover between species. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8042280/ Since the containment stage of contact tracing by local public health resources failed due inadequate resources, the US experienced community spread, which then required a lockdown stage to prevent cases from overwhelming hospitals. The lockdown stage had severe economic consequences which interacted unevenly with the state public health agencies, and now with increased vaccination levels an electronic tool to indicate covid-19 status to generate commerce has gotten a polticial response, again releated to data privacy and human rights.

The solution addresses SSI or self soverign citizen identity, that has been enhanced with government based identity to reach a NIST level of identity or Identity Assurance Level as specified in NIST 800=63 at IAL level 2.



Etholos forks the EU DGC opensource software (and which is time limited to the pandemic) effort and adds features to make the certificates usable for U.S. citizens in a digital format on a smart phone, and suitable for international travel to Europe to promote tourism revenue to European nations.

The development effort harmonizes national travel credentials from European national countries built in response to the pandemic, IATA integrations based on historical airline health conventions along with NYM based zero knowledge proofs, non profit applications that feature complex rules analyis (largely in the cloud), and self soverign identity with data held on smart phones and verifiable claims that has been data minimized, such as Mitre SMART on FHIR Cards that take valid FHIR Immunization resources obtained from electronic healthcare records software and reduces that data footprint (Data Minimization) via a X.509v3 to CBOR/COSE format to then be scanned by a QR code scanner. 

The general functional requirements and expectations of travellers are:

1. Necessary identification is captured on a smartphone per ICAO profiles for machine readable travel documents and can thus increase assurance level (Commercial Identity Upgrade) relative to the US paper CDC shot card, as well as providing a basis to add the Passport Data using a public key signing process to a verifiable credential https://www.w3.org/TR/vc-data-model/ where the presentation is constrained to attributes necessary for attribute sharing in user defined varied and specific use cases.
3. Since the EU Covid-19 certificate is based on national travel constraints to EU citizens, and also guaranteed rights,  who at the same time largely have access to unique national patient identifiers, the c=US solution creates unique US national (note national in this context does not mean U.S. Government) patient identifiers in an organized, open systems virtual context based on RFC-1218 x.500 and LDAP naming structure. In this context, national organizations, states, hosptitals, localities, that are authoritative for patient identity can "hold" patient identity as they currently do, but with a reduced risk of duplication that leads to medical errors that has been clearly documented over the last thirty years since Patient ID was first built into HIPAA in 1996, and subsequently blocked from government funding due to privacy and security concerns. The solution addresses these issues regarding identity management security, addressed fairly recently by CMS patient renumbering of patient identity away from useage of the SSN, which crosses over to the credit system, and therefore valuable to identity theft. 
5. Compatible and extensible to x.509 certificates in which a shared PKD (public key directory) to verify digital signatures is valuable. Currently UPI unique patient identifiers are not a government provided service in the US versus other countries.
6. A harmonius infrastructure similar to ICAO and thus a "digital covid-19 passport" but not necessarily using the ICAO infrastructure where the Country Level Signing Authority is maintained by the U.S. State Department for official passport use. Holders of valid ICAO e-passports will be able to sign their vaccination data to created a verified credential with the U.S. passport included as an embedded proof.

My Use case is creatively targeted to Iceland as a "reverse travel Viking UX from Vineland (Martha's Vineyard) to Iceland based on optical crystalline digital twinning and navigation by natural polarized light, commonly known as "Iceland Spar navigation", which shows what can be accomplished with natural forces to solve a difficult problem. "Digital Twinning" in particular is applied by IBM to their covid-19 credential application, here it is more of a metaphor for leveraging natural forces relating to physics.

X.509v3 vulnerability and TLS threat models as exposed by old sextant technology navigator Moxie Marlinspike of SIgnal.  Merging sailing and Thomas Pychon in "Against the Day" involving travel across Riemann surfaces, and the "wierd" view of covid-19 variants cast into a string theory model of potential Philip K. Dick VALIS or living intelligence model in which are enountering the covid-19 virus analogous to the rules of Flatland. As such, while we can prime our immune systems to recogize features of the virus, such as spike proteins, variants on the spike protein, create challenges for immunization, and should thus be represented in the travel data model with vaccine variant information.

https://www.science20.com/adaptive_complexity/mindbending_science_thomas_pynchons_mindbending_novel_against_day_part_i-8804

1. Prior exposure to community acquired Covid-19, previously termed an "Immunity Certificate:
2. Current covid-19 status, time based, obtained via testing lab result of PCR test


Reuse existing code and historical cultural precedent to create an open architecture that can be extended by subject matter experts in different communities of interest.

Security and necessary encryption facilitates trust while preventing abuse often present in social media by managing sharing in a Deluzian Thousand Plateau context. Overall permissions are granted by end user, but the services, microservices, are native to the existing environment.

Up to date strategy on the prototype on https://covidcleared.blogspot.com

