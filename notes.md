Evolutionary Architecture
=========================

- 2 Kinds of Chnage:
    - technology driven
        - evolutionary architecture
    - business driven
        - Agile is for buiness/domain-driven change
- Why predict the future?
    - When change is difficult / expensive
    - dont have to be
- goals are good, but how do you know, that you come nearer to the goal
    - how can you tell, that you don't degrade
- ea depends on agile
    - devops
    - ci/cd
    - makes ea easier
- ff fix requirements: Implementations can change, but only within the boundaries, that is given by the fitnesse functions
- ff are:
    - monitors -> Continous ff
    - unit/functional tests
    - metrics
    - chaos engineering
- ff categories
    - triggerd
    - continous
    - static 
    - dynamic
        - rely on a shifting definition based on extra context. 
    - automatic
    - manual
    - temporal / time-based
    - domain-specific
        - Most are unit/function/acceptance tests
    - intentional
        - before the design
    - emergende
        - discover while dev / ops -> As you build the system
        - ff is a living part of the system. It evolves with it
- ff != test
    - ff: architectural characteristics
    - unit/UAT/function for tests for the problem domain
- Fitness-Functions are for non-functional requirements, unit/UAT/func tional test for functional requirements?
- Chaos monkey for flipping the dependency: Not longer dependend to Amazon, which is not controlled by netflix. So they became independend
- FF as executable Specification

- component is physically (module not). Component consists of multiple modules
- Smaller Quantum Size implies Evolutionary
- And more evolutionary leads to less 10%-Danger, because you can evolutionate away from it? If true: smaller Quantum Size leads to less risk of 10%-Trap?
    - Hybrits can bring you out of the trap: For example 

- Put in Practice:
    1. Identify dimesions
        - NO ivy tower!
    2. Define functions
    3. Usse deployment piplines and/or continous fitness functions
        - Pipleine + Monitoring
    Repeat

- FF in Deployment Pipeline
- Stages of CI Pipleine can use different Repos. For example for Security-STage: Only one repo has to be changed. Multiple Dimension Moularization.
    - SEcurity
    - Code-STyle
    - Mem-Checks
    - 




Day 2
-----

- EA allowes Experiments
    - Hypothis-Driven-Development
- Innovations Dilemma
    - The future is already here, it is just not equali distributed
- Books
    - Contionous Delivery
    - Lean Entrprise
    - Refactoring Databases
    - Intrastructure as Code
    - Release it
    - Evolutionary Archtitecure
- At leas Continouse Integration
    - 1. CI
    - 2. Continous Delivery
        - Contionous Delivery can have manual steps and does not update the system automatically
        - Continous Deployment no more manual steps
    - 3. Evolutionary Architecture
- Only know anything: Run experiment --> The sientific method
- cycle-time: Total time between check-in and running in productionclea
- process-ff
- smoke-test: Just see a little bit
- deployment-pipeline can measure cycle-times
    - cloud-bees for jenins
- More and more stable tests
- cycle-time-guard
    - prevent degrading
- simon brown: Modular Monolith
- The more reusable, the less usable
- service-templates
- FF also just test a single thing
- FF should be as local as possible 
- Teams should own the pipelines, architects should support
