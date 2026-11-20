# 03. The test, and the arithmetic of a phone on a nightstand

No study in the record puts a phone beside a bed and counts remembered dreams (`02`, gap G7). This page is the measurement that would fill that gap, written to be run by one person in their own bedroom in three weeks, and the arithmetic that places a nightstand on the same scale as the laboratory antennas.

## 1. What the laboratory doses were

- Loughran 2005 and Schmid 2012: a handset-like signal at the head for 30 minutes before sleep, at 2 watts per kilogram peak spatial absorption (`01`, section 2).
- Danker-Hopfe 2020: a head-worn antenna for 30 minutes before sleep and 7.5 hours through the night, at 2 watts per kilogram (GSM 900) and 6 watts per kilogram (TETRA).
- The American limit for a phone held at the ear is 1.6 watts per kilogram averaged over one gram of tissue (FCC); the European limit is 2 watts per kilogram over ten grams (ICNIRP). The laboratory doses were at or above the legal maximum for a phone pressed to the head, for a whole night.

## 2. What a phone on a nightstand delivers, in order of magnitude

These are estimates from the physics, labeled as such; a meter in the bedroom would replace them.

- A phone transmits at most about 0.2 to 2 watts, and only while it is sending: a few percent of the time when idle, more during a call or a download.
- Radio power spreads over a sphere. At one metre, 2 watts gives about 0.16 milliwatts per square centimetre at peak and about 0.02 at a typical 0.25-watt average. For scale: the old Soviet occupational limit was 0.01 milliwatts per square centimetre, the old American limit 10, and today's general-public limit at mobile frequencies about 1 (`01`, documents c and r).
- A field of 1 milliwatt per square centimetre (10 watts per square metre) at mobile frequencies corresponds, in the international guideline's own reference levels, to a whole-body absorption of about 0.08 watts per kilogram. So the nightstand phone's 0.02 to 0.16 milliwatts per square centimetre corresponds to roughly 0.0002 to 0.001 watts per kilogram while transmitting, and, averaged over a night in which it transmits a few percent of the time, to roughly 0.00001 to 0.0001 watts per kilogram.
- Against the laboratory's 2 to 6 watts per kilogram, all night, at the head: a factor of ten thousand to a hundred thousand.

What that arithmetic does and does not say. It says the nightstand is four to five orders of magnitude below the exposures that measurably deepened sleep and shortened REM latency in the laboratory. It does not say a phone cannot affect a night, because the laboratory studies also show the effect depends on pulse modulation, varies greatly between people, and in one study tracked a single gene variant; a sensitive person at a low dose is not excluded by physics, only unmeasured. Measuring it is the next section.

## 3. The three-arm test

**The question.** Does the phone's radio change whether a dream is remembered, once the two things that travel with the phone, a lit screen before bed and an alarm at the end, are held the same on every night?

**The arms.**
- **A. Phone in the room, on, beside the bed**, as usual, but face down and silent.
- **B. Phone in the room, in airplane mode and powered off**, beside the bed. The object is there; the radio is not.
- **C. Phone out of the room**, in another room, off.

**Held the same on every night, all three arms.**
- Bedtime and intended wake time, within fifteen minutes.
- No lit screen of any kind for the sixty minutes before bed (the REM result: Chang 2015).
- Waking: natural, with no alarm, on every night; if an alarm is unavoidable, the same quiet alarm across the room on every night, never on the phone.
- No other radio moved: the router, the television and any other phone stay where they always are.
- The log is on paper at the bed, and it is written before anything else is touched on waking (the recall result: the awakening review in `01`, section 2).

**Order.** Run the arms in blocks of one night each in a rotating order, so that no arm sits on all the weekends or all the bad nights: A B C, B C A, C A B, and again. Seven nights per arm is twenty-one nights and will show a large effect; fourteen per arm, six weeks, will show a small one.

**The blind, which is the part that matters.** The base-station study in `01` found that sleep complaints followed what people believed about the exposure, not the exposure. A test the sleeper can see is a test of belief. So: for arms A and B, the phone goes face down in an opaque box or drawer on the nightstand, and **another person sets its state after the sleeper is in bed** and writes the arm on a slip kept away from the bed. The sleeper logs the night without knowing whether the radio was on. Arm C cannot be blinded (the phone is visibly gone); it is the control for "the object is in the room at all," and its result is read with that in mind. Without a second person, run A against B unblinded and say so on the result.

**The log, one line per night.**

| date | arm (filled in by the other person, after) | lights out | woke | woke by (natural / alarm / other) | dream recalled (yes / no) | vividness 0 to 3 | notes |
|---|---|---|---|---|---|---|---|

**Pre-register before night one.** Write down, before the first night, the exact counting rule below and the prediction, and seal it: a simple way is to save the plan as a file and record its SHA-256 hash somewhere dated (a tweet, an e-mail to oneself, a commit). After the last night, publish the plan and the log together. This is what keeps the result from being argued about afterwards, and it is the same tool the Monroe files use.

**The counting rule.** For each arm, the recall rate is the number of nights with a remembered dream divided by the number of nights in that arm. Report the three rates and the three counts. The pre-registered prediction is one of: "A lower than B" (the radio matters), "A about equal to B and both lower than C" (the object matters, not the radio), or "all three about equal" (neither; the screen and the alarm were the whole story). With seven nights an arm, a difference of three or more nights out of seven between A and B is worth taking seriously and worth repeating; a difference of one is noise.

**What each result means.**
- A lower than B, blinded: the radio changed recall at nightstand dose. That would be a finding the laboratory has only reached with a head antenna, and it should be repeated and then written up with the log.
- A about equal to B, both lower than C: the presence of the phone changed recall, through anything but the radio: habit, expectation, the reach for it on waking. Worth knowing, and solved by arm C.
- All about equal: the nights were the screen and the alarm, which the protocol removed on every night, and the phone's radio was not the cause.

## 4. Safety, in plain words

Nothing in this test exposes anyone to anything they are not already exposed to. The only change is removing a phone from a room, which is also the most reliable sleep improvement in the literature, for reasons that have nothing to do with radio. Anyone whose sleep is already disordered, or who is on medication that affects sleep, should keep their usual schedule and treat this as a log, not a treatment.

## 5. What would end the question

A result either way, logged and pre-registered, is more than the record holds today. A finding that the radio matters at nightstand dose would be the first of its kind and would deserve a laboratory. A finding that it does not would close the question for that person and leave the screen and the alarm, which anyone can fix tonight.
