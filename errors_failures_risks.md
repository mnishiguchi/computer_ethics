# Chapter 8 Review Exercises

## Reference
- http://www.iup.edu/WorkArea/DownloadAsset.aspx?id=170833
- http://www.cc.gatech.edu/~harrold/4001/cs4001c_fall2007/Classnotes/Slides/safety/trusting.pdf
- http://esminfo.prenhall.com/computing/baase3e/Baase_Ch8.pdf

## Questions
### 1. Cases in which **insufficient testing** was a factor in a program error or system failure.
- Customer of AT&T lost telephone service for voice and data
    + A three-line change in a two-million-line telecommunications switching program. It was not tested after the modification of those three lines which contained a typo.
- [Denver Airport Baggage System](http://calleam.com/WTPF/?page_id=2086)
    + Underestimation of complexity.
    + The time allowed for development and testing of the system was insufficient.
- [Ariane 5 Explosion](https://www.ima.umn.edu/~arnold/disasters/ariane.html)
    + A 64 bit floating point number relating to the horizontal velocity of the rocket with respect to the platform was converted to a 16 bit signed integer. The number was larger than 32,767, the largest integer storeable in a 16 bit signed integer, and thus the conversion failed.
- Therac-25 incidents
  + Many factors contributed to the injuries and deaths which include lapses in good safety design, insufficient testing, bugs in the software that controlled the machines, and an inadequate system of reporting and investigating the accidents.


### 2. Cases in which the provider did an **inadequate job of informing customers** about flaws in the system.
- Therac-25 incidents
  + In the first overdose incident, when the patient told the machine operator that the machine had “burned” her, the operator told her that was impossible.
  + The number and pattern of problems in this case, and the way they were handled, suggest serious irresponsibility.
- [Denver Airport Baggage System](http://calleam.com/WTPF/?page_id=2086)
  + Some observers criticized BAE for taking on the job when the company should have known that there was not enough time to complete it. Others blamed the city government for poor management, politically motivated decisions, and proceeding with a grandiose but unrealistic plan.


### 3. One cause of the delay in completing the Denver airport
- Underestimation of complexity.
- The time allowed for development and testing of the system was insufficient.


### 4. One case in which reuse of software caused a serious problem
- The first launch of France’s Ariane 5 rocket and “No Fly” lists


### 5. One characteristic of successful high reliability organizations
- Use good software engineering techniques at all stages of development, including specifications, design, implementation, documentation, and testing.
- "Success actually requires avoiding many separate possible causes of failure."
- "We are what we repeatedly do. Excellence, therefore, is not an act, but a habit."


### 6. One principle of human-interface design that is particularly important in safety-critical applications
- Well-designed user interfaces can help avoid many problems. They should include appropriate checking of input to reduce major system failures caused by typos or other errors a person will likely make.


### 7. Many college students attend several colleges before they eventually graduate. It would be a convenience for students if they could order a complete transcript (say, for job applications) from the federal student database. Describe ways in which getting transcripts from the database might be riskier than getting them from the individual colleges.
- One problem would be the risk of losing all the transcript when the single database goes wrong.
- Also, there is a risk of the federal government conveniently using the database for different purposes other than issuing transcripts, which may pose privacy issues.
