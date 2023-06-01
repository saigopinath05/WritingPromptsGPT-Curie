# WritingPromptsGPT-Curie
This is an open-ended project to explore the fine-tuning process of GPT-3 and the panic around AI replacing writing jobs. I would like to ascertain how valuable fine-training is with creative tasks like short stories; for example, how does a fine-tuned curie model, with much lower parameters and cost of generation, compare to the out of the box davinci model? Additionally, it will be interesting to see whether the quality of stories from all models come close to human quality at all.

In this project, I scrape top posts and corresponding top comments from the subreddit WritingPrompts, and use them as training data for OpenAI's gpt3 curie model. I then compare performance across three models (fine-tuned curie, default curie, and default davinci) with a prompt from training and a new prompt and subjectively evaluate their story quality. 


## References:
https://github.com/openai/openai-cookbook
https://platform.openai.com/docs/guides/fine-tuning
https://praw.readthedocs.io/en/stable/
