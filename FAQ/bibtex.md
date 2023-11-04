---
title: "Referencing System in LaTex (BibTex)"
authors:
  - name: Ehsanur Rahman Rhythm
    email: ehsanur.rahman.rhythm@g.bracu.ac.bd
    link: https://errhythm.me
    avatar: https://errhythm.me/assets/img/rhythm.png
order: -2
icon: ":black_nib:"
---

Many of you might face hard time in Latex to keep the correct referencing format. There would be different format for IEEE, ACM, ACL or Springer. BibTex can easily solve this problem.

In your project, Create a file named `refs.bib`

Add the following code in the bottom of the `main.tex`:

```latex
% For IEEE
\bibliographystyle{IEEEtran}
% For ACM
%\bibliographystyle{acm}
% For Springer
%\bibliographystyle{spbasic}
\bibliography{refs.bib}
```

Add BibTex references in that `refs.bib` and cite them in paper by `/cite{bibtex_id}`

It's important to follow the correct reference format and this method formats your reference automatically.
