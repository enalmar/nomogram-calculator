# Nomogram — the marginal rate calculator

The published build of the free UK marginal tax rate calculator. It shows what the
next pound of income is actually taxed at, including the bands the headline rates
do not mention: the 60% personal allowance taper between £100,000 and £125,140, the
High Income Child Benefit Charge, the £100,000 childcare cliff, student loan
repayments, and the Scottish rates.

**Live:** https://enalmar.github.io/nomogram-calculator/

## What this repository is

The built static output, and nothing else. It is published here so GitHub Pages can
serve it; the source lives in a separate private repository.

There is no server. Every figure is computed in the browser by a zero-dependency
tax engine, which is why the site stores nothing, sets no cookies, and has no
cookie banner — there is nothing to consent to and nothing to send anywhere.

## What it is not

It is not advice, and it is not a personal recommendation. It states what a set of
figures produces under the tax rules for the year selected, and nothing about what
anyone should do. Every rate and threshold behind it is a cited parameter carrying
the gov.uk page it came from and the date a person last checked it.
