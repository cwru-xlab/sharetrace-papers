# ShareTrace publications

1. Untitled Master's Thesis (WIP) of [@rtatton](https://github.com/rtatton)
   - Builds upon [2]:
      - Contextualizes ShareTrace as a mobile-crowdsensing application
      - Reformulates the ShareTrace algorithm in an online setting within the formal actor model
      - Proposes an application of local differential privacy to allow centralized population-level risk aggregation
      - Evaluates message reachability accuracy, efficiency, and scalability (similar to [2])
      - Evaluates the relationship between message passing, temporal concurrency, and user/contact data distributions
   - [Code implementation](https://github.com/cwru-xlab/sharetrace-akka)
2. ShareTrace: Contact Tracing with the Actor Model ([arXiv](https://arxiv.org/abs/2203.12445v3),[IEEE](https://ieeexplore.ieee.org/document/9982762/))
   - Newer version of [3]
   - [IEEE HealthCom 2022 Conference slides and presentation](https://github.com/cwru-xlab/sharetrace-healthcom22)
   - [AI-HAPP Pandemic Preparedness 2023 Workshop slides](https://github.com/cwru-xlab/sharetrace-ai-happ23)
3. [ShareTrace: Contact Tracing with Asynchronous, Parallel Message Passing on a Temporal Graph](https://arxiv.org/abs/2203.12445v2)
   - Non-iterative, asynchronous formulation of [4] using subnetwork actors (based on the distributed extension)
   - Proposes message reachability to quantify message-passing complexity on a temporal network
   - Evaluates message reachability accuracy, efficiency, and scalability
   - [CHIL 2022 Conference Poster](https://github.com/cwru-xlab/sharetrace-chil22)
   - [Code implementation](https://github.com/cwru-xlab/sharetrace-ray)
4. [ShareTrace: An Iterative Message Passing Algorithm for Efficient and Effective Disease Risk Assessment on an Interaction Graph](https://doi.org/10.1145/3459930.3469553)
   - Original design of the ShareTrace algorithm
   - Evaluates efficacy
   - Proposes a distributed extension
5. [ShareTrace: A Smart Privacy-Preserving Contact Tracing Solution by Architectural Design During an Epidemic](https://github.com/cwru-xlab/sharetrace-papers/blob/373abf36b05227f4a5f5cb405cd61e8dc225a9a6/sharetace-whitepaper.pdf)
   - Original whitepaper
