# EEG-Datasets

A list of all public EEG datasets. This list of EEG resources is not exhaustive. If you find something new or have explored any unfiltered links in-depth, please update the repository.

Table of Contents
=================

- [EEG-Datasets](#eeg-datasets)
- [Table of Contents](#table-of-contents)
    - [Motor-Imagery](#motor-imagery)
    - [Emotion-Recognition](#emotion-recognition)
    - [Error-Related Potentials (ErrP)](#error-related-potentials-errp)
    - [Visually Evoked Potentials (VEPs)](#visually-evoked-potentials-veps)
    - [Event-Related Potentials (ERPs)](#event-related-potentials-erps)
    - [Slow-Cortical Potentials (SCPs)](#slow-cortical-potentials-scps)
    - [Resting State](#resting-state)
    - [Music and EEG](#music-and-eeg)
    - [Eye-blinks/movements](#eye-blinksmovements)
    - [Miscellaneous](#miscellaneous)
    - [Clinical EEG](#clinical-eeg)
    - [Others (Unfiltered)](#others-unfiltered)
    - [Resources to search for database (Unfiltered)](#resources-to-search-for-database-unfiltered)


----

### Motor-Imagery

* [Left/Right Hand MI](http://gigadb.org/dataset/100295):  Includes 52 subjects (38 validated subjects with discriminative features), results of physiological and psychological questionnaires, EMG Datasets, location of 3D EEG electrodes, and EEGs for non-task related states
* [Motor Movement/Imagery Dataset](https://www.physionet.org/physiobank/database/eegmmidb/): Includes 109 volunteers, 64 electrodes, 2 baseline tasks (eye-open and eye-closed), motor movement, and motor imagery (both fists or both feet)
* [Grasp and Lift EEG Challenge](https://www.kaggle.com/c/grasp-and-lift-eeg-detection/data): 12 subjects, 32channels@500Hz, for 6 grasp and lift  events, namely a. HandStart b. FirstDigitTouch c. BothStartLoadPhase d. LiftOff e. Replace f. BothReleased
* [The largest SCP data of Motor-Imagery](https://doi.org/10.6084/m9.figshare.c.3917698): The dataset contains 60 hours of EEG BCI recordings across 75 recording sessions of 13 participants, 60,000 mental imageries, and 4 BCI interaction paradigms, with multiple recording sessions and paradigms of the same individuals. BCI interactions involving up to 6 mental imagery states are considered. [[Article]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6190745/pdf/sdata2018211.pdf)
* [BCI Competition IV-1](http://www.bbci.de/competition/iv/#dataset1): 64 EEG channels at 1000Hz sampling rate for 2 classes of left hand, right hand, foot (+ idle state) for 7 subjects. Evaluation data is continuous EEG which contains also periods of idle state.
* [BCI Competition IV-2a](http://www.bbci.de/competition/iv/#dataset2a): 22-electrode EEG motor-imagery dataset,  with 9 subjects and 2 sessions, each with 288 four-second trials of imagined movements per subject. Includes movements of the left hand, the right hand, the feet, and the tongue. [[Dataset Description]](http://www.bbci.de/competition/iv/desc_2a.pdf)
* [BCI Competition IV-2b](http://www.bbci.de/competition/iv/#dataset2b): 3-electrode EEG motor-imagery dataset with 9 subjects and 5 sessions of imagined movements of the left or the right hand, the latest 3 sessions include online feedback. [[Dataset Description]](http://www.bbci.de/competition/iv/desc_2b.pdf)
* [High-Gamma Dataset](https://github.com/robintibor/high-gamma-dataset): 128-electrode dataset obtained from 14 healthy subjects with roughly 1000 four-second trials of executed movements divided into 13 runs per subject.  The four classes of movements were movements of either the left hand, the right hand, both feet and rest.
* [Left/Right Hand 1D/2D movements](https://sites.google.com/site/projectbci/): 19-electrode data of one subject with various combinations of 1D and 2D hand movements (actual execution). 
* [Imagination of Right-hand Thumb Movement](https://archive.ics.uci.edu/ml/datasets/Planning+Relax): In every trial, subjects were asked to rest and rest data was recorded for 5 mins. Further, 5-second epoch data was also recorded when subjects were asked to imagine right-hand thumb movement. 5 of such imagined motor movement, and rest state was recorded for each trial. Single subject, 8 electrodes at 256Hz.
* [Mental-Imagery Dataset](https://figshare.com/collections/A_large_electroencephalographic_motor_imagery_dataset_for_electroencephalographic_brain_computer_interfaces/3917698): 13 participants with over 60,000 examples of motor imageries in 4 interaction paradigms recorded with 38 channels medical-grade EEG system. It contains data for up to 6 mental imageries primarily for motor movements. [[Article]](https://www.nature.com/articles/sdata2018211#ref-CR57)


---

### Emotion-Recognition

* [DEAP](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/): Includes 32 subjects, each watchine 1-min long excerpts of music-videos, rated by users in terms of arousal/valence/like-dislike/dominanace/famaliarity, and frontal face recording of 22/32 subejcts.
* [Enterface'06](http://www.enterface.net/results/): Enterface'06 Project 07: EEG(64 Channels) + fNIRS + face video, Includes 16 subjects, where emotions were elicited through a selected subset of IAPS dataset.
* [Imagined Emotion](http://headit.ucsd.edu/studies/3316f70e-35ff-11e3-a2a9-0050563f2612): 31 subjects, subjects listen to voice recordings that suggest an emotional feeling and ask subjects to imagine an emotional scenario or to recall an experience in which they have felt that emotion before.
* [NeuroMarketing](https://drive.google.com/open?id=0B2T1rQUvyyWcSGVVaHZBZzRtTms): 25 subjects, 14 electrodes, Like/Dislike on commercial e-commerce products over 14 categories with 3 images each. Article for the dataset: Analysis of EEG signals and their application to neuromarketing. [[Article]](https://link.springer.com/article/10.1007/s11042-017-4580-6)
* [SEED](http://bcmi.sjtu.edu.cn/~seed/seed.html): 15 subjects were shown video clips eliciting positive/negative/neutral emotion and EEG was recorded over 62 channels.
* [SEED-IV](http://bcmi.sjtu.edu.cn/~seed/seed-iv.html): 15 subjects were shown video clips of elicit happy/sad/neutral/fear emotions and EEG was recorded over 62 channels (with eye-tracking) for 3 sessions per subject (24 trials per session).
* [SEED-VIG](http://bcmi.sjtu.edu.cn/~seed/seed-vig.html): Vigilance labels with EEG data in a simulated driving task. 18 electrodes and eye-tracking included.
* [HCI-Tagging](https://mahnob-db.eu/hci-tagging/): Subjects were shown video clips (fragments of movies) and they were asked to annotate the emotional state on the scale of valence and arousal. During the whole experiment, audio, video, gaze data, and physiological data were recorded simultaneously with accurate synchronization between sensors.
* [Regulation of Arousal](https://ieee-dataport.org/open-access/regulation-arousal-online-neurofeedback-improves-human-performance-demanding-sensory): 18 subjects going through an online flight simulator study with three different audio-feedback silence, sham and BCI. [[Article]](https://www.pnas.org/content/116/13/6482)


---

### Error-Related Potentials (ErrP)

* [BCI-NER Challenge](https://www.kaggle.com/c/inria-bci-challenge): 26 subjects, 56 EEG Channels for a P300 Speller task, and labeled dataset for the response elicited when P300 decodes a correct or incorrect letter.

* [Monitoring ErrP in a target selection task](http://bnci-horizon-2020.eu/database/data-sets): 6 subjects with 64 EEG electrodes, watching a cursor move towards a target square, and elicited responses are labeled based on whether the cursor moves in right or wrong direction. [[Dataset Description]](https://lampx.tugraz.at/~bci/database/013-2015/description.pdf)

* [ErrPs during continuous feedback](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/contErrP_description.pdf): 10 subjects with 28 EEG electrodes, playing a video game to study execution and outcome error. [[Dataset Part-1]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/Continous_ErrP_dataset_Part1.rar) [[Dataset Part-2]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/Continous_ErrP_dataset_Part2.rar)

* [HCI-Tagging](https://mahnob-db.eu/hci-tagging/): Subjetcs were shown images or movie fragments with a tag at the bottom of the screen. In some cases, the tag correctly described something about the situation. However, in other cases, the tag did not apply to the media item. After each item, a participant was asked to press a green button if they agreed with the tag being applicable to the media item or press a red button if not. During the whole experiment, audio, video, gaze data, and physiological data were recorded simultaneously with accurate synchronization between sensors.

---

### Visually Evoked Potentials (VEPs)

* [c-VEP BCI](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/cVEP_dataset.rar): 9 subjects, 32 EEG Channels for a VEP BCI speller (32 characters) task, and labeled dataset for the response elicited for the label associated with the speller. [[Dataset description]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/cVEP_description.pdf) [[Published article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0051077)

* [c-VEP BCI with dry electrodes](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/dry_cVEP_dataset.rar): 9 subjects, 15 dry-EEG Channels for a VEP BCI speller (32 characters) task, and labeled dataset for the response elicited for the label associated with the speller. [[Article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0172400)

* [SSVEP - Visual Search/Discrimination and Handshake](https://archive.ics.uci.edu/ml/datasets/EEG+Steady-State+Visual+Evoked+Potential+Signals#): Includes 3 different tests, (i) Five Box visual test: attended and unattended disc and square-based stimuli, (ii) visual search within natural images: search of yellow dot stimuli in B&W natural images, (iii) handshake test: showing left/right hand closed/open images. 30 subjects, 14 electrodes. [[Article 1]](http://www.journalijar.com/uploads/154_IJAR-13703.pdf) [[Article 2]](https://www.hindawi.com/journals/ddns/2018/2143873/) [[More Dataset: Dataset 2]](http://www2.hu-berlin.de/eyetracking-eeg/testdata.html)

* [Synchronized Brainwave Dataset](https://www.kaggle.com/berkeley-biosense/synchronized-brainwave-dataset): 15 people were presented with 2 different video stimulus including blinks, relaxation, mental mathematics, counting color boxes, and watching superbowl ads. [[Stimulus 1]](https://www.youtube.com/watch?v=zkGoPdpRvaU&feature=youtu.be) [[Stimulus 2]](https://www.youtube.com/watch?v=sxqlOoBBjvc&feature=youtu.be)

---


### Event-Related Potentials (ERPs)

* [Pattern Visual Evoked Potentials](https://www2.le.ac.uk/departments/engineering/research/bioengineering/neuroengineering-lab/software): Dataset#5, 2 subjects for checkboard light pattern (oddball paradigm) recorded at O1 position. 
* [Face vs. House Discrimination](https://purl.stanford.edu/xd109qh3109): 7 Epileptic subjects were presented with 50  grayscale stimulations each for Face and House pictures. For each subject, a total of 3 experimental runs were conducted resulting in 300 stimulations. 
* [Target Versus Non-Target](https://zenodo.org/record/2649069): 25 subjects testing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm. 16-electrodes, wet. [publication](https://hal.archives-ouvertes.fr/hal-02126068), [code](https://github.com/plcrodrigues/py.BI.EEG.2012-GIPSA). Dataset id: BI.EEG.2012-GIPSA.
* [Target Versus Non-Target](https://zenodo.org/record/2669187): 24 subjects playing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm. 16-electrodes, wet. Up to 8 sessions per subject. Two experimental conditions: with and without adaptive calibration using Riemannian geometry. [publication](https://hal.archives-ouvertes.fr/hal-02103098), [code](https://github.com/plcrodrigues/py.BI.EEG.2013-GIPSA). Dataset id: BI.EEG.2013-GIPSA.
* [Target Versus Non-Target](https://zenodo.org/record/3266223): 71 subjects playing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adapative Riemannian Geometry (no-calibration). 16-electrodes, dry. [publication](https://hal.archives-ouvertes.fr/hal-02171575), [code](https://github.com/plcrodrigues/py.BI.EEG.2014a-GIPSA). Dataset id: bi2014a.
* [Target Versus Non-Target](https://zenodo.org/record/3267302): 38 subjects playing a multiplayer and collaborative version of Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adapative Riemannian Geometry (no-calibration). 32 electrodes per subject, wet, and 2 subjects during each session. [publication](https://hal.archives-ouvertes.fr/hal-02173958), [code](https://github.com/plcrodrigues/py.BI.EEG.2014b-GIPSA). Dataset id: bi2014b.
* [Target Versus Non-Target](https://zenodo.org/record/3266930): 50 subjects playing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adapative Riemannian Geometry (no-calibration). 32-electrodes, wet. 3 sessions per subject with modulation of flash duration. [publication](https://hal.archives-ouvertes.fr/hal-02172347), [code](https://github.com/plcrodrigues/py.BI.EEG.2015a-GIPSA). Dataset id: bi2015a.
* [Target Versus Non-Target](https://zenodo.org/record/3268762): 44 subjects playing a multiplayer (cooperation and competition) version of Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adaptive Riemannian Geometry (no-calibration). 32 electrodes per subject, wet, 2 subjects for each session. [publication](https://hal.archives-ouvertes.fr/hal-02173913), [code](https://github.com/plcrodrigues/py.BI.EEG.2015b-GIPSA). Dataset id: bi2015b.
* [Impedance Data](https://erpinfo.org/impedance): 12 subjects for P300 task (Oddball paradigm) with 20% of rare stimuli. In total, there were 128 target stimuli and 512 standard stimuli. The dataset was collected in a way such that one recording contains different impedances in electrodes. [[Article]](https://static1.squarespace.com/static/5abefa62d274cb16de90e935/t/5ac6962a8a922d0b8b8be6a1/1522964012664/Kappenman+2010+Psychophys+Impedance.pdf) [[Data]](https://erpinfo.org/impedance)
* [Sustained-Attention Driving](https://figshare.com/articles/Multi-channel_EEG_recordings_during_a_sustained-attention_driving_task/6427334/5): 27 subjects for sustained-attention driving in a VR settin for monitoring event-related potentials. Each subject participated in two 90-minute sessions (w/o and without kinesthetic feedback) and recorded with 32 channels and 500Hz. [[Article]](https://www.nature.com/articles/s41597-019-0027-4#Sec12) [[Pre-processed dataset]](https://figshare.com/articles/Multi-channel_EEG_recordings_during_a_sustained-attention_driving_task_preprocessed_dataset_/7666055/3)
* [Dryad-Speech](https://datadryad.org/stash/dataset/doi:10.5061/dryad.070jc): 5 different experiments for studying natural speech comprehension through a variety of tasks including audio, visual stimulus and imagined speech. (i) Audio-book version of a popular mid-20th century American work of fiction - 19 subjects, (ii) presentation of the same trials in the same order, but with each of the 28 speech segments played in reverse, (iii) N400 experiment: subjects read 300 sentences presented with the rest of the sentence and half which ended with an incongruent word -, (iv) cocktail party experiment: 33 subjects undertook 30 trials, each of 60 s in length, where they were presented with 2 classic works of fiction: one to the left ear, and the other to the right ear. Subjects were divided into 2 groups of 17 and 16 (+1 excluded subject) with each group instructed to attend to the story in either the left or right ear throughout the entire 30 trials, (v) multisensory experiment:  stimuli were drawn from a set of videos that consisted of a male speaking American English in a conversational-like manner. [[Main Article]](https://www.sciencedirect.com/science/article/pii/S0960982218301465) [[Supplemntary Article]](https://www.ncbi.nlm.nih.gov/pubmed/26412129)
* [ERP Core](https://github.com/andrewxstewart/ERP_CORE) 6-7 ERP paradigms including N170, N400, LRP/ERN, etc., from 40 participants, includes analysis scripts, experiments, results, and data. [[Article]](https://psyarxiv.com/4azqm/) [[Website]](https://erpinfo.org/erp-core)

---

### Slow-Cortical Potentials (SCPs)

* [Mental-Imagery Dataset](https://figshare.com/collections/A_large_electroencephalographic_motor_imagery_dataset_for_electroencephalographic_brain_computer_interfaces/3917698): 13 participants with over 60,000 examples of motor imageries in 4 interaction paradigms recorded with 38 channels medical-grade EEG system. It contains data for up to 6 mental imageries primarily for motor movements. [[Article]](https://www.nature.com/articles/sdata2018211#ref-CR57)

---

### Resting State

* [Resting State EEG Data](https://dataverse.tdl.org/dataverse/txstatecogelectro): 22 subjects, 72 EEG Channels for a resting task of 8 mins with 4 mins of eyes closed and 4 mins of eyes open. [[Article]](https://www.frontiersin.org/articles/10.3389/fnins.2017.00425)
* [EID-M, EID-S](https://drive.google.com/drive/folders/1t6tL434ZOESb06ZvA4Bw1p9chzxzbRbj): 8 subjects in rest state (with eyes closed) recorded from 14 electrodes using EPOC+ for 54s at 128 Hz (7000 samples each). EID-M has three trials and EID-S is a single trial dataset. The dataset was used to develop a person identification system through brainwaves. [[Article]](https://arxiv.org/pdf/1711.06149.pdf)
* [SPIS Resting State Dataset](https://github.com/mastaneht/SPIS-Resting-State-Dataset): 10 subjects, 64 channels, 2.5 minutes recording in each state (eyes-closed and eyes-open) prior to a 105-minute session of Sustained Attention to Response Task with fixed-sequence and varying ISIs. [[Artcile]](https://www.ncbi.nlm.nih.gov/pubmed/32167917)
* [Alpha-waves](https://zenodo.org/record/2348892) 20 subjects, 16 channels, 10s samples of two triggers (a) eyes-closed, and (b) eyes-open. The labels are also available for fatigue (from 1-10).

---

### Music and EEG

* [Music Imagery Information Retrieval](https://github.com/sstober/openmiir): 10 subjects, 64 EEG Channels for a music imagery task of 12 different pieces w/ different meter, length and tempo. [[Article]](https://pdfs.semanticscholar.org/cde4/b1ec89f2c05a41f1143792a890a00e89541a.pdf)
  
---

### Eye-blinks/movements

* [Involuntary Eye Movements during Face Perception](http://www2.hu-berlin.de/eyetracking-eeg/testdata.html): Dataset 1, 26 electrodes, 500Hz sampling rate, and 120 trials. Eye movements and pupil diameter record, EEG, and EOG data are present when the subject is presented with a happy/sad/angry face on the screen. [[Article]](http://www.jneurosci.org/content/suppl/2009/09/30/29.39.12321.DC1/Supplemental_Material.pdf) [P.S: Dataset available on request only]
* [Voluntary-Involuntary Eye-Blinks](https://drive.google.com/file/d/0By5iwWd39NblS2tRWmVTdmRzZUU/view?usp=sharing): Voluntary eye-blinks (subject were asked to blink voluntarily within 1s of audio stimulus) and involuntary eye-blinks (natural) was recorded for 20 subjects on 14 electrodes using g.tec. For each subject, 3 sessions with 20 trials each are present in .mat format. [[Article]](https://www.sciencedirect.com/science/article/pii/S0925231216001569)
* [EEG-eye state](https://archive.ics.uci.edu/ml/datasets/EEG+Eye+State): Eye-state labeled data for one continuous recording of EEG of 117 seconds with eye-closed and eye-open labels. The dataset was recorded from an Emotiv headset.
* [EEG-IO](http://gnan.ece.gatech.edu/eeg-eyeblinks/): Voluntary single eye-blinks (external stimulation was provided) and EEG was recorded for frontal electrodes (Fp1, Fp2) for 20 subjects using OpenBCI Device and BIOPAC Cap100C. One session was conducted including around 25 blinks per subject. Manual annotation was done using a video feed. [[Article]](https://proceedings.allerton.csl.illinois.edu/media/files/0174.pdf)
* [EEG-VV, EEG-VR](http://gnan.ece.gatech.edu/eeg-eyeblinks/): Involuntary eye-blinks (natural blinks) and EEG was recorded for frontal electrodes (Fp1, Fp2) for 12 subjects using OpenBCI Device and BIOPAC Cap100C. Subjects performed two activities - watching a video (EEG-VV) and reading an article (EEG-VR). Manual annotation was done using a video feed. [[Article]](https://proceedings.allerton.csl.illinois.edu/media/files/0174.pdf)
* [Eye State Prediction](http://suendermann.com/corpus/EEG_Eyes.arff.gz): 117 seconds recording of a single subject with labeled eye state data (open and closed) recorded using EPOC headset (14 electrodes). [[Article]](http://suendermann.com/su/pdf/aihls2013.pdf)
* [Kara-One](http://www.cs.toronto.edu/~complingweb/data/karaOne/karaOne.html): Imagined and vocalized phonemic and single-word prompts to access the language and speech production. 14 subjects were recorded using a 64-channel Neuroscan Quick-cap, along with face tracking and audio. [[Article]](http://www.cs.toronto.edu/~complingweb/data/karaOne/ZhaoRudzicz15.pdf)
* [EEGEyeNet](https://openreview.net/forum?id=Nc2uduhU9qa): EEG and Eye Tracking recordings from 356 different subjects collected from three different experimental paradigms (left-right, angle-amplitude and absolute position) and with 128-channels. [[Article]](https://openreview.net/forum?id=Nc2uduhU9qa) [[Data]](https://osf.io/ktv7m/)

---

### Miscellaneous

* [MNIST Brain Digits](http://mindbigdata.com/opendb/index.html): EEG data when a digit(0-9) is shown to the subject, recorded 2s for a single subject using Minwave, EPOC, Muse, Insight. Includes over 1.2M samples. 
* [Imagenet Brain](http://www.mindbigdata.com/opendb/imagenet.html): A random image is shown (out of 14k images from the Imagenet ILSVRC2013 train dataset) and EEG signals are recorded for 3s for one subject. Includes over 70k samples.
* [Working Memory](https://github.com/pbashivan/EEGLearn/tree/master/Sample%20data): Participants briefly observe an array containing multiple English characters SET (500ms) and maintain the information for three seconds. A TEST character is then presented and participants respond by pressing a button if the TEST character matches one of the characters in the SET. 15 students, 64 electrodes, and a 500Hz sampling rate. Only a small subset of data is available publicly. [[Original Paper]](https://www.memphis.edu/acnl/publications/pdfs/ejn2014b.pdf) [[Further Analysis in ICLR]](https://arxiv.org/pdf/1511.06448.pdf)
* [Deep Sleep Slow Osciallation](https://challengedata.ens.fr/challenges/10): 10 seconds of recording starting 10 seconds before the end of a slow oscillation. Data is recorded to predict whether or not a slow oscillation will be followed by another one in a sham condition, i.e. without any stimulation.
* [Genetic Predisposition to Alcoholism](https://archive.ics.uci.edu/ml/datasets/EEG+Database): 120 trials for 120 subjects recorded from 64 electrides at 256Hz. Two groups of subjects were considered, alcoholic and control. Stimuli details are given in the paper. 
* [Confusion during MOOC](https://www.kaggle.com/wanghaohan/confused-eeg): 10 students watching MOOC videos in two categories - non-confusing (e.g., basic maths) and confusing (e.g., quantum theory). 2-minute duration 10 videos in each category. Recorded from single-channel wireless MindSet over the frontal channel. [[Article]](http://www.cs.cmu.edu/~kkchang/paper/WangEtAl.2013.AIED.EEG-MOOC.pdf) 
* The Nencki-Symfonia EEG/ERP dataset: high-density electroencephalography (EEG) dataset obtained at the Nencki Institute of Experimental Biology from a sample of 42 healthy young adults with three cognitive tasks: (1) an extended Multi-Source Interference Task (MSIT+) with control, Simon, Flanker, and multi-source interference trials; (2) a 3-stimuli oddball task with frequent standard, rare target, and rare distractor stimuli; (3) a control, simple reaction task (SRT); and additionally (4) a resting-state protocol (REST). [Data](http://doi.org/10.5524/100990) - [Paper](https://doi.org/10.1093/gigascience/giac015)

---

### Clinical EEG

* [TUH EEG Resources](https://www.isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml): Massive amount of data for (i) Abnormal EEG and (ii) EEG Seizures
* [Predict-UNM](http://predict.cs.unm.edu/): A large repository of clinical EEG datasets

---

### Others (Unfiltered)

* https://sccn.ucsd.edu/~arno/fam2data/publicly_available_EEG_data.html - http://headit.ucsd.edu/studies 
* https://www2.le.ac.uk/departments/engineering/research/bioengineering/neuroengineering-lab/software
* https://github.com/pbashivan/EEGLearn/tree/master/Sample%20data 
* Section 2: https://arxiv.org/pdf/1611.08024.pdf 
* EEG Databases for Emotion Recognition, NTU 
* https://engineuring.wordpress.com/2009/07/08/downloadable-eeg-data/ 
* http://www.brainsignals.de/
* http://www.fil.ion.ucl.ac.uk/spm/data/
* http://www.brainliner.jp/search/showall/1
* http://bnci-horizon-2020.eu/database/data-sets
* http://archive.ics.uci.edu/ml/datasets/EEG+Database
* https://www.physionet.org/physiobank/database/#neuro
* https://sites.google.com/site/iitrcsepradeep7/resume
* http://memory.psych.upenn.edu/RAM
* http://fcon_1000.projects.nitrc.org/indi/cmi_eeg/
* https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8616018
* https://arxiv.org/pdf/1805.06427.pdf
* http://www.gtec.at/Research/Biosignal-Data-Sets/content/Biosignal-Data-Sets
* http://studycatalog.org/
* https://ieee-dataport.org/data-competitions
* The Australian EEG Database https://aed.newcastle.edu.au/AED/login.jsp [contact: aed@newcastle.edu.au] 
* Links for more datasets: http://www.fieldtriptoolbox.org/faq/open_data/ (might include some duplicates)
* https://figshare.com/articles/EEG_dataset/8091242 A paper with the same title is also there
* [Search Enginer: Might include a lot of duplicates] https://app.dimensions.ai/discover/data_set?search_text=eeg%20brain-computer%20interfaces&search_type=kws&search_field=full_search
* BIDS dataset: https://github.com/bids-standard/bids-examples https://osf.io/cj2dr/ https://zenodo.org/record/2536267 https://osf.io/dvmrb/
* Another platform for Neuro datasets: https://openneuro.org/
* Brain Invaders data: https://arxiv.org/abs/1905.05182
* User-security-based public datasets in section 4.2 of the paper, "A Survey on Brain Biometrics"
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5493744/ For Motor Imagery
* https://thinquanaut.wordpress.com/open-data-sources/
* https://mimic.physionet.org/
* Data: https://drive.google.com/drive/folders/0B3jfvN2T6iLMLWJMMVJMSXBqajg Paper: https://static1.squarespace.com/static/5abefa62d274cb16de90e935/t/5ac6962a8a922d0b8b8be6a1/1522964012664/Kappenman+2010+Psychophys+Impedance.pdf
* RAM dataset: http://memory.psych.upenn.edu/RAM
* https://osf.io/bndjg/ Article: https://www.ncbi.nlm.nih.gov/pubmed/25450163
* https://github.com/voytekresearch/OpenData
* contact for data: https://www.krigolsonteaching.com/uploads/4/3/8/4/43848243/2002_holroydcoles.pdf
* contact for data: https://medicalxpress.com/news/2017-06-brain-preference-based-decisions.html
* STRUM: A new Dataset for Neuroergonomics Research. The Strum dataset is not available on https://headit.ucsd.edu/
* https://paperswithcode.com/search?q=eeg+dataset

---

### Resources to search for database (Unfiltered)

* https://dataverse.harvard.edu/dataverse/harvard?q=EEG&types=dataverses%3Adatasets%3Afiles&sort=score&order=desc&page=22
* https://www.quora.com/How-can-I-get-free-data-sets-for-EEGs
* https://www.physionet.org/physiobank/database/#neuro
* https://www.researchgate.net/post/What_EEG-data_repositories_do_you_know_or_can_you_recommend_for_sharing_data
* https://www.physionet.org/
* https://alpha.physionet.org/about/database/
* http://www.mamem.eu/mamem-makes-publicly-available-a-challenging-eeg-dataset-based-on-a-ssvep-based-experimantal-protocol/
* https://figshare.com/articles/MAMEM_Phase_I_Dataset_-_A_dataset_for_multimodal_human-computer_interaction_using_biosignals_and_eye_tracking_information/5231053
* https://figshare.com/articles/MAMEM_EEG_SSVEP_Dataset_I_256_channels_11_subjects_5_frequencies_/2068677
* https://figshare.com/articles/MAMEM_EEG_SSVEP_Dataset_II_256_channels_11_subjects_5_frequencies_presented_simultaneously_/3153409
* https://figshare.com/articles/MAMEM_EEG_SSVEP_Dataset_III_14_channels_11_subjects_5_frequencies_presented_simultaneously_/3413851
* https://NEMAR.org about 200 BIDS formatted MEEG experiments

---