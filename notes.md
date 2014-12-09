# outline 1

* have to deal with lack of invariance.
* learn talker-specific distributions of cues.
* chicken and egg problem: need to know distributions to classify, but need to know classification to learn distribution.
    * (not _totally_ true, but without knowing classification it's much harder.  need to track a lot more possibilities)
    * in the absence of information about the intended category, the listener needs to maintain uncertainty about not only the intended category but about how to update the distribution of cues for each possible alternative category.
    * if listeners are rationally updating their beliefs, they should take advantage of all available information about the intended category.
* know that people do phonetic adaptation/perceptual learning in both _supervised_ (norris,  and _unsupervised_ situations (clarayds, munson).
* but previous work leaves some gaps:
    * studies with _supervised_ adaptation have found very rapid effects, but never pitted with comparable unsueprvised cases.  so it's not clear to what extent people are really taking advantage of the supervision information.
    * the kind of labeling information that has been provided to subjects is of the kind that we already know leads to substantial changes in the perception of speech sounds (audio-visual speech, highly biasing lexical contexts).  there's _some_ ambiguity in whether label really functions the same as in traditional supervised learning paradigms (where it's explicit feedback on categorization judgements, or an explicit category label), rather than changing the low-level percept which is then operated on by normal unsupervised distributional learning processes.
* so we investigated phonetic adaptation in the presence or absence of _contextual_ labels.
    * listened to spoken words
    * synthesized VOT continuum, both ends were words (beach-peach, bees-peas,
    * two response alternatives (pictures), one /p/-initial and one /b/-initial.
    * on _unlabeled_ trials, both response options were members of the same minimal pair. on _labeled_ trials, one response picture matched the minimal pair of the stimulus, and the other did not.  For instance, for a stimulus from the beach-peach continuum, an unlabeled trial would have pictures of a beach and a peach, while a labeled trial might have a picture of a beach and pees.
    * there were two types of conditions.
        1. supervised vs. unsupervised.  For listeners in the supervised condition, half of the trials were labeled and half were unlabeled.  Listeners in the unsupervised condition received only unsupervised trials.
        2. VOT distribution.  Listeners heard VOT values drawn from one of four sets of distributions, distinguished only by the mean VOT values of a high and low VOT cluster (corresponding to /p/ and /b/).  These were: 0/40ms, 10/50ms, 20/60ms, and 30/70ms, with implied b/p category boundaries of 20ms, 30ms, 40ms, and 50ms, respectively.  (Figure for example).
* contrary to our exepctations, listeners in the supervised condition adapted neither more quickly nor more completely.
* why? maybe the higher shift distributions were just too far out there (prior probability too low) and even knowing the labels isn't enough to overcome that.  or maybe listeners don't take contextual information into account for the purposes of supervising phonetic adaptation.  (maybe tie in with use or not of context in syntactic processing, combined with probabilistic knowledge of syntactic preferences??)


## feedback

simplify: do unsupervised learning during acquisition, supervised learning/adaptation in adults.  forget about contextual nature of disambiguating information.

link to informativity: is information provided by label is used by listeners.

integrate bottom-up and top-down in PROCESSING (ganong effect, supervised trials), but not during the learning that IS happening in the background.

want to make appealing to psycholinguists/sentence processing people.  "information encapsulation"

# outline 2

* intro
    * learn probabilistic mapping between cues and linguistic categories during acquisition: unsupervised.
    * adults can learn different cue-category statistics, but learning is typically _supervised_, with another source of information which disambiguates the intended linguistic category (phonetic or syntactic).
    * don't know whether people are using the labels provided during supervised adaptation, or whether its bottom-up distributional learning.
    * people _do_ integrate bottom-up and top-down information during processing at many levels (ganong, mike stuff, etc.)
* study: phonetic adaptation with and without supervision information
    * listened to spoken words
    * synthesized VOT continuum, both ends were words (beach-peach, bees-peas,
    * two response alternatives (pictures), one /p/-initial and one /b/-initial.
    * on _unlabeled_ trials, both response options were members of the same minimal pair. on _labeled_ trials, one response picture matched the minimal pair of the stimulus, and the other did not.  For instance, for a stimulus from the beach-peach continuum, an unlabeled trial would have pictures of a beach and a peach, while a labeled trial might have a picture of a beach and pees.
    * there were two types of conditions.
        1. supervised vs. unsupervised.  For listeners in the supervised condition, half of the trials were labeled and half were unlabeled.  Listeners in the unsupervised condition received only unsupervised trials.
        2. VOT distribution.  Listeners heard VOT values drawn from one of four sets of distributions, distinguished only by the mean VOT values of a high and low VOT cluster (corresponding to /p/ and /b/).  These were: 0/40ms, 10/50ms, 20/60ms, and 30/70ms, with implied b/p category boundaries of 20ms, 30ms, 40ms, and 50ms, respectively.  (Figure for example).
* results: 
    * learned in all conditions.  less so for large VOT shifts (unsuprising given that these are way outside the normal VOT distributions)
    * listeners responded on labeled trials with almost perfect accuracy
    * ...but supervised learning was not any faster or more complete
* discussion 
    * most straightforwardly suggests that linguistic adaptation is driven mostly by bottom-up learning, and even though top-down information ("labels") is incorporated during processing, it's not used to guide adaptation.
    * or that don't use this _kind_ of label: non-linguistic contextual information.
    * an alternative interpretation is that the large shifts are so wacky that they can't be learned (and so no amount of superivsion is going to help), while the small shifts are learned too quickly for supervision to make a difference.
