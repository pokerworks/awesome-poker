# Awesome Poker [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Poker as a discipline: software, research, game theory, solvers, engines, hand histories, datasets, tools, and high-quality learning resources.

Maintained by [PokerWorks](https://pokerworks.io) as a community resource. Inclusion is based on relevance, quality, usefulness, and maintenance, not affiliation.

## Contents

- [Libraries & Toolkits](#libraries--toolkits)
- [Game Engines & Platforms](#game-engines--platforms)
- [Solvers](#solvers)
- [AI, Game Theory & Research](#ai-game-theory--research)
  - [Frameworks & Environments](#frameworks--environments)
  - [Landmark Systems & Papers](#landmark-systems--papers)
  - [Algorithms & Methods](#algorithms--methods)
- [Hand Histories, Formats & Standards](#hand-histories-formats--standards)
  - [Formats & Protocols](#formats--protocols)
  - [Parsers & Converters](#parsers--converters)
- [Datasets & Corpora](#datasets--corpora)
- [Fairness, RNG & Security](#fairness-rng--security)
- [Tracking & Analysis](#tracking--analysis)
- [Competitions & Benchmarks](#competitions--benchmarks)
- [Client & UI Assets](#client--ui-assets)
- [Rules, Math & References](#rules-math--references)
- [Learning & Education](#learning--education)
- [Communities & Research Groups](#communities--research-groups)
- [Notes](#notes)

## Libraries & Toolkits

- [PokerHandEvaluator](https://github.com/HenryRLee/PokerHandEvaluator) - High-performance evaluator for 7-card, Omaha, and Monte Carlo equity workloads.
- [PokerKit](https://github.com/uoftcprg/pokerkit) - Multi-variant Python toolkit for simulation, state tracking, hand history notation, and statistical analysis.
- [OMPEval](https://github.com/zekyll/OMPEval) - Fast C++ evaluator and equity calculator for Hold'em and Omaha simulations.
- [PokerStove](https://github.com/andrewprock/pokerstove) - Classic C++ range enumeration and equity-calculation software.
- [pokersolver](https://github.com/goldfire/pokersolver) - JavaScript hand solver for ranking, comparing, and explaining poker hands in browser or Node.js apps.
- [chehsunliu/poker](https://github.com/chehsunliu/poker) - Go package for parsing cards and evaluating poker hands.
- [eval7](https://github.com/julianandrews/pyeval7) - Python and Cython evaluator with PokerStove-style range parsing and equity-calculation helpers.
- [treys](https://github.com/ihendley/treys) - Pure Python evaluator for fast Hold'em hand ranking and simulations.
- [rs-poker](https://github.com/elliottneilclark/rs-poker) - Rust library for hand ranking, card enumeration, and poker-agent experiments.

## Game Engines & Platforms

- [PokerTH](https://github.com/pokerth/pokerth) - Mature open-source Texas Hold'em game with desktop clients and network play.
- [OddSlingers](https://github.com/Monadical-SAS/oddslingers.poker) - Full-stack Django and React codebase behind an open-source online poker platform.
- [PyPokerEngine](https://github.com/ishikota/PyPokerEngine) - Python engine for building, testing, and benchmarking poker agents.
- [MIT Pokerbots Engine](https://github.com/mitpokerbots/engine) - Template engine for the MIT Pokerbots autonomous pokerbot competition.
- [poker-ts](https://github.com/claudijo/poker-ts) - TypeScript table model for running Texas Hold'em games.
- [clubs](https://github.com/fschlatt/clubs) - Python engine for arbitrary community-card poker variants.

## Solvers

- [TexasSolver](https://github.com/bupticybee/TexasSolver) - Open-source Texas Hold'em GTO solver with a desktop interface and short-deck support.
- [poker_solver](https://github.com/noambrown/poker_solver) - No-limit Texas Hold'em river solver using counterfactual-regret variants.
- [slumbot2019](https://github.com/ericgjackson/slumbot2019) - CFR implementations from the Slumbot author for Hold'em-like poker games.
- [PioSOLVER](https://piosolver.com/) - (Commercial) Desktop Hold'em solver for building trees, running solves, and analyzing postflop strategies.
- [GTO+](https://www.gtoplus.com/) - (Commercial) Hold'em solver for building decision trees and recalculating turn or river branches.
- [GTO Wizard](https://www.gtowizard.com/) - (Commercial) Cloud platform for solver libraries, trainers, hand review, and custom solving.
- [MonkerSolver](https://monkerware.com/solver.html) - (Commercial) Solver used for Omaha, Hold'em, and multi-way game-tree analysis.

## AI, Game Theory & Research

### Frameworks & Environments

- [RLCard](https://github.com/datamllab/rlcard) - Reinforcement-learning environments for poker variants such as Leduc, Limit Hold'em, No-Limit Hold'em, and Dou Dizhu.
- [OpenSpiel](https://github.com/google-deepmind/open_spiel) - General game-theory research framework with imperfect-information poker environments and solver algorithms.
- [PokerRL](https://github.com/EricSteinberger/PokerRL) - Multi-agent poker reinforcement-learning framework with Deep CFR, NFSP, and distributed training support.
- [neuron_poker](https://github.com/dickreuter/neuron_poker) - OpenAI Gym Texas Hold'em environment with rendering, Monte Carlo equity calculation, and reinforcement-learning agents.

### Landmark Systems & Papers

- [Cepheus](https://www.science.org/doi/10.1126/science.1259433) - Science article describing the essential weak solution of heads-up limit Texas hold'em.
- [DeepStack](https://arxiv.org/abs/1701.01724) - Depth-limited solving system with neural counterfactual value estimation for heads-up no-limit Texas hold'em.
- [Libratus](https://www.ijcai.org/proceedings/2017/772) - Carnegie Mellon system for superhuman heads-up no-limit Texas Hold'em.
- [Pluribus](https://www.science.org/doi/10.1126/science.aay2400) - Superhuman six-player no-limit Texas hold'em system from Brown and Sandholm.
- [Student of Games](https://arxiv.org/abs/2112.03178) - Unified algorithm for strong play in perfect- and imperfect-information games, including heads-up no-limit Hold'em.
- [AlphaHoldem](https://ojs.aaai.org/index.php/AAAI/article/view/20394) - End-to-end reinforcement-learning framework for heads-up no-limit Texas Hold'em.

### Algorithms & Methods

- [Counterfactual Regret Minimization](https://poker.cs.ualberta.ca/publications/NIPS07-cfr.pdf) - Foundational regret-minimization algorithm for large imperfect-information games.
- [Neural Fictitious Self-Play](https://arxiv.org/abs/1603.01121) - Deep reinforcement-learning method for approximating Nash equilibria in imperfect-information games.
- [Deep Counterfactual Regret Minimization](https://arxiv.org/abs/1811.00164) - Deep CFR method for scaling counterfactual-regret minimization with neural approximation.
- [ReBeL](https://arxiv.org/abs/2007.13544) - Reinforcement learning and search framework for imperfect-information games, evaluated on heads-up no-limit Texas hold'em.

## Hand Histories, Formats & Standards

### Formats & Protocols

- [Poker Hand History File Format Specification](https://phh.readthedocs.io/) - PHH specification for machine-readable hand histories across poker variants.
- [Recording and Describing Poker Hands](https://arxiv.org/abs/2312.11753) - Paper introducing the PHH format for recording poker hands across variants.
- [Open Hand History](https://hh-specs.handhistory.org/) - JSON hand-history specification for standardizing online poker hand data across operators and analysis tools.
- [ACPC Protocol Specification](https://pokerkit.readthedocs.io/en/stable/_static/protocol.pdf) - Protocol reference for dealer-to-player messages used by Annual Computer Poker Competition tooling.

### Parsers & Converters

- [Hand History Parser](https://github.com/poker-apprentice/hand-history-parser) - TypeScript parser for online poker hand histories, published as `@poker-apprentice/hand-history-parser`.
- [pluribus-hand-parser](https://github.com/VitamintK/pluribus-hand-parser) - Parser for the public Pluribus hand-history release.

## Datasets & Corpora

- [PHH Dataset](https://zenodo.org/records/17136841) - Multi-variant poker hand-history corpus published in the PHH format.
- [IRC Poker Database](https://poker.cs.ualberta.ca/irc_poker_database.html) - Historical corpus of more than 10 million online poker hands collected on IRC from 1995 to 2001.
- [Official ACPC Match Logs](http://www.computerpokercompetition.org/downloads/competitions/) - Download index for Annual Computer Poker Competition match logs and benchmark data across multiple years.
- [PokerBench](https://huggingface.co/datasets/RZ412/PokerBench) - No-limit Texas Hold'em decision-making dataset with solver-labeled preflop and postflop scenarios.

## Fairness, RNG & Security

- [NIST SP 800-90A](https://www.nist.gov/publications/recommendation-random-number-generation-using-deterministic-random-bit-generators-6) - NIST recommendation for deterministic random bit generation mechanisms.
- [NIST Statistical Test Suite](https://csrc.nist.gov/Projects/random-bit-generation/Documentation-and-Software) - Documentation and software for statistical testing of random and pseudorandom number generators.
- [GLI-11 Gaming Devices Standard](https://gaminglabs.com/wp-content/uploads/2018/09/GLI-11-Gaming-Devices-V3-0.pdf) - Gaming Laboratories International standard for gaming devices, including RNG expectations.
- [Dealing Cards in Poker Games](https://crypto.stanford.edu/~pgolle/papers/poker.html) - Mental-poker protocol for shuffling and dealing cards without a trusted dealer.
- [mental-poker](https://github.com/geometryxyz/mental-poker) - Rust implementation of a mental-poker protocol based on Barnett-Smart and verifiable shuffle primitives.

## Tracking & Analysis

- [FPDB-3](https://github.com/jejellyroll-fr/fpdb-3) - Open-source poker tracking and analysis suite with HUD support, hand-history import, reporting, and a web interface.
- [PokerTracker 4](https://www.pokertracker.com/products/PT4/index.php) - (Commercial) Tracker, report builder, hand replayer, and HUD for Hold'em and Omaha.
- [Holdem Manager 3](https://www.holdemmanager.com/hm3/index.php) - (Commercial) Hand database, filtering, replay, and HUD software for online poker analysis.
- [HoldemResources Calculator](https://www.holdemresources.net/) - (Commercial) Tournament preflop, ICM, and bounty analysis tool.

## Competitions & Benchmarks

- [MIT Pokerbots](https://pokerbots.org/) - Annual programming competition where teams build autonomous pokerbots for a custom variant.
- [Annual Computer Poker Competition](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/2474/0) - Report on the benchmark event that shaped academic computer-poker research.
- [Slumbot](https://slumbot.com/) - Public heads-up no-limit poker bot used as a benchmark opponent for poker agents.
- [GTO Wizard Benchmark](https://arxiv.org/abs/2603.23660) - Benchmark for evaluating heads-up no-limit Texas Hold'em agents against GTO Wizard AI.

## Client & UI Assets

- [SVG-cards](https://github.com/htdebeer/SVG-cards) - SVG and PNG playing-card deck assets distributed through npm.
- [playing-cards-assets](https://github.com/hayeah/playing-cards-assets) - MIT-licensed SVG and PNG deck assets derived from open vector cards.
- [Vector Playing Cards](https://github.com/notpeter/Vector-Playing-Cards) - Public-domain SVG deck with scripts for generating custom-sized PNG cards.

## Rules, Math & References

- [Tournament Directors Association Rules](https://www.pokertda.com/poker-tda-rules/) - Widely used tournament poker rules and procedures.
- [Robert's Rules of Poker](https://www.pagat.com/docs/RobsPkrRulesHome.pdf) - Rule reference for common poker procedures and disputes.
- [Poker Probability](https://en.wikipedia.org/wiki/Poker_probability) - Probability tables for poker hand frequencies.

## Learning & Education

- [MIT Poker Theory and Analytics](https://ocw.mit.edu/courses/15-s50-poker-theory-and-analytics-january-iap-2015/) - OpenCourseWare class on poker theory, analytics, decision-making, and trading connections.
- [An Introduction to Counterfactual Regret Minimization](http://modelai.gettysburg.edu/2013/cfr/) - Model AI teaching module with a CFR tutorial, exercises, and sample code.
- [Artificial Intelligence Poker Tutorial](https://chisness.github.io/2019-04-25/artificial-intelligence-poker-tutorial) - Code-oriented walkthrough of poker AI concepts, CFR, and agent implementation.
- [Counterfactual Regret Minimization for Poker AI](https://int8.io/counterfactual-regret-minimization-for-poker-ai/) - Long-form technical explanation of CFR and poker game-tree solving.

## Communities & Research Groups

- [Computer Poker Research Group](https://poker.cs.ualberta.ca/) - University of Alberta group behind major computer-poker milestones including Cepheus and DeepStack.
- [Two Plus Two Forums](https://forumserver.twoplustwo.com/) - Long-running poker forum with software, theory, strategy, and community sections.

## Related Lists

- [apehex/awesome-poker](https://github.com/apehex/awesome-poker) - Earlier broad poker resource list.
- [PokerBotAI/awesome-poker-ai](https://github.com/PokerBotAI/awesome-poker-ai) - AI-focused poker resource list.

## Notes

This list is intentionally selective. See [contributing.md](contributing.md) for inclusion criteria and maintenance expectations. Historically important resources that do not meet the main-list maintenance bar belong in [historical.md](historical.md).
