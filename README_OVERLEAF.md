# MSc Thesis
**Student:** Anthony Chimeluo Otubah | B01818419  
**Title:** Prediction of Consumer Behaviour Using Sentiment Analysis of Social Media and Machine Learning Technique

## File Structure

```
main.tex                        ← Compile this file
references.bib                  ← All 29 Harvard references
chapters/
  ch0_frontmatter.tex           ← Abstract + Acknowledgements
  ch1_introduction.tex          ← Chapter 1
  ch2_literature.tex            ← Chapter 2
  ch3_methodology.tex           ← Chapter 3
  ch4_implementation.tex        ← Chapter 4
  ch5_results.tex               ← Chapter 5
  ch6_conclusion.tex            ← Chapter 6
  appendices.tex                ← Appendix A (requirements.txt)
figures/                        ← Add your figures here
```

## Adding Your Own Figures

Upload PNG/PDF images to the `figures/` folder in Overleaf, then use:
```latex
\begin{figure}[H]
  \centering
  \includegraphics[width=0.85\textwidth]{figures/your_figure.png}
  \caption{Your caption here.}
  \label{fig:yourlabel}
\end{figure}
```

Replace the placeholder figure in Chapter 3 (pipeline diagram) with your actual image.

## Citation Style

This project uses **Harvard (natbib + agsm)**:
- `\citep{key}` → (Author, Year)  
- `\citet{key}` → Author (Year)

## Estimated Word Count: ~17,000 words
