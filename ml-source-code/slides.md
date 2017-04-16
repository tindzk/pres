---
title: Applying Machine Learning to Source Code
author: Tim Nieradzik
date: 19th July 2016
institute: Ukrainian Catholic University
lang: british
spelling: new
include-after:
    - \plain{Questions?}
---

## Why?
\centering
\huge

**GitHub:** 2M active repositories^[Q4/2014, according to 
[GitHut.info](http://githut.info)]

##
\centering
\huge

Large proportion of commits are fixes!

## Survey
| **Project** | **Commits (fixes)** | **Commits (total)** | **%** |
|-------------|---------------------|---------------------|-------|
| <span style="font-variant: small-caps">caffe</span> | 838 | 3737 | 22% |
| <span style="font-variant: small-caps">tensorflow</span> | 1418 | 5976 | 24% |
| <span style="font-variant: small-caps">node</span> | 4329 | 14444 | 30% |
| <span style="font-variant: small-caps">ruby</span> | 7968 | 43978 | 18% |
| <span style="font-variant: small-caps">spark</span> | 5779 | 17034 | 34% |
| <span style="font-variant: small-caps">elasticsearch</span> | 4059 | 23309 | 17% |

```bash
git log --grep='fix' -i | grep '^commit' | wc -l
git log | grep '^commit' | wc -l
```

##
\centering
\huge

Can we detect faulty changes before they get committed?

## Project idea
\centering
\huge

Sentiment Analysis


## Project idea
\centering
\huge

Semantic code suggestions

