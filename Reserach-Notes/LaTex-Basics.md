---
id: LaTex-Basics
aliases:
  - latx-basics
tags:
  - LaTex
created: "17-10-2026 14:33"
status:
---

# LaTex-Basics

When using LaTex we are just writing plan text file which describes the document's structure and presentation. LaTex converts this source text, combined with markup, into a typeset document.

There are certain [[LaTex-Syntax|LaTex-Syntax]] rules used when making documents in LaTex

## LaTex Document

LaTex allows users to structure their documents with a variety of hierarchical constructs, including chapters,sections,subsections and paragraphs.[[LaTex-Document|LaTex-Document]]

```tex
\documetclass{article}
\usepackage[utf8]{inputenc}

\title{LaTex}
\author{bibin}
\date{octber 2026}

\begin{document}

\maketitle
\section{Introduction}

\end{document}
```
