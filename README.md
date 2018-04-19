# NLP Chinese to English Using Statistical Machine Translation

Implementation of Chinese to English Statistical Machine translation System.


## Abstract
This paper is for Chinese to English statistical machine translation system with emphasis on  feedback  exchange  between  decoder  and reranker. We have used future cost based beamsearch decoder and PRO reranking algorithm with ordinal regression to build our decoder-reranker system. Our idea here is to use signif-icant features such as language model, translation model and alignment score for our de-coder and use feedback loop from the rerankersystem  to  improve  translation  quality.We have improved on the PRO algorithm by combining ordinal regression for better learning in the reranking phase of the system. Our experiment shows +3.5 BLEU score improvement as compared to baseline system having only de-coder.  We have used Moses tokenizer which further improved the BLEU score by +2.0.

## Porject Report
Check out <a href = "./report.pdf" target="_blank">report.pdf</a> for the report of the project.

