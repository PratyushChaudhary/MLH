# Fine-Tune a Foundation Model on Indian Dank Memes

This is my small project for the **Global Hack Week (GHW) by MLH** under the challenge:
> “Fine-Tune a Foundation Model”

I used posts from **r/IndianDankMemes** on Reddit to fine-tune a language model.  
Just wanted to see how it picks up the humor, slang, and style from this community.

---

## What’s in this folder

- A Jupyter notebook that:
  - fetches meme data from Reddit,
  - cleans and preps it,
  - and runs the fine-tuning with OpenAI.

- A sanitized JSONL file used for training.

Any leftover links to Reddit images in the notebook are simply from fetching the top posts.

---

## Fine-tuned model

## Example output

Here’s a quick sample of what the fine-tuned model generates:  

![example meme output](https://raw.githubusercontent.com/PratyushChaudhary/MLH/refs/heads/main/GHW/Fine-Tune_a_Foundation_Model_1/captures/Fine-Tune_Model_in_Action.png)

---

## How to run this

1. Clone the repo.
2. Open the notebook at:
GHW/Fine-Tune_a_Foundation_Model_1/Fine-Tune_a_Foundation_Model.ipynb
3. Run through the cells to see how the data was collected, cleaned, and used for fine-tuning.

---

## Note

This was mainly for the GHW challenge, just to experiment with how fine-tuning changes a model’s style.  
It’s all very casual — so use responsibly if you reuse any part.

---

## Thanks

Big thanks to MLH for the fun event, and to all the open source tools that made this easy.
