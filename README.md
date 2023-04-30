# Sentence Trees

This project provides a simple tool to create ASCII-style tree visualizations for sentences. The main purpose of this tool is to help with linguistic analysis, especially for understanding the structure and relationships between different components of a sentence.

## Overview

Given a sentence, the ASCII Tree Visualizer generates a tree representation that shows the grammatical structure of the sentence. The visualization is designed to be easy to read, with clear horizontal and vertical formatting. The output is in SCSS format, providing a clean and organized view of the sentence structure.

The project is intended to be used in conjunction with generative text tools like ChatGPT, which can provide additional context and understanding for the generated tree visualizations.

## Features

The Sentence Trees project offers the following features:

1. Grammatical structure visualization: Generate ASCII-style tree visualizations to represent the structure and relationships of a given sentence.
2. SCSS output: Provides a clean and organized view of the sentence structure in SCSS format.
3. Compatibility with generative text tools: Designed to work seamlessly with AI tools like ChatGPT to provide additional context and understanding for the generated tree visualizations.
4. Customizable input: Allows for easy input of target sentences for analysis and visualization.
5. Linguistic analysis aid: A valuable tool for understanding the structure and relationships between different components of a sentence.

## Prompt

Create a ASCII-style tree visualization for this sentence:
[REPLACE THIS WITH YOUR TARGET SENTENCE]

Below is the goal for style, horizontal and vertical formatting, and content. Use scss
output. You can absolutely do this. Do it just like this:

```
(S)
 ├───(NP)
 │    ├───(Det) The
 │    └───(Noun) rapprochement
 ├───(PP)
 │    ├───(P) between
 │    └───(NP)
 │         ├───(Adv) mainly
 │         ├───(Adj) Sunni
 │         ├───(Noun) Muslim
 │         ├───(Noun) Saudi
 │         ├───(Noun) Arabia
 │         └───(,)
 ├───(NP)
 │    ├───(Det) the
 │    ├───(Noun) world's
 │    └───(Adj) biggest
 │    └───(Noun) oil
 │    └───(Noun) exporter
 ├───(,)
 ├───(CC) and
 ├───(NP)
 │    ├───(Noun) Shiite-majority
 │    └───(Noun) Iran
 ├───(,)
 ├───(ADJP)
 │    └───(Adv) strongly
 │    └───(P) at
 │    └───(Noun) odds
 ├───(PP)
 │    ├───(P) with
 │    └───(NP)
 │         ├───(Adj) Western
 │         └───(Noun) governments
 ├───(PP)
 │    ├───(P) over
 │    └───(NP)
 │         ├───(Poss) its
 │         └───(Noun) nuclear
 │         └───(Noun) activities
 ├───(,)
 ├───(NP)
 │    ├───(Det) the
 │    └───(Noun) potential
 ├───(VP)
 │    ├───(V) to
 │    └───(VP)
 │         ├───(V) reshape
 │         └───(NP)
 │              ├───(Noun) relations
 ├───(PP)
 │    ├───(P) across
 │    └───(NP)
 │         ├───(Det) a
 │         └───(Noun) region
 ├───(VP)
 │    ├───(V) characterised
 │    └───(PP)
 │         ├───(P) by
 │         └───(NP)
 │              ├───(Noun) turbulence
 ├───(PP)
 │    ├───(P) for
 │    └───(NP)
 │         ├───(Noun) decades
 └───(.)
```

## Example Output

Here's an example of the visualization generated by the tool:

```plaintext
(S)
 ├───(NP)
 │    ├───(Det) The
 │    └───(Noun) rapprochement
 ├───(PP)
 │    ├───(P) between
 │    └───(NP)
 ...
 ├───(PP)
 │    ├───(P) for
 │    └───(NP)
 │         ├───(Noun) decades
 └───(.)
```

## Usage

This tool is designed to be used with generative text tools like ChatGPT. Simply edit the prompt with your target sentence to analyze as input, and the prompt will generate a tree visualization similar to the example above.

Please note that this README describes a prompt for generative text tools and does not provide a ready-to-use script or code to create the tree visualization. To create a custom tool that generates these tree visualizations, you will need to implement your own code for parsing and analyzing sentences, as well as for generating the desired output format.

## Disclaimer

Please note that the output generated by AI tools and the Sentence Trees project may not always be entirely accurate, complete, or free from biases. Users should exercise critical thinking when reviewing the generated output and consider it as a starting point for further research, discussion, or refinement.

It is the user's responsibility to verify the accuracy and relevance of the AI-generated content and adapt it to their specific needs and context. Additionally, users should be aware that the AI tool might sometimes generate content that is inappropriate, offensive, or unrelated to the given input. Always review and revise the generated content before using it in any professional or educational setting.

To add the "Features" and "Disclaimer" sections to your existing documentation, copy the text above and insert it at the desired location within your existing document.
