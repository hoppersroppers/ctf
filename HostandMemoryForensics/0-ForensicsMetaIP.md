# Forensics Meta IP
##  [Register for the Free Course Today!](https://www.roppers.org/courses/ctf)
Resources:

* http://www.abchs.com/xsecure/chs/coursedocs/SSI_R1/pdf/DigitalForensics.pdf
* http://www.forensichandbook.com/locards-exchange-principle/
* http://science.howstuffworks.com/locards-exchange-principle2.htm
* http://www.forensicdna.com/assets/the_origin_of_evidence.pdf
* https://www.law.cornell.edu/wex/daubert_standard
* http://www.forensicsciencesimplified.org/legal/daubert.html
* https://www.law.cornell.edu/wex/frye_standard
* http://www.forensicsciencesimplified.org/legal/frye.html


## Theory:

### Explain the scientific method and Locard?s Exchange Principle, and how they are both relevant in the digital world.

What is the scientific method?

* Controlled variables in order to establish repeatability

What is Locard?s Exchange Principle?

* Every time you make contact with another person, place, or thing, it results in an exchange of physical materials. At the same time, you will also take something away from the scene with them.

* How are they relevant in the digital world, especially in digital forensics? Give examples.

### Explain the six parts of the Inman-Rudin Paradigm

* Transfer, identification, individualization, association between source and target, the divisibility of matter, and reconstruction

Which was added by Inman-Rudin?
* Divisibility of matter

### Explain the Frye and Daubert Standards, the differences between them, and which is more prevalent

What is the Frye Standard?

* Frye Standard means that an expert opinion based on a scientific technique is admissible only where the technique is generally accepted as reliable in the relevant scientific community.

What is the Daubert Standard?

* Daubert Standard means evidence must be the product of sound "scientific methodology" derived from the scientific method

What is the difference between them?

* Difference is ?accepted? vs. ?sound scientific methodology?

Which is the modern standard?

* Daubert is the modern standard

### Walk through the collection steps and explain the order of triage and why, using terms of order of volatility.

     -  Where is the evidence?  List what systems were involved in the
         incident and from which evidence will be collected.

      -  Establish what is likely to be relevant and admissible.  When
         in doubt err on the side of collecting too much rather than not
         enough.

      -  For each system, obtain the relevant order of volatility.

      -  Remove external avenues for change.

      -  Following the order of volatility, collect the evidence with
         tools as discussed in Section 5.

      -  Record the extent of the system's clock drift.

      -  Question what else may be evidence as you work through the
         collection steps.

      -  Document each step.

      -  Don't forget the people involved.  Make notes of who was there and what were they doing, what they observed and how they reacted.

What is the order of volatility? 
     -  registers, cache

      -  routing table, arp cache, process table, kernel statistics,
         memory

      -  temporary file systems

      -  disk

      -  remote logging and monitoring data that is relevant to the
         system in question

      -  physical configuration, network topology

      -  archival media

Why is it important to follow this order of triage?

Explain the importance of chain of custody, write blockers, and hashes.

* What is a chain of custody and why is it important?
* What are write blockers and why are they important?
* What are the two main uses of hashes in a forensics case?
