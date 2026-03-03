Marcelo Bayon
Independent Research Engineer · Operations Leader · Entrepreneur
Salt Lake City, Utah

Current Research
SECD-CRF — Stochastic Electron Cascade Defect Predictor
Patent Pending · Open Source Python · No Lab Required

I am the creator and lead developer of SECD-CRF, a novel algorithm for predicting manufacturing defects in EUV (Extreme Ultraviolet) lithography — the process used to fabricate chips at the 3nm and 5nm scale.

The problem it solves:
At advanced semiconductor nodes, light behaves like individual particles landing randomly. This randomness causes defects that are unpredictable with current tools unless you run expensive full-physics simulations or build actual test chips. SECD-CRF predicts those defect locations from chip layout files alone, on commodity hardware, in seconds.

What makes it novel:
Physics-informed Monte Carlo simulation of EUV photon absorption and secondary electron scattering
A non-Gaussian blur kernel K(r) = A·exp(-r/λ)·(1 + B·r²) derived from measured secondary electron range in photoresist (~5nm) — not a fitted Gaussian approximation
Conditional Random Fields (CRFs) with edge potentials derived from that physics kernel, encoding spatial defect correlations between neighboring layout pixels
Direct inference from GDSII layout without requiring full Monte Carlo at runtime

Current stage: Stage 1 (photon absorption Monte Carlo) is complete, tested, and publicly available. Stage 2 (electron blur kernel) is in active development.
→ secd-crf repository

Background
My path to semiconductor research is unconventional — and I think that's a strength.
I spent a decade in operations leadership and entrepreneurship, which taught me how to translate complex systems into simple, actionable models. I've coached teams using behavioral frameworks like PACE and Neuro-Linguistic Programming. I've built financial products for real estate professionals. I've run my own companies.
What those experiences share with physics-informed algorithm development: you are always building a model of reality — deciding what to include, what to simplify, and what the output needs to tell a decision-maker. The domain changes. The thinking doesn't.
I currently work in the mortgage industry providing loan products for domestic and foreign nationals business owners acquiring residential properties in the US. 
I'm a lifelong autodidact. My current areas of active study are semiconductor physics, probabilistic graphical models, scientific computing, and grant writing for deep-tech commercialization.

Technical Work
SECD-CRF (active)
EUV stochastic defect prediction · Python, NumPy, SciPy, Matplotlib · Patent Pending
Mortgage + Real Estate Tools
Financial modeling, income reliability scoring, SaaS tooling for real estate professionals

What I'm Working Toward

Publishing SECD-CRF Stages 2–4 and submitting to arXiv and SPIE
Filing a USPTO Provisional Patent Application on the SECD-CRF algorithm
Submitting a DOE or NSF SBIR Phase I application for stochastic defect modeling tooling
Building academic collaborations at U of U, BYU, or USU for co-investigator partnerships
Establishing SECD-CRF as an open validation baseline for the semiconductor research community

Open to Collaboration

Semiconductor process engineers and EDA researchers
Computational physicists working in nanoscale manufacturing
University researchers pursuing EUV modeling (SBIR co-investigator conversations welcome)
Entrepreneurs and engineers building in deep tech
The LATINX engineering and entrepreneurship community


Values
Integrity · Tenacity · Perpetual improvement · Moxie
I am a strategic thinker with a track record of building things that didn't exist before — in business and now in research. I believe the best technical work is explainable to anyone, defensible under scrutiny, and useful in the real world.

Contact
📧 Marcelo.Bayon1987@gmail.com 
📞 801-971-4338
📍 Salt Lake City, Utah
