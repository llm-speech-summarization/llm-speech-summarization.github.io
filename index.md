# Prompting Large Language Models with Audio for General-Purpose Speech Summarization

<font size="5">Anonymous submission to Interspeech 2024</font>

## Abstract

In this work, we introduce a framework for speech summarization that leverages the processing and reasoning capabilities of large language models (LLMs). We propose an end-to-end system that combines an instruction-tuned LLM with an audio encoder that converts speech into token representations that the LLM can interpret. Using a dataset with paired speech-text data, the overall system is trained to generate consistent responses to prompts with the same semantic information regardless of the input modality. The resulting framework allows the LLM to process speech inputs in the same way as text, enabling speech summarization by simply prompting the LLM. Unlike prior approaches, our method is able to summarize spoken content from any arbitrary domain, and it can produce summaries in different styles by varying the LLM prompting strategy. Experiments demonstrate that our approach outperforms a cascade baseline of speech recognition followed by LLM text processing.

<p></p>

## Contents

This page contains examples of spoken document summaries generated using the method proposed in the above paper. We provide sample summaries of articles from the CNN / DailyMail Dataset, where speech has been synthesized using a StyleTTS 2 model trained on the LJ Speech dataset, as well as examples demonstrating how varying the prompt to the LLM can produce summaries in different styles.

We also show summaries of stories spoken by actual people in "in the wild" settings, demonstrating the usability of our method in real-life scenarios.

Finally, we include examples of our system's responses to other types of spoken prompts and queries, demonstrating its ability to understand and process general speech inputs beyond those for summarization.

### Navigation

* [Summarization Examples: CNN / DailyMail](#summarization-cnn-dailymail)
* [Summarization Examples: In the Wild Data](summarization-in-the-wild)
* [Responses to General Speech Prompts](#general-responses)

<p></p>

<a id="summarization-cnn-dailymail"></a>
### Summarization Examples: CNN / DailyMail

[Back to top](#contents)

<p></p>

<a id="summarization-in-the-wild"></a>
### Summarization Examples: In the Wild Data

[Back to top](#contents)

<p></p>

<a id="general-responses"></a>
### Responses to General Speech Prompts

[Back to top](#contents)
