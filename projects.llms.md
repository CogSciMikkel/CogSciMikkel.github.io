# Projects

A selection of my academic and professional projects

------------------------------------------------------------------------

## DaCy: Open-Source Danish NLP Models (spaCy)

**2026-Present \| Junior Data Scientist \| Center for Humanities Computing, Aarhus University**

**What I do:** Train, evaluate, and package Danish spaCy pipelines, from small CPU models to transformer encoders, and preprocess the training data.

[DaCy](https://github.com/centre-for-humanities-computing/dacy) is a collection of natural language processing pipelines for Danish, developed under the [Danish Foundation Models](https://www.foundationmodels.dk/index.html) initiative supporting open-access Danish language AI. Working on actively used open-source pipelines has strengthened my collaborative development and versioning practices.

Our [latest models](https://github.com/centre-for-humanities-computing/DaCy/blob/main/training_1.0.0/release_post/release_post.md) achieve state-of-the-art performance and outperform both spaCy’s own Danish pipelines and GPT-based models.

*Stack: Python (spaCy) \| Transformers \| NER \| Dependency Parsing \| UCloud*

------------------------------------------------------------------------

## Alumni Career Outcomes Analysis (LLM Data Pipeline)

**2025-Present \| Student Programmer \| Aarhus University School of Business and Social Sciences**

**What I do:** Build an LLM-based pipeline that collects and structures employment data for alumni across all BSS programmes, and produce the downstream analyses and visualisations for BSS leadership.

Aarhus University BSS previously had no record of their graduates’ career outcomes. The pipeline loads alumni data from administrative records, runs automated online searches, and sends results to an LLM via the OpenAI API for structured categorisation. All data lives in a PostgreSQL database on UCloud.

The project started as a one-off analysis for Economics and Business Economics alumni and expanded to all BSS programmes after positive reception from faculty leadership.

*Stack: R \| Python \| PostgreSQL \| OpenAI API \| UCloud*

------------------------------------------------------------------------

## Task Instruction and N170 Lateralisation (EEG)

*Picking Sides: N170 Lateralisation in an Emotional Stroop Task*

**2026 \| Cognitive Neuroscience \| Group Project**

**What I did:** Helped run the full EEG data collection and contributed to preprocessing, analysis code, and visualisation.

We investigated whether task instructions modulate the hemispheric distribution of N170 congruency effects in an emotional Stroop task, where affective words were superimposed onto affective faces. The question was whether attending to either faces or words would drive the congruency effect of the other into its associated hemisphere.

As a group, we programmed the experiment in PsychoPy, set up the EEG equipment, and tested participants at Aarhus University Hospital. We combined behavioural reaction time modelling with EEG amplitude analysis and fitted linear models to both data streams to assess whether congruency effects were lateralized differently across tasks.

*Methods: Electroencephalography (EEG) \| Neurophysiological data analysis \| MNE-Python \| PsychoPy \| Reaction time analysis*

------------------------------------------------------------------------

## Synchrony and the Social Simon Effect (Bayesian GLMM)

*Tapping Together, Responding Apart: The Effect of Interpersonal Synchrony on the Social Simon Effect*

**2026 \| Social and Cultural Dynamics \| Group Project**

**What I did:** Programmed the PsychoPy experiment and ran the full Bayesian GLMM analysis which included prior and posterior checks and a simulation-based power analysis.

We investigated whether interpersonal synchrony modulates the Social Simon Effect (SSE), the response conflict that emerges when two people share a go/no-go task. The question had not previously been tested empirically.

The analysis pipeline covered empirically grounded priors verified through prior predictive simulations, a GLMM fitted via Hamiltonian MC, and model evaluation with posterior predictive checks. A simulation-based parameter recovery test showed that the inconclusive results were due to the small sample size rather than a true null.

*Methods: Bayesian GLMM \| Prior and posterior predictive checks \| Simulation-based power analysis \| Reaction time analysis \| PsychoPy*

------------------------------------------------------------------------

## Framing and Decision Dynamics (Mouse Tracking)

*Same Options, Different Struggles: How Framing Affects Decision Dynamics*

**2026 \| Perception and Action \| Group Project**

**What I did:** Built the full technical pipeline, from the PsychoPy experiment to mouse trajectory preprocessing and mixed-effects analysis of decision conflict.

We examined how gain versus loss framing shapes real-time decision difficulty, even when options remain objectively equivalent. Grounded in prospect theory, we implemented a 2×2 within-subjects design and used mouse tracking to capture continuous decision dynamics.

I preprocessed the high-resolution trajectory data, operationalised decision conflict using area under the curve, and analysed it with linear mixed-effects models. We interpreted both significant and null effects within a dynamic perception-action framework.

*Methods: Mouse tracking \| Linear mixed-effects models \| PsychoPy*

------------------------------------------------------------------------

## Pain Tracking App for Chronic Pain Self-Management (React App)

*Bridging Pain and Communication: A Mobile Implementation of Pain Assessments for Chronic Pain Self-Management*

**2025 \| Applied Cognitive Science \| Group Project**

**What I did:** Co-developed a React-based pain tracking app for chronic pain patients.

This project grew out of my interest in how talking about pain often breaks down across language and cultural barriers. The app supports more nuanced conversations between patients and clinicians by integrating clinically validated pain assessment tools into an interface with daily check-ins, an interactive body map, and visualisations suited to users with varying health literacy levels. Inclusive design principles and health literacy considerations shaped key interface decisions throughout.

*Methods: React \| Human-centred design \| Inclusive UX design \| Clinical pain measures*

------------------------------------------------------------------------

## Social Context and Fear (Heart Rate Analysis)

*Scream Together, Fear Together: How Communication Influences the Experience of Fear*

**2024 \| Cognition and Communication \| Group Project**

**What I did:** Ran the statistical analysis of heart rate and self-report data in an experiment on social context and fear.

We investigated how different social contexts shape the subjective and physiological experience of fear. Participants watched a horror clip alone, with a silent co-viewer, or with a co-viewer they were encouraged to communicate with. The analysis linked communication to significantly increased physiological arousal without a corresponding rise in self-reported fear. This suggests that social interaction intensifies bodily responses without necessarily altering subjective emotional experience.

*Methods: Heart rate monitoring \| Self-report surveys \| Experimental design \| Biometric data analysis*
