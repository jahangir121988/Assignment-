# Assignment-software engineering 
 Summary 1

*Uncertainty Modeling and Evaluation for Dependable IoT Cloud Systems Design*
_Who
Luca Berardinelli, Hong-Linh Truong
Track
ISSTA 2020 TAV-CPS/IoT
When
Sun 19 Jul 2020 10:00 - 10:30 at Zoom - TAV-CPS/IoT Workshop_

     Developing dependable complex applications using IoT and cloud services is very challenging. Using service APIs and client libraries the developer can glue various software capabilities to build complex IoT Cloud applications but the developer also needs to arbitrarily extend and model functional and quality aspects of new components, connectors, and their interactions. Hence, knowledge about existing IoT Cloud and modeling is crucial. However, due to the lack of knowledge and the complexity of IoT Cloud Systems, the developer might introduce or might not be able to detect various types of uncertainties, which strongly influence the application. In this talk we aim at detecting such uncertainties and recommend software design to deal with such uncertainties as early as possible. We model and evaluate potential uncertainties on design artifacts representing structural and/or behavioral information about the system under study. We propose a rule-based Uncertainty Modeling and Evaluation methodology (UME) and tool (T4UME) to help users in detecting potential uncertainties on design artifacts and to decide whether or not refactoring strategies should be applied to uncertain system design artifacts. In particular, our framework deals with uncertainty as a crosscutting, multidisciplinary concept by providing proper extension and customisation mechanism to suitably tailor its adoption to different 



Summary 2

   *Efficient Testing of Cyber-Physical Systems*
Who
Jun Sun, Zijiang Yang
Track
ISSTA 2020 TAV-CPS/IoT
When
Sun 19 Jul 2020 10:30 - 11:00 at Zoom - TAV-CPS/IoT Workshop
     
        Cyber-physical systems (CPSs) play a critical role in automating public infrastructure and thus attract wide range of attacks. Assessing the effectiveness of defense mechanisms is challenging as realistic sets of attacks to test them against are not always available. In this short paper, we briefly describe smart fuzzing, an automated, machine learning guided technique for systematically producing test suites of CPS network attacks. Our approach uses predictive machine learning models and meta-heuristic search algorithms to guide the fuzzing of actuators so as to drive the CPS into different unsafe physical states. The approach has been proven effective on two real-world CPS testbeds.




      Summary 3 
  
    *A Programming Model for Semi-implicit Parallelization of Static Analyses*
Who
Dominik Helm, Florian Kübler, Jan Thomas Kölzer, Philipp Haller, Michael Eichberg, Guido Salvaneschi, Mira Mezini
Track
ISSTA 2020 Technical Papers
When
Wed 22 Jul 2020 12:30 - 12:50 at Zoom - STATIC ANALYSIS AND SEARCH-BASED TESTING Chair(s): Daniel Kroening
     
        Parallelization of static analyses is necessary to scale to real-world programs, but it is a complex and difficult task and, therefore, often only done manually for selected high-profile analyses. In this paper, we propose a programming model for semi-implicit parallelization of static analyses which is inspired by reactive programming. Reusing the domain-expert knowledge on how to parallelize analyses encoded in the programming framework, developers do not need to think about parallelization and concurrency issues on their own. The programming model supports stateful computations, only requires monotonic computations over lattices, and is independent of specific analyses. Our evaluation shows the applicability of the programming model to different analyses and the importance of user-selected scheduling strategies. We implemented an IFDS solver that was able to outperform a state-of-the-art, specialized parallel IFDS solver both in absolute performance and scalability.
