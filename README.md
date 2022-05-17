<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The project mainly aims to order articles on Wikipedia based on Graph Neural Network.

The brief process of making the GNN is as follows:
* Scraping and Labelling of Articles
* Building the Wikipedia Graph
* Creation of Additional features using Centrality Metrics
and Clustering coefficient
* Development of Node Classification Model
* Graph Traversal and Article Ordering Algorithm

### Refer [this](https://github.com/Anupam0401/Wikipedia-Graph-Analysis/blob/master/Assignment%202_%20Wikipedia%20Graph%20Analysis.pdf) document for detailed desciption of the project.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [sklearn](https://jquery.com](https://scikit-learn.org/)
* [Node2Vec](https://snap.stanford.edu/node2vec/)
* [Google Colab](https://colab.research.google.com)



<!-- GETTING STARTED -->
## Getting Started

To run the project, simply run the cells in the **[python notebook](https://github.com/Anupam0401/Wikipedia-Graph-Analysis/blob/master/Assignment2_wiki_graph_analysis.ipynb)** in Google Colab or other equivalent software for running python notebooks.

### Prerequisites

When running on local system, install the following dependencies using the following commands before running:
* pip
  ```sh
  pip install pandas
  ```
   ```sh
  pip install -U scikit-learn
  ```


<!-- USAGE EXAMPLES -->
## Usage

Given some Math topic, this project enables the user to explore all the topics that are the prerequisite to that topic, i.e., provide a list of topics which should be known before jumping into the input topic.

_For more examples, please refer to the [Documentation](https://github.com/Anupam0401/Wikipedia-Graph-Analysis/blob/master/Assignment%202_%20Wikipedia%20Graph%20Analysis.pdf)_

