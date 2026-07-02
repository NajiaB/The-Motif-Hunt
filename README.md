# 🧬🧬🧬 The Motif Hunt
## A secret is hiding in the DNA...
---

In this tutorial, we'll use deep learning to solve a real problem in biology: finding the secret pattern that makes a protein stick to DNA.

Certain proteins called transcription factors act like switches: they grab onto specific spots in your DNA and turn genes on or off. The spot they grab onto always has a short repeated pattern called a **[motif](https://open.oregonstate.education/appliedbioinformatics/chapter/chapter-2-sequence-motifs/)**.

The catch? We don't know what the motif looks like. All we have is a list of DNA sequences and a simple yes/no answer for each one: did the protein bind here or not?

Our job is to train a **neural network** to learn the difference between sequences the protein likes and sequences it ignores, and then figure out why. What pattern did it actually learn?

All we know is that the motif we're looking for is composed of exactly 12 nucleotides.

That's the mystery we're solving today.

---

| Step | What you'll do |
|------|---------------|
| 1 | Load the data and explore the sequences |
| 2 | See how the AI reads DNA (one-hot encoding) |
| 3 | Watch the AI make predictions |
| 4 | Explore saliency maps (which bases matter most?) |
| 5 | Extract what the AI actually learned => Slido |
| 6 | The motif reveal  |


[Notebook](https://colab.research.google.com/drive/1is0zH6s_OQsONQTSMlwqLKyfhXpiR664#scrollTo=27h2SoEaAdHj) (with all the answers).
