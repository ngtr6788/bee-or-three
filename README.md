# bee-or-three

## Motivation
The phrase "Bee or Three" is a phrase and a hypothetical machine learning scenario
mentioned in CGP Grey's "How machines learn" video (maybe the title had changed, I
can't remember). The video talks about how machines "learn" using a genetic algorithm,
but he did make a footnote video talking about alternate learning methods.

I did this project as "homework" for Jeremy Howard's "Practical Deep Learning
for Coders", especially the first two lessons, the introduction and how to deploy
to production. I also learned the fast.ai library through the lectures and this
project.

## How to run
1. Install poetry. This is what I used for this project, though in hindsight, I could use
something else like mamba.
2. Run `poetry install` to install the dependencies.
3. Run `poetry shell` to be in a virtual environment.
   1. Run `jupyter notebook` to run the notebooks in this project.
   2. Run `python app.py` to run the Gradio application

## How it works
The `bee_or_three_model.ipynb` notebook downloads images from the internet and fast.ai
trains a neural networks and exports it. The `app.py` takes the exported model and runs
a Gradio application.

## Next steps
- [ ] Actually deploy the Gradio application to production