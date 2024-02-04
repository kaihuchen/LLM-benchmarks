# Open-source Benchmarks for LMMs (Large Multimodal Models)

*last updated: Feb 4, 2024

This repository is meant to be the home for a collection of many collections of datasets for testing the vision performance of a LMM.

This work is still in its preliminary stage。

## Background

LMMs have become practical as a new tool for performing visual recognition from an image, with the ability to identify multiple objects, their relationship, the environment, assessment of the overall situation per a certain given goal, suggest the best course of commonsense actions, and explain the actions.

For example, in the context of level 5 autonomous driving, a single test case might look like the following:

- Image: ![tornado](images/tornado2.jpg)
- Description: a large tornado ahead
- Action: turn around and evacuate
- Explanation: Tornadoes are incredibly dangerous and can cause major damage and injuries, even if you are not directly hit by the funnel cloud.

*(to be filled)*

## Benchmarks by Type

### Domain-specific: Level 5 Autonomous Car

Evaluate the capability of an LMM to function as part of a Level 5 autonomous car. This includes the responsibility to detect current or impending hazards and propose suitable high-level responses.

### Domain-specific: Level 5 Autonomous Drone

Assess the proficiency of an LMM to operate as part of a Level 5 autonomous drone. This involves the responsibility to <*to be filled*>.

### Domain-specific: Home Safety Monitoring

Examine the effectiveness of an LMM in the role of a home safety mobile robot, with the duty to issue warnings about any potential hazards or threats.

### Domain-specific: medical diagnosis

Evaluate an LMM’s ability to make diagnoses based on provided medical scan images.

### Ensembe AI

Assess an LMM’s interface capabilities to function as a component within an ensemble of chatbots, ensuring its ability to communicate effectively with the ensemble.

### Reasoing

Examine an LMM’s skill in performing high-level planning or diagnosis, with or without specific prompting.

### In-context learning

Test an LMM’s ability to utilize additional text/images to supplement or override its inherent knowledge.

### Set-of-Mark Prompting

Assess an LMM’s ability to facilitate discourse over an image with a number of spatial and speakable marks overlaying on the image.

Ref: [Set-of-Mark Github repository and paper](https://github.com/microsoft/SoM)

## Related Resources

Working documents for collected test cases:

- For [level 5 autonomous driving](https://github.com/kaihuchen/AutonomousBackseatDriver)
- For a *home guardian*, a mobile home robot with the duty to identify any hazard in and around a home.
*(to be filled)* 

## Released datasets

None yet as of Feb 4, 2024.

## To the Community

You are welcome to contribute to these dataset. If you have any feedbacks please post them to the *issues* area of this repo.

