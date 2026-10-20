# Suggested datasets for course projects

**Course: Computational Application to Cognitive Neuroscience**

## EEG datasets

### N170: Face perception

**Dataset:** [N170 on OSF](https://osf.io/pfde9/overview)

**Task:** participants classify faces, cars, scrambled faces, and scrambled cars as objects or textures.

**Starting contrast:** faces versus cars.

**Suggested project ideas:**

- Plot condition-specific ERPs and their difference at posterior electrodes.
- Compare mean-amplitude and peak-based measurements, assessing their stability under trial subsampling.
- Train a classifier to distinguish faces from cars and evaluate accuracy over time.

**Reference:** [Kappenman et al. (2021), ERP CORE](https://doi.org/10.1016/j.neuroimage.2020.117465).

### MMN: Passive auditory oddball

**Dataset:** [MMN on OSF](https://osf.io/5q4xs/overview)

**Task:** participants watch a silent video while ignoring standard tones (80 dB; 80%) and deviant tones (70 dB; 20%).

**Starting contrast:** deviant minus standard tones.

**Suggested project ideas:**

- Estimate the auditory difference waveform and quantify its amplitude.
- Use repeated trial subsampling to examine how unequal trial counts affect noise and measurement stability.
- Compare a conventional ERP analysis with time-resolved classification of tone type.

**Reference:** [Kappenman et al. (2021), ERP CORE](https://doi.org/10.1016/j.neuroimage.2020.117465).

### N2pc: Visual search

**Dataset:** [N2pc on OSF](https://osf.io/yefrq/overview)

**Task:** participants find a square in the designated target colour and report whether its gap is at the top or bottom.

**Starting contrast:** posterior activity contralateral minus ipsilateral to the target.

**Suggested project ideas:**

- Construct lateralised ERPs by combining left-target and right-target trials.
- Test whether the lateralised amplitude differs from zero across participants.
- Explore whether trial-level lateralisation predicts response time, accounting for repeated trials within participants.

**Reference:** [Kappenman et al. (2021), ERP CORE](https://doi.org/10.1016/j.neuroimage.2020.117465).

### P3: Active visual oddball

**Dataset:** [P3 on OSF](https://osf.io/etdkz/overview)

**Task:** participants classify letters as targets or nontargets. Target identity changes across blocks; targets constitute 20% of trials.

**Starting contrast:** target minus nontarget trials.

**Suggested project ideas:**

- Quantify the target-related ERP and visualise its scalp distribution.
- Compare linear classifiers using predefined time-window features and multichannel features.
- Examine how training-set size and class balancing influence classification performance.

**Reference:** [Kappenman et al. (2021), ERP CORE](https://doi.org/10.1016/j.neuroimage.2020.117465).

### N400: Word-pair judgement

**Dataset:** [N400 on OSF](https://osf.io/29xpq/overview)

**Task:** participants judge whether a target word is semantically related or unrelated to a preceding prime.

**Starting contrast:** unrelated minus related target words.

**Suggested project ideas:**

- Estimate the semantic-relatedness ERP difference.
- Test whether neural amplitude predicts response time using a model that includes condition and participant effects.
- Decode semantic relatedness over time, checking whether performance generalises across participants.

**Reference:** [Kappenman et al. (2021), ERP CORE](https://doi.org/10.1016/j.neuroimage.2020.117465).

## fMRI datasets

*Datasets will be added here.*
