# Awesome Poker [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Poker as a discipline: software, research, game theory, solvers, engines, hand histories, datasets, tools, and high-quality learning resources.

Maintained by [PokerWorks](https://pokerworks.io) as a community resource. Inclusion is based on relevance, quality, usefulness, and maintenance, not affiliation.

## Contents

- [Libraries & Toolkits](#libraries--toolkits)
- [Game Engines & Platforms](#game-engines--platforms)
- [Solvers](#solvers)
- [AI, Game Theory & Research](#ai-game-theory--research)
- [Hand Histories, Formats & Standards](#hand-histories-formats--standards)
- [Datasets & Corpora](#datasets--corpora)
- [Tracking & Analysis](#tracking--analysis)
- [Competitions & Benchmarks](#competitions--benchmarks)
- [Fairness, RNG & Security](#fairness-rng--security)
- [Client & UI Assets](#client--ui-assets)
- [Rules, Math & References](#rules-math--references)
- [Learning & Education](#learning--education)
- [Communities & Research Groups](#communities--research-groups)
- [Notes](#notes)

## Libraries & Toolkits

- [PokerHandEvaluator](https://github.com/HenryRLee/PokerHandEvaluator) - Efficient 7-card and Omaha poker hand evaluation library.
- [PokerKit](https://github.com/uoftcprg/pokerkit) - Python toolkit for poker simulation, hand evaluation, state tracking, and statistical analysis.
- [OMPEval](https://github.com/zekyll/OMPEval) - C++ poker hand evaluator and equity calculator for Hold'em and Omaha simulations.
- [PokerStove](https://github.com/andrewprock/pokerstove) - C++ poker evaluation and enumeration software for equity calculations and range analysis.
- [pokersolver](https://github.com/goldfire/pokersolver) - JavaScript poker hand solver for comparing hands and identifying winning combinations.
- [chehsunliu/poker](https://github.com/chehsunliu/poker) - Go library for poker hand evaluation.
- [treys](https://github.com/ihendley/treys) - Pure Python poker hand evaluation library inspired by Deuces.
- [rs-poker](https://github.com/elliottneilclark/rs-poker) - Rust poker library for hand ranking, card enumeration, and agent experiments.

## Game Engines & Platforms

- [PokerTH](https://github.com/pokerth/pokerth) - Open-source Texas Hold'em game written in C++ and Qt.
- [OddSlingers](https://github.com/Monadical-SAS/oddslingers.poker) - Django and React codebase for an open-source online poker platform.
- [PyPokerEngine](https://github.com/ishikota/PyPokerEngine) - Python poker engine for developing and evaluating AI agents.
- [MIT Pokerbots Engine](https://github.com/mitpokerbots/engine) - Template engine for the MIT Pokerbots autonomous pokerbot competition.
- [poker-ts](https://github.com/claudijo/poker-ts) - TypeScript Texas Hold'em table model for running poker games.
- [clubs](https://github.com/fschlatt/clubs) - Python engine for simulating arbitrary community-card poker games.

## Solvers

- [TexasSolver](https://github.com/bupticybee/TexasSolver) - Open-source Texas Hold'em GTO solver with a graphical interface and short-deck support.
- [poker_solver](https://github.com/noambrown/poker_solver) - No-limit Texas Hold'em river solver using counterfactual-regret variants.
- [slumbot2019](https://github.com/ericgjackson/slumbot2019) - Implementations of CFR algorithms for Hold'em-like poker games.
- [PioSOLVER](https://piosolver.com/) - (Commercial) Desktop Hold'em solver for building trees, running solves, and analyzing postflop strategies.
- [GTO+](https://www.gtoplus.com/) - (Commercial) Hold'em game-theory analysis software for building decision trees and solving spots.
- [GTO Wizard](https://www.gtowizard.com/) - (Commercial) Cloud poker study platform with pre-solved solutions, trainers, and custom solving tools.

## AI, Game Theory & Research

- [RLCard](https://github.com/datamllab/rlcard) - Reinforcement-learning toolkit with poker environments including Limit Texas Hold'em, No-Limit Texas Hold'em, and Leduc Hold'em.
- [OpenSpiel](https://github.com/google-deepmind/open_spiel) - Research framework for games and algorithms with imperfect-information poker environments.
- [Cepheus](https://www.science.org/doi/10.1126/science.1259433) - Science paper on essentially weakly solving heads-up limit Texas hold'em.
- [DeepStack](https://arxiv.org/abs/1701.01724) - Paper on depth-limited solving and neural counterfactual value estimation for heads-up no-limit Texas hold'em.
- [Libratus](https://www.ijcai.org/proceedings/2017/772) - Paper summary of the Carnegie Mellon no-limit poker AI system.
- [Pluribus](https://www.science.org/doi/10.1126/science.aay2400) - Science paper on superhuman AI for six-player no-limit Texas hold'em.
- [Counterfactual Regret Minimization](https://poker.cs.ualberta.ca/publications/NIPS07-cfr.pdf) - Foundational paper introducing regret minimization for large imperfect-information games.
- [Neural Fictitious Self-Play](https://arxiv.org/abs/1603.01121) - Deep reinforcement-learning approach for approximating Nash equilibria in imperfect-information games.
- [Deep Counterfactual Regret Minimization](https://arxiv.org/abs/1811.00164) - Paper introducing Deep CFR for large imperfect-information poker games.
- [ReBeL](https://arxiv.org/abs/2007.13544) - Paper on reinforcement learning and search for imperfect-information games, including heads-up no-limit Texas hold'em.

## Hand Histories, Formats & Standards

- [Poker Hand History File Format Specification](https://phh.readthedocs.io/) - Specification for the PHH hand-history format across poker variants.
- [ACPC Protocol Specification](https://pokerkit.readthedocs.io/en/stable/_static/protocol.pdf) - Protocol reference for dealer-to-player messages used by Annual Computer Poker Competition tooling.
- [pluribus-hand-parser](https://github.com/VitamintK/pluribus-hand-parser) - Parser for the publicly released Pluribus hand-history data.

## Datasets & Corpora

- [PHH Dataset](https://zenodo.org/records/17136841) - Multi-variant dataset of poker hand histories in the Poker Hand History format.
- [IRC Poker Database](https://poker.cs.ualberta.ca/irc_poker_database.html) - Historical corpus of more than 10 million IRC poker hands collected from 1995 to 2001.
- [Official ACPC Match Logs](http://www.computerpokercompetition.org/downloads/competitions/) - Download index for Annual Computer Poker Competition match logs and benchmark data.

## Tracking & Analysis

- [PokerTracker 4](https://www.pokertracker.com/products/PT4/index.php) - (Commercial) Tracking, reporting, hand replay, and HUD software for Hold'em and Omaha.
- [Holdem Manager 3](https://www.holdemmanager.com/hm3/index.php) - (Commercial) Hand database, reporting, filtering, replay, and HUD software for online poker analysis.

## Competitions & Benchmarks

- [MIT Pokerbots](https://pokerbots.org/) - Annual MIT programming competition where teams build autonomous pokerbots for a custom poker variant.
- [Annual Computer Poker Competition](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/2474/0) - Competition report covering the benchmark event that shaped academic computer-poker research.
- [Slumbot](https://slumbot.com/) - Public heads-up no-limit poker bot and benchmark opponent for poker agents.
- [GTO Wizard Benchmark](https://arxiv.org/abs/2603.23660) - Benchmark paper for evaluating heads-up no-limit Texas Hold'em agents against GTO Wizard AI.

## Fairness, RNG & Security

- [NIST SP 800-90A](https://www.nist.gov/publications/recommendation-random-number-generation-using-deterministic-random-bit-generators-6) - NIST recommendation for deterministic random bit generation mechanisms.
- [NIST Statistical Test Suite](https://csrc.nist.gov/Projects/random-bit-generation/Documentation-and-Software) - NIST documentation and software for statistical testing of random and pseudorandom number generators.
- [GLI-11 Gaming Devices Standard](https://gaminglabs.com/wp-content/uploads/2018/09/GLI-11-Gaming-Devices-V3-0.pdf) - Gaming Laboratories International standard covering gaming-device requirements, including RNG expectations.
- [Dealing Cards in Poker Games](https://crypto.stanford.edu/~pgolle/papers/poker.html) - Paper proposing a mental-poker protocol for shuffling and dealing cards without a trusted dealer.

## Client & UI Assets

- [SVG-cards](https://github.com/htdebeer/SVG-cards) - SVG and PNG playing-card deck assets, installable through npm.
- [playing-cards-assets](https://github.com/hayeah/playing-cards-assets) - MIT-licensed SVG and PNG playing-card image assets derived from open vector cards.

## Rules, Math & References

- [Tournament Directors Association Rules](https://www.pokertda.com/poker-tda-rules/) - Widely used tournament poker rules and procedures.
- [Robert's Rules of Poker](https://www.pagat.com/docs/RobsPkrRulesHome.pdf) - Reference rules for common poker procedures and disputes.
- [Poker Probability](https://en.wikipedia.org/wiki/Poker_probability) - Overview of poker hand frequencies and probability tables.

## Learning & Education

- [MIT Poker Theory and Analytics](https://ocw.mit.edu/courses/15-s50-poker-theory-and-analytics-january-iap-2015/) - OpenCourseWare class on poker theory, analytics, decision-making, and connections to trading.
- [Artificial Intelligence Poker Tutorial](https://chisness.github.io/2019-04-25/artificial-intelligence-poker-tutorial) - Code-oriented walkthrough of poker AI concepts, CFR, and agent implementation.
- [Counterfactual Regret Minimization for Poker AI](https://int8.io/counterfactual-regret-minimization-for-poker-ai/) - Long-form technical explanation of CFR and poker game-tree solving.

## Communities & Research Groups

- [Computer Poker Research Group](https://poker.cs.ualberta.ca/) - University of Alberta research group behind major computer-poker milestones including Cepheus and DeepStack.
- [Two Plus Two Forums](https://forumserver.twoplustwo.com/) - Long-running poker discussion forum with strategy, software, theory, and community sections.

## Related Lists

- [apehex/awesome-poker](https://github.com/apehex/awesome-poker) - Earlier broad poker resource list, useful prior art for this project.
- [PokerBotAI/awesome-poker-ai](https://github.com/PokerBotAI/awesome-poker-ai) - AI-focused poker resource list.

## Notes

This list is intentionally selective. See [contributing.md](contributing.md) for inclusion criteria and maintenance expectations. Historically important resources that do not meet the main-list maintenance bar belong in [historical.md](historical.md).
