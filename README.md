# Hi, I'm Secil Yanik Guyot 👋

I work at the intersection of AI engineering and AI safety — evaluating, improving, and building GenAI systems people can trust.

I recently wrapped up two years as a Research Engineer at the Australian National University's [Machine Intelligence and Normative Theory (MINT) Lab](https://mintresearch.org) where I worked on evaluating the moral competence of large language models and built GenAI tooling for research workflows. Before pivoting into AI, I spent 15+ years in data and business analytics at organisations including Sophos and Deutsche Post DHL — experience that shapes how I bridge research rigour with real-world stakeholder needs.

I hold a master's degree in Applied Cybernetics from Australian National University, a MicroMasters credential from MITx in Statistics and Data Science and a bachelor's degree in Business Informatics from Marmara University. 

Outside of work, I bake sourdough loaves every week, play tennis, dance to swing jazz and occasionally go scuba diving. I have recently started sewing, a hobby which sometimes keeps me up at night as I try to figure out how to tackle the unknown or decide which project to work on next. More importantly, I am a loyal servant to our fluffy overlord called Milo. 

Check out my [LinkedIn profile](https://www.linkedin.com/in/secilyanik) to find out more about my career and skills.

## 🔍 What I work on

- **LLM evaluation** — designing evaluation frameworks for GenAI systems, from moral competence benchmarks to hallucination and grounding assessments for a claims-processing agent at a major Australian insurer
- **AI workflow automation** - built a research agent to automate ingestion, summarisation and querying of research corpus using make.com (iPaaS), various APIs including GenAI models and OpenAI vector store
- **RAG pipelines & agents** — building retrieval-augmented and agentic systems using OpenAI, Anthropic, and Google Cloud Vertex AI platform tools

## 📄 Publications

- [A Scalable Approach to Evaluating Moral Sensitivity in LLMs](https://arxiv.org/abs/2607.02972) — arXiv, 2026

I am a co-first author of this paper which evaluated the moral competence of LLMs in noisy conditions. For this eval, we generated 1000 diverse moral dilemma vignettes based on a methodology my co-first author, Daniel Kilov, and I developed. We then added three types of noisy perturbations and context additions, and asked LLMs to identify any morally relevant features for each vignette. I developed the eval metric of semantic similarity which we used to compare the LLM responses to noisy versions versus the original vignette. We found that the models we evaluated are just as adept at identifying morally relevant features in noisy conditions as in the originals, however, the noise seems to affect how many features they identify, and the direction of change doesn't follow any pattern. Beyond the methodological contributions, I handled all technical aspects: the synthetic data generation pipeline, LLM response collection, eval metric calculation, and data analysis. The repo and the dataset are to be published soon. 

For anyone interested in reading about the motivation of this work, check out the [blog post by MINT Lab PI Prof. Seth Lazar](https://blog.cosmos-institute.org/i/206254393/sensitivity) at Cosmos Institute.

- [NoRA: Evaluating Grounded Reasonableness in Visual First-person Normative Action Reasoning](https://arxiv.org/abs/2606.04806) — arXiv, 2026

This paper takes the moral sensitivity work to first-person video content. NoRA is a benchmark that focuses on evaluating VLMs on their justifications for actions rather than comparing actions to annotations. My contribution was technical support to first author Sichao Li for the experiment setup. The dataset is available on [Hugging Face](https://huggingface.co/datasets/MINTLABJHUANU/NoRA).

- [Discerning What Matters: A Multi-Dimensional Assessment of Moral Competence in LLMs](https://ojs.aaai.org/index.php/IASEAI/article/view/43035) — IASEAI '26

This was our first eval on LLM moral sensitivity where we used two 12-vignette datasets, one publicly available and one original noise-perturbed set, to measure model moral competence based on human preferences. We found that the models we evaluated did well on the public dataset but worse on the original noisy vignettes. I handled most of the technical aspects of the experiments, noise additions to vignettes, collecting LLM responses and creating human annotation surveys on Qualtrics. The repo and the datasets are available [here](https://github.com/mint-philosophy/Measuring-Moral-Skill-in-LLMs).

- [Resource Rational Contractualism Should Guide AI Alignment](https://ojs.aaai.org/index.php/IASEAI/article/view/43037) — IASEAI '26

As the title suggests, this paper proposes Resource Rational Contractualism (RRC) should be the method for AI alignment in decision making where goals and values diverge as it is more efficient and adaptable compared to virtual bargaining for every situation. RRC asks an AI agent to choose between rule-based thinking and virtual bargaining in any given situation based on how usual the situation is and the stakes involved. We found that the RRC method was almost as accurate as virtual bargaining and less costly in terms of token usage. My contributions were collecting LLM responses and analysing the output. The repo is available [here](https://github.com/mint-philosophy/RRC_experiments).

## 📫 Get in touch

secil.yanik [at] gmx.net
