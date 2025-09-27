**Translator **
<p align="center">
  <a href=" https://0d8bd4dbd19f2fb21d.gradio.live" target="_blank">
    <img src="https://img.shields.io/badge/Open%20Demo-Click%20Here-brightgreen" alt="Open Live Demo" />
  </a>
</p>


Project Overview
A lightweight Translator web application built with Gradio and executed on Google Colab. This repository contains the source notebook for a simple text translation UI. A live shared demo is available at: https://0d8bd4dbd19f2fb21d.gradio.live
This README explains how to run the app on Google Colab, how to add a clickable Live Demo button to the repository homepage, and how to make the demo persistent.

Features

Text input → translated text output
Simple and responsive Gradio UI
Example language options and sample texts
Runs smoothly on Google Colab without local setup

Tech Stack

Python 3.8+
Gradio
Google Colab
Transformers, torch.

Quick Start (Google Colab)

Open the notebook (translator(1).ipynb) directly in Google Colab.
Run all the cells in order.
The final cell will launch the Gradio interface. Use iface.launch(share=True) to generate a temporary shareable demo link.
