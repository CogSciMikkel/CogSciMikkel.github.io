# Projects

A selection of my academic and professional projects

------------------------------------------------------------------------

## BSS Alumni Career Tracker

**2025-Present \| Student Programmer \| Aarhus University BSS**

BSS had no systematic record of its graduates’ career outcomes. I built a generalisable and automated pipeline that constructs and maintains that record by collecting, extracting, and structuring employment data for alumni across all BSS study programmes.

The pipeline loads alumni from administrative data, runs automated online searches, and sends results to an LLM via the OpenAI API for structured attribute extraction. When a search yields no result, the pipeline refines its queries and retries. All data lives in a PostgreSQL database on UCloud.

The project started as a one-off analysis for Economics and Business Economics alumni and was expanded to all BSS programmes after positive reception from BSS leadership.

*Stack: R \| Python \| PostgreSQL \| OpenAI API \| UCloud*

------------------------------------------------------------------------

## N170 Lateralisation in an Emotional Stroop Task

*Picking Sides: N170 Lateralisation in an Emotional Stroop Task*

**2026 \| Cognitive Neuroscience \| Group Project**

We investigated whether task instructions modulate the hemispheric distribution of N170 congruency effects in an emotional Stroop task, where affective words were superimposed onto affective faces. The question was whether attending to one stimulus type drives the congruency effect of the other into its associated hemisphere.

I contributed to the EEG preprocessing pipeline, analysis code, and data visualisation. We combined behavioural reaction time modeling with EEG amplitude analysis and fitted linear models to both data streams to assess whether congruency effects were lateralized differently across tasks.

*Methods: EEG \| MNE-Python \| Linear models \| Reaction time analysis \| Data visualisation*

------------------------------------------------------------------------

## Interpersonal Synchrony and the Social Simon Effect

*Tapping Together, Responding Apart: The Effect of Interpersonal Synchrony on the Social Simon Effect*

**2026 \| Social and Cultural Dynamics \| Group Project**

We investigated whether interpersonal synchrony modulates the Social Simon Effect (SSE), the response conflict that emerges when two people share a go/no-go task. The question had not previously been tested empirically.

I programmed the experimental procedure in PsychoPy and ran the full Bayesian analysis pipeline: specifying empirically grounded priors, verifying them through prior predictive simulation, fitting a GLMM via Hamiltonian MC, and evaluating model fit with posterior predictive checks. I also conducted a simulation-based parameter recovery test to assess statistical power. Results were inconclusive, which the power analysis attributed to the small sample size rather than a true null.

*Methods: Bayesian GLMM \| PsychoPy \| Prior and posterior predictive checks \| Simulation-based power analysis \| Reaction time analysis*

------------------------------------------------------------------------

## Framing and Decision Dynamics

*Same Options, Different Struggles: How Framing Affects Decision Dynamics*

**2026 \| Perception and Action \| Group Project**

We examined how gain versus loss framing shapes real-time decision difficulty, even when options remain objectively equivalent. Grounded in prospect theory, we implemented a 2×2 within-subjects design and used mouse tracking to capture continuous decision dynamics.

I was responsible for the full technical pipeline: programming the experimental procedure in PsychoPy, preprocessing high-resolution trajectory data, operationalising decision conflict using area under the curve, and analysing the data with linear mixed-effects models. We interpreted both significant and null effects within a dynamic perception-action framework.

*Methods: Mouse tracking \| PsychoPy \| Linear mixed-effects models*

------------------------------------------------------------------------

## Pain Tracking App

*Bridging Pain and Communication: A Mobile Implementation of Pain Assessments for Chronic Pain Self-Management*

**2025 \| Applied Cognitive Science \| Group Project**

This project grew out of my interest in how pain communication breaks down across language and cultural barriers. We developed a React-based pain tracking app to support more nuanced conversations between chronic pain patients and clinicians. We integrated validated pain assessment tools into an interface featuring daily check-ins, an interactive body map, and visualisations suited to users with varying health literacy levels.

Two of us shared the app development evenly. Inclusive design principles and health literacy considerations shaped key interface decisions throughout.

*Methods: React \| Human-centred design \| Inclusive design \| Clinical pain measures*

------------------------------------------------------------------------

## Social Context and Fear

*Scream Together, Fear Together: How Communication Influences the Experience of Fear*

**2024 \| Cognition and Communication \| Group Project**

We investigated how different social contexts shape the subjective and physiological experience of fear. Participants watched a horror film either alone, with a silent co-viewer, or with a co-viewer they were encouraged to communicate with. The project group collected heart rate data and self-report responses across conditions, and I ran the statistical analysis linking communication to significantly increased physiological arousal without a corresponding rise in self-reported fear.

This dissociation suggests that social interaction intensifies bodily responses without necessarily altering subjective emotional experience.

*Methods: Heart rate monitoring \| Self-report surveys \| Experimental design \| Biometric data analysis*
