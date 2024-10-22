# data-phishing-detection

A dataset to test methods to detect phishing emails

The file `data.parquet` contains the dataset, 400 emails. 200 are synthetic phishing attempts and 200 are synthetic regular emails.

## Schema

input - an email, synthesized by an LLM, that is either a phishing attempt or a regular email.
output - 'Yes' if the email is a phishing attempt, 'No' otherwise.

## Prompt

The `prompt.md` file contains a prompt that can be used with an LLM as a starting point for detection. Append an example to the prompt for an LLM to classify.

## Use

This data is intended for research purposes only and should not be used in any other context.

## Availability

- [Hugging Face](https://huggingface.co/datasets/RevaHQ/data-phishing-detection)
- [GitHub](https://github.com/RevaHQ/data-phishing-detection)
