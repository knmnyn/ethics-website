---
hide:
  - navigation
  - toc
---
As authors, your role is crucial: your research and your participation in the scientific community have an impact. You need to try and make sure that you do not contribute to causing any harm. A few key principles to help you think about possible ethical issues and how to report them are listed down below:

## 1. Include ethics from the start, and throughout the pipeline
Ethics is not an afterthought, and is not limited to filling an ethical consideration section or to tick boxes when submitting your papers. To make sure your research is not raising ethical concerns, ethical reflections should start from the conception of the experiment, and be present at all steps, then diligently reported in papers.

Try and ask yourself questions about ethics while thinking about research questions, experiment and methodology design, tools and datasets choice/conception, tools evaluation, ... 

The following principles are examples of elements to keep in mind and apply in your research, at every step.

## 2. Take into consideration all stakeholders

It takes a village to do research: from annotators, human participants, to involved researchers and even downstream users, many people can contribute or be affected by your work. It is important that all of them are taken into account, treated with respect and that you do not cause them any harm. Be transparent about who contributed to your research, how so, etc. This ensures that everyone was treated correctly, and also helps to signal possible bias (e.g., if a majority of men participated in an experiment, the results may only apply to men).

Some more specific advice depending on the target population:

### About human annotators/crowdworkers/interns and human participants
Report how they were recruited, their level of "expertise"/education, some basic demographic information that could be relevant (e.g., gender, country of origin, spoken languages, ...), ... Also specify what their task was, what guidelines/specific training they followed, and if the task presented any risk (e.g., offensive content that had to be annotated, etc.).

For human participants, also provide details about their informed consent, the procedures that were used to pseudonymize/anonymize when applicable, and whether or not a debrief took place after the experiment. 

### About downstream users
Make sure that possible users will benefit from your research, and try and document the possible gaps: did you take into consideration a variety of possible users? Is one population less well represented? Will your system work less well on specific populations? What could be used to mitigate these problems?

## 3. Think about the possible impact of your research
Other important elements are related to ethics and should be taken into account from the start, and reported, as precisely as possible. For instance:

### Limitations
Even before filling the Limitations section of your papers, limitations of your work should be addressed. The scope of your work should be clear, and what it does and does not do should be explicitly stated. For instance, what (variety of) language(s) does your system support? What population is (not) represented? What could be improved? Are there any possible conflicts of interest and/or (unconscious) bias?
Stating these limitations allows for better transparency, but also allows readers to better frame your research and to mitigate their own possible biases. It also highlights the future directions that should be prioritized.

### Potential for misuse, dual use and possible risks:
While your work was probably conducted with good intentions, it is important to consider if/how it could be misused and the risks it could create. Be especially careful about marginalized populations that could be even more impacted. If in doubt, feel free to discuss with others, and especially with possibly concerned people. If the risks seem too high, ask yourself if it is really worth it, and how so.

### Environmental impact
If you used computational resources, your work had an environmental impact. This should be thought about while conceiving the experiment, in order to estimate the impact and try and see if less costly alternatives exist. For example, to use LLMs, libraries such as VLLM (https://docs.vllm.ai/en/latest/) exist and make inference faster and less environmentaly costly.
In any case, you should report the used resources (GPUs, time, ...). Tools, such as https://calculator.green-algorithms.org/ or https://github.com/blubrom/MLCA, help you compute estimated environmental impact (carbon footprint, ...).

### About data collection/creation
Creating or collecting data raises a lot of ethical questions: was the collected data under a permissive license/did the authors gave their informed consent? Is the resulting collection representative of different populations? Does it contain offensive content? Does it contain sensitive information? Was everything properly documented?


## 4. Ethics is a discussion: the more the merrier!
Remember that ethics is not all about theory, but it is an ongoing, dynamic discussion. To enrich your perspectives, reach out to people around you: colleagues, students, even friends and family. Whether it is to discuss an ethical dilemma, to share your research ideas, or to brainstorm, it could enlarge your views and add perspectives you had not thought about.


## 5. Extend your knowledge on ethics
The ACL ethics committee gathered resources on ethics and NLP. Feel free to consult our reading list https://ethics.aclweb.org/resources/ethics-reading-list/ ! 

The ARR Responsible NLP Research (https://aclrollingreview.org/responsibleNLPresearch/) is also a useful, complementary resource to the present webpage. 

Remember that keeping yourself informed and raising awareness is a first, crucial step to aim at a more ethical research.