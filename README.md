# Common Hugging Face Pipelines (tasks)

Here are many of the standard pipelines available in 🤗 Transformers:

| Task                               | Pipeline name / alias                           | Description                                                         |
| ---------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------- |
| Text classification / sentiment    | `"text-classification"` / `"sentiment-analysis"` | Classify text into categories (e.g. positive/negative)              |
| Token classification / NER         | `"token-classification"` / `"ner"`              | Named entity recognition (label tokens)                             |
| Question answering                 | `"question-answering"`                          | Given a context and question, return answer span                    |
| Fill-mask                          | `"fill-mask"`                                   | Predict masked tokens in text (“cloze” task)                        |
| Text generation                    | `"text-generation"`                             | Generate text continuations (e.g. with GPT-style models)            |
| Summarization                      | `"summarization"`                               | Summarize long text into shorter form                               |
| Translation                        | `"translation"`                                 | Translate from one language to another                              |
| Text2text generation               | `"text2text-generation"`                        | General text-to-text tasks (e.g. summarization, translation, etc.)  |
| Zero-shot classification           | `"zero-shot-classification"`                    | Classify into labels not seen during training                       |
| Feature extraction                 | `"feature-extraction"`                          | Extract model embeddings / features from text                       |
| Conversational                     | `"conversational"`                              | For chat / dialogue models (maintain conversation state)            |
| Image classification               | `"image-classification"`                        | Classify images                                                     |
| Object detection                   | `"object-detection"`                            | Detect objects and bounding boxes in images                         |
| Image segmentation                 | `"image-segmentation"`                          | Segment parts of image (pixel-level)                                |
| Image-to-image / Image-to-text     | (e.g. `"image-to-text"`)                        | Convert images into text descriptions                               |
| Text-to-image / Diffusion          | (via `diffusers` pipelines)                     | Generate images from text prompts (e.g. Stable Diffusion pipelines) |
| Audio / speech tasks               | (e.g. `"automatic-speech-recognition"`)         | Transcribe audio to text                                            |
| Speech-to-text / text-to-speech    | (if supported)                                  | Convert speech audio to text or text to speech if model supports it |
