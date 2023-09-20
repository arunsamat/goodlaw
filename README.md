# The GoodLaw Project :balance_scale:

## :book: Overview

The GoodLaw Project is an open-source initiative aimed at standardizing the evaluation of Large Legal Language Models (LLLMs) across various legal practice areas. This repository serves as a specialized collection of benchmarking prompts designed to evaluate the output quality of LLLMs in different legal contexts.

## :question: Why GoodLaw?

The legal industry is undergoing a transformation with the integration of machine learning technologies. The GoodLaw Project fills a critical gap by providing a curated set of prompts that serve as a reliable benchmark for assessing the quality and applicability of LLLM outputs across various legal domains.

## :star: Features

- **Curated Benchmarking Prompts**: A carefully curated set of prompts that cover a wide array of legal topics.
- **Open-Source and Community-Driven**: The repository is open for community contributions.

## :bar_chart: Quantitative Evaluation

For those interested in a more quantitative evaluation, we recommend using the [ARC Framework](https://github.com/Your_Link_To_ARC_Framework), which focuses on Accuracy, Relevance, and Completeness.

## :handshake: How to Contribute

- Add new prompts under the `benchmark_prompts` folder, organized by legal practice area and task type (retrieval or generation).
- Improve or add to the usage guidelines in the `USAGE_GUIDELINES.md` file.

For detailed guidelines, please read [`CONTRIBUTING.md`](CONTRIBUTING.md).

## :page_with_curl: License

This project is licensed under the MIT License - see the [`LICENSE.md`](LICENSE.md) file for details.

## :file_folder: Repository Structure Explained

The repository is meticulously organized to accommodate different types of tasks—retrieval tasks like QnA and generation tasks like drafting and summarization. Here's how it's structured:

- **benchmark_prompts**: This is the main folder where all the benchmarking prompts are stored. It contains sub-folders for each legal practice area, such as `mergers_and_acquisitions`.

    - **Practice Area Sub-folders**: Within each practice area folder, there are sub-folders that categorize the type of legal activity. For example, `public_transactions` is a sub-folder within `mergers_and_acquisitions`.

        - **Task Type Folders**: These are folders like `retrieval` that specify the type of task. They contain an `eval_prompt.txt` file with evaluation prompts and a `sample_docs` folder.

            - **eval_prompt.txt**: This text file contains the evaluation prompts designed to test LLLMs on tasks related to that specific practice area and task type.

            - **sample_docs**: This folder contains example documents that ground the retrieval tasks. For instance, `fb-oculus.pdf` is a sample document in the `mergers_and_acquisitions/public_transactions/retrieval/sample_docs` folder.
