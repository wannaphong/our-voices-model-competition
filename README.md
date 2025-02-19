

# Our voices model competition

- [What we are looking for ?](https://github.com/common-voice/our-voices-model-competition/blob/main/README.md#what-are-we-looking-for)
- [Participant packs](https://github.com/common-voice/our-voices-model-competition/blob/main/README.md#participant-packs)
- [Rules](https://github.com/common-voice/our-voices-model-competition/blob/main/submit/RULES.md)

## About 

We want to see - and incentivise! - great diversity, equity and inclusion-conscious work being done with the Common Voice dataset.
We are running a model and methods competition with three broad themes, plus an open category.

### Register your interest 

Start today by [registering your interest with this form](https://mozillafoundation.typeform.com/to/TSTzyijc), and you'll receive a participant pack with guidance, resources, advice and more to help you. 

Please read the [full rules](https://github.com/common-voice/our-voices-model-competition/blob/main/submit/RULES.md) if you are considering applying. 

## Participant packs

Localised versions of the participant packs can be found on our [Google Drive](https://drive.google.com/drive/u/0/folders/1rmJedUn5qdLLLr9rSb_pL2Q-qvlxMPAc).

## What are we looking for?

Your entry must be a diversity, equity and inclusion-conscious Model or Method under one of the following categories.
It must primarily make use of Mozilla Common Voice data from the 11th release (September 2022).
Outside of this, we are being deliberately open-ended. However, here are some illustrative examples;

| Categories             | About                                                                                     |
|--------------------|-------------------------------------------------------------------------------------------|
| Gender    | An STT model for an under-resourced language that performs equally well for women |
| Variant, Dialect or Accent | 1) Proof of concept for an under-served language variant delivered with a small ‘toy’ corpus 2) Accent classifiers by, and for, a community |
| Methods and Measures     |  1) A benchmark bias corpus 2) Dataset audit methodology                         |
|  Open         | Exciting DEI work primarily using Common Voice that doesn't fit into the categories above   |


Judging will be done by Sponsor or its designees, who shall have sole discretion in determining winners based on the following equally weighted criteria:

- Word Error Rate (“WER”) - how many word recognition mistakes your model makes when used on a fresh dataset
- WER Score when balanced by gender or Accent demographics (as per competition theme)
- Utility - this is a judgment scoring by panelists evaluating how effective, original and useful your method or measure would be
- Social need / ecosystem value - whether this model adds value to the universe of other models for the same language. We do not disqualify submissions that are not open source, but when considering ecosystem value-add within the wider rubric, we will consider the license under which your work is available.
- Deployability rating - this is a judgment scoring by panelists evaluating how easy would this be to install in an application
- Environmental impact rating (via GPU usage) - this has two components - expert panel rating plus required provision of their processing stats - aka how 'hungry' is your model? is it written to be efficient?

---

## How are you making sure it's easy for all languages to participate?

- We are actively encouraging submissions at proof of concept stage that use a small or 'toy' corpus
- Our methodology and methods category enables teams to submit outlines for tools that they do not yet have the resources to build out further
- We have allowed a month of development time to accomodate those relying on CPU / slower compute
- Languages will be judged within 'Bands' - high resource, medium resource and low resource - to ensure a fairer competition between languages that exist in different contexts
- We are creating a flexible, holistic rubric that makes it possible for judges to look at ecosystem value-add factors beyond performance metrics like Word Error Rate
- For marginalised communities who have governance concerns about releasing their model under an open source license, they are welcome to submit with an explanation to that effect, and this will be considered accordingly

## Our judges 

Who are the judging panel?

- [Professor Francis Tyers](https://linguistics.indiana.edu/about/faculty/tyers-francis.html) - Computational Linguistics Advisor, Mozilla Foundation & Academic, University of Indiana Indiana
- [Dr Vitaly Lavrukhin](https://developer.nvidia.com/blog/author/vlavrukhin/) - Principal Applied Research Scientist, NVIDIA
- [Wiebke Hutiri](https://www.tudelft.nl/en/tpm/about-the-faculty/departments/engineering-systems-and-services/people/phd-candidates/w-wiebke-toussaint/) - PhD Candidate at Delft University of Technology - Fairness in Voice Tech
- [Dr Abeba Birhane](https://abebabirhane.github.io/) - AI Fellow Mozilla
- [Rebecca Ryakitimbo](https://rebeccaryakitimbo.africa/) - Community Fellow, Kiswahili
- [Britone Mwasaru](https://foundation.mozilla.org/en/blog/jina-ni-britone-mwasaru-the-name-is-britone-mwasaru/) - Community Fellow, Kiswahili
- [Dr Josh Meyer](https://www.linkedin.com/in/josh-r-meyer)- Co-Founder, Coqui
- [Stefania Delprete](http://stefaniadelprete.com/) - Data Scientist and Italian MCV Community Rep
- [Kathy Reid](https://cybernetics.anu.edu.au/people/kathy-reid/) - PhD Candidate at Australian National University - Bias in Speech Tech, Open Source
- Gabriel Habayeb - Senior Data Engineer, Mozilla Foundation

## Submission process

In order to submit your code for the competition, you should do the following:

- Fork this repository in GitHub.
- Create a new directory in a subdirectory of [submit/](https://github.com/common-voice/our-voices-model-competition/tree/main/submit) that corresponds to the category you want to submit in. 
- Commit and push your code to that subdirectory in your fork.
- Open a pull request to this repository.
- You must then **make your final submission** using [this form](https://mozillafoundation.typeform.com/to/oBKEMY1E). Submissions which are not submitted via the Typeform will **not be able to be considered**.
