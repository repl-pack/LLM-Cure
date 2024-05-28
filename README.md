# LLM-Cure

## Abstract
The exponential growth of the mobile app market underscores
the importance of constant innovation and rapid response to user
demands. User satisfaction is paramount, and developers rely on
user reviews and industry trends to identify areas for improvement.
However, the sheer volume of reviews poses challenges in manual
analysis, necessitating automated approaches. Existing automated
approaches either analyze only a target app’s reviews, neglecting
valuable insights from competitors or fail to provide actionable
feature enhancement suggestions. To address these gaps, we pro-
pose an LLM-based Competitive User Review Analysis for Feature
Enhancement) (LLM-Cure), a novel approach powered by large lan-
guage models (LLMs) to automatically generate suggestions for
mobile app feature improvements by leveraging insights from the
competitive landscape. LLM-Cure operates in two phases. First, it
identifies and categorizes high-level features within reviews using
its LLM capabilities. Secondly, when provided with a complaint in
a user review, LLM-Cure curates highly rated features in compet-
ing apps related to the complaint and proposes potential improve-
ments tailored to the target application. We evaluate LLM-Cure
on 1,056,739 reviews of 70 popular Android apps. Our evaluation
demonstrates that LLM-Cure outperforms the state-of-the-art ap-
proach in assigning features to reviews by up to 13% in F-1 score
and by up to 11% in recall. Additionally, LLM-Cure demonstrated
its capability to provide actionable suggestions for improving user
complaints, which were validated through implementation in the
development cycle, verified through the release notes

![Overall Approach](docs/approach.jpg)
