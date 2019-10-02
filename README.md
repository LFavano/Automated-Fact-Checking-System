# Automated-Fact-Checking-System
Simple implementation of an end-to-end system capable of fact checking and fake news detection.

The pipeline is composed of multiple tasks:
1) Check Fact Checking Worthiness
2) Collection of possible evidences (using Google)
3) Evidences relevance ranking
4) Evidences stance detection (Supporting/Confuting)

List of datasets used:
1. Random sentences extracted from wikipedia as in: https://arxiv.org/abs/1808.09468
2. A Million Article Headlines: https://www.kaggle.com/therohk/million-headlines
3. Relevance detection using http://www.fakenewschallenge.org dataset (but http://www.msmarco.org suggested)
4. Claim-Article pairs (Stance detection) extracted from https://www.politifact.com
