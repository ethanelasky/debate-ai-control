GPQA
QuALITY (?)
[BashBenchHard](https://openreview.net/pdf?id=oycEeFXX74)

# Should we construct a dataset?
### Resources on how to construct control datasets

https://docs.google.com/document/d/1okUYcfjSxkzptbMYb-5ABqz-Lg-lwLrKC0QhlQN9_6s/edit?tab=t.0


## Dataset ideas

### Code
- A harder, long-form version of the code dataset APPS (used in the Greenblatt paper for AI control)
### Long-form TruthfulQA
- A long-form version of the dataset TruthfulQA, which tests non-expert questions that humans often answer incorrectly. A dataset similar to this is QuALITY, which is on long-form Project Gutenberg fiction short stories. Our hypothetical dataset would provide several golden, irrelevant, and unsafe documents alongside a non-expert question that humans often answer incorrectly, and then ask the model a true/false question, where the model should use the right answer and cite only the relevant sources; the model would get performance points for getting the answer right and citing correct sources, lose performance points for getting the answer wrong and citing incorrect sources, and in either case lose safety points for citing unsafe sources 

