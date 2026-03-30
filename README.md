# nlp-overview

Overview of NLP resources for Clinical Data Science at Maastricht University.

This page is intentionally short and link-first. If a topic already has a strong external overview, course page, or documentation site, this README links to it instead of repeating the same material here.
Sections are grouped roughly by workflow: learn, build, run, evaluate, and find data.

## UM Courses

- [Advanced Natural Language Processing](https://curriculum.maastrichtuniversity.nl/meta/465515/advanced-natural-language-processing)
- [Information Retrieval and Text Mining](https://curriculum.maastrichtuniversity.nl/meta/464235/information-retrieval-and-text-mining)

## Learning Resources

- [Andrej Karpathy videos](https://www.youtube.com/@AndrejKarpathy/videos) for intuitive introductions to language modeling, transformers, and LLMs.
- [Hands-On Large Language Models by Maarten Grootendorst](https://www.maartengrootendorst.com/book/) for practical, modern NLP workflows.
- [Stanford CS224N](https://web.stanford.edu/class/cs224n/index.html) for a full academic course on NLP with deep learning.
- [Hugging Face Course](https://huggingface.co/course/chapter1/1) for a practical introduction to transformer tooling and workflows.
- [Sebastian Ruder's blog](https://ruder.io) for NLP background and survey-style reading, including [A Review of the Recent History of NLP](https://www.ruder.io/a-review-of-the-recent-history-of-nlp/) and the accompanying [lecture](https://www.youtube.com/watch?v=sGVi4gb90zk&list=PLICxY_yQeGYlcjO6ANCXworXHGC6hHXjA).
- [Natural Language Processing with Transformers, Revised Edition](https://www.oreilly.com/library/view/natural-language-processing/9781098136789/) for a book-length treatment of transformer-based NLP.
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) for a visual explanation of transformer internals.
- [fast.ai Practical Deep Learning for Coders](https://course.fast.ai/) for an applied deep learning course with NLP coverage.
- [ACL Anthology](https://aclanthology.org/) for NLP papers, workshops, and proceedings.

## Model Development and Fine-Tuning

- [Transformers](https://huggingface.co/docs/transformers/index) for the main Python library used to train, fine-tune, and run transformer models.
- [Unsloth](https://unsloth.ai) for faster and cheaper fine-tuning workflows for open-weight LLMs.

## Model Serving and Interfaces

- [Ollama](https://ollama.com) to run models locally.
- [OpenWebUI](https://openwebui.com) as a web interface for Ollama and related backends.
- [WebLLM](https://webllm.mlc.ai) for in-browser LLM inference.
- [vLLM](https://www.vllm.ai) for high-throughput serving of open-weight models.

## Data and Annotation Tools

- [Label Studio](https://labelstud.io) for annotation, evaluation, and data-labeling workflows.
- [MedMorf](https://medmorf.com) for browser-based medical data processing tools.

## Medical Datasets

- [PhysioNet](https://physionet.org) for biomedical datasets including MIMIC and related clinical resources.
- [n2c2](https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/) for shared clinical NLP tasks and note-based challenge datasets.
- [Zenodo medicalnlp community](https://zenodo.org/communities/medicalnlp/?page=1&size=20) for medical NLP-related datasets and project outputs.
- [Hugging Face Datasets](https://huggingface.co/datasets) for broader dataset discovery, mostly outside the clinical domain.
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/) for biomedical abstracts and literature discovery.
- [PubMed Central Open Access Subset](https://pmc.ncbi.nlm.nih.gov/tools/openftlist/) for full-text biomedical articles with open-access licensing.
- [eICU Collaborative Research Database](https://physionet.org/content/eicu-crd/2.0/) for multi-center critical care data on PhysioNet.

## Clinical Benchmarks and Leaderboards

- [Vals healthcare benchmarks](https://www.vals.ai/benchmarks#healthcare-benchmarks) as a broader entry point for healthcare model evaluation, including active benchmark pages such as MedCode and MedScribe.
- [Vals AI MedQA benchmark](https://www.vals.ai/benchmarks/medqa) as an archived but still useful medical QA comparison across open and closed models.
- [Arena leaderboard](https://arena.ai/leaderboard) for a live mixed-model leaderboard covering both open and closed models, though not specific to healthcare.
- [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) for open-weight model tracking outside the clinical domain.
- For benchmark pages in this category, prefer links that are updated regularly and clearly state whether they compare open-weight, closed, or mixed model sets.

## Shared Medical Tasks

- [Social Media Mining for Health (SMM4H)](https://healthlanguageprocessing.org/smm4h-2026/)
- [MultiClinAI Shared Task](https://temu.bsc.es/MultiClinAI/)
- [MedGemma Impact Challenge](https://www.kaggle.com/competitions/med-gemma-impact-challenge/overview)
- [BioASQ](http://www.bioasq.org/) for biomedical semantic indexing and question answering challenges.

## Community and Other Links

- [GitHub Education](https://github.com/education) for student access to developer tools and credits.
- [UMCU GitHub organization](https://github.com/umcu)
- [AlphaSignal Newsletter](https://alphasignal.ai)
- [AI Report podcast (Dutch)](https://www.aireport.nl)
- [OHDSI](https://www.ohdsi.org/) for the open community around observational health data standards and tooling.
- [BioNLP Workshop proceedings](https://aclanthology.org/venues/bionlp/) for biomedical and clinical NLP research venues.

## Scope

This repository is best used as a curated starting point:

- use it to find courses, tools, datasets, and external reading quickly;
- prefer linking to high-quality maintained resources instead of copying their content here;
- add short notes only when they help with local context for Clinical Data Science or Maastricht University.