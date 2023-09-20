# The GoodLaw Project :balance_scale:

## :book: Overview

The GoodLaw Project is an open-source initiative that aims to standardize the evaluation of Large Legal Language Models (LLLMs) across various legal practice areas. This repository serves as a specialized collection of benchmarking prompts designed to evaluate the output quality of LLLMs in different legal contexts.

## :question: Why GoodLaw?

The legal industry is undergoing a transformation with the integration of machine learning technologies. As LLLMs become increasingly sophisticated, the absence of a standardized evaluation mechanism poses a challenge. The GoodLaw Project fills this critical gap by providing a curated set of prompts that serve as a reliable benchmark for assessing the quality and applicability of LLLM outputs across various legal domains.

## :star: Features

- **Curated Benchmarking Prompts**: A carefully curated set of prompts that cover a wide array of legal topics.
- **Open-Source and Community-Driven**: The repository is open for community contributions.

## :bar_chart: Quantitative Evaluation

For those interested in a more quantitative evaluation, we recommend using the [ARC Framework](https://github.com/Your_Link_To_ARC_Framework), which focuses on Accuracy, Relevance, and Completeness.

## :handshake: How to Contribute

- Add new prompts under the `benchmark_prompts` folder, organized by legal practice area.
- Improve or add to the usage guidelines in the `USAGE_GUIDELINES.md` file.

For detailed guidelines, please read [`CONTRIBUTING.md`](CONTRIBUTING.md).

## :page_with_curl: License

This project is licensed under the MIT License - see the [`LICENSE.md`](LICENSE.md) file for details.

## :file_folder: Repository Structure

The repository is organized into several key folders and files:

- **benchmark_prompts**: This folder contains sub-folders for each legal practice area, such as `mergers_and_acquisitions`, `intellectual_property`, etc. Each sub-folder holds an `eval_prompt.txt` file with evaluation prompts and a `sample_docs` folder with sample legal documents relevant to that practice area.

- **CONTRIBUTING.md**: Guidelines for contributing to the project.

- **USAGE_GUIDELINES.md**: Instructions on how to use the benchmarking prompts for evaluation.

- **README.md**: This file, providing an overview of the project.
