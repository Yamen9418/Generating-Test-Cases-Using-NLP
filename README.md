# Master Thesis "Generating-Test-Cases-Using-NLP"
## Evaluating LLMs for Automated Test Case Generation 

# Abstract
Software testing today is a vital factor in maintaining the quality and reliability
of software products in an always-advancing technical era. Nevertheless, making
manual high-quality test documents has been historically laborious and lengthy,
which results in significant time and money consumption for the whole software
creation process. Recently, the use of transformer models has become an efficient
tool for the automation of this procedure. This thesis is based on the use of
large language models to create test case documents from feature specifications
written in natural language.
We assess different ways to improve our model’s effectiveness, such as fine-
tuning, prompt engineering, and agentic workflow methods. We carry out the
research with the use of a quantized and optimized model for memory efficiency
that demonstrates the possibility of generating good test cases even with the re-
striction of computational resources. With our approach, we achieved remark-
able results in both the BLEU score and the human evaluation score. Our highest
BLEU score achieved with our best approach is 32.93, which also corresponded
to the highest human evaluation score 3.71. This is not far from the reference
value 4.68 of being humanly written and undergoing a review process.

![Pipeline](https://github.com/Yamen9418/Generating-Test-Cases-Using-NLP/blob/main/pipeline-1.png)
