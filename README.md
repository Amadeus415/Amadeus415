<p align="center">
  <img src="./assets/banner.jpg" alt="" width="100%" />
</p>

### Hi, I'm Amadeus.

I'm a data engineer at Autodesk in San Francisco. I own the supplier domain in our enterprise data layer and build the apps and AI agents that sit on top of it. Outside work I build things like these, and every number below comes from a script in the repo.

| Project | What it is | Measured |
| --- | --- | --- |
| [vendormatch](https://github.com/Amadeus415/vendormatch) | Entity resolution for messy vendor records. Cheap matchers take the easy pairs; a local LLM only sees the hard ones. | F1 0.936 vs 0.906 for the best string match. A local Qwen3-14B on 3.6% of pairs cuts false matches 37%. 50k records in 31 s. |
| [Nightshift](https://github.com/Amadeus415/agentic_trading) | A prediction-market paper fund that agents run and improve every day. Python holds the money. | 96 autonomous cycles, 885 risk checks, 0 breaches |
| [NanoServe](https://github.com/Amadeus415/nanoserve) | A readable LLM serving stack for Apple Silicon: OpenAI-compatible API, streaming, benchmarks. | Continuous batching: 2.2x throughput, 4.5x lower worst-case TTFT for 8 Qwen3-14B streams. About 5 ms of server overhead. |
| [NanoTrain](https://github.com/Amadeus415/nanotrain) | Train a small language model from scratch, then serve it with NanoServe. | 4.9M-parameter model to 1.56 nats/byte on Tiny Shakespeare in 11 minutes |

[amadeusc.com](https://amadeusc.com) · [LinkedIn](https://www.linkedin.com/in/amadeus-colenbrander-72112520a/)
