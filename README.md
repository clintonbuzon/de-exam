# Thinking Machines Data Engineering Exam

## Part 1: Algorithmic thinking

![Additional problem](https://i.imgur.com/EdUiEtk.png)

Please code up a brute-force solution to this problem (it will not finish in a reasonable time) and at least 3 improvements to reduce the run time, ideally measuring the incremental reduction in run-time of each improvement. Some ideas:
- A data structure (e.g. https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)
- Ways to reduce the values of potential parameters for `a` and `b` that you need to evaluate for (there are at least 2 simple, useful reductions)
- Parallelization

Your end solution should be able to finish in approx. 1 minute.

## Part 2: Soft(ware) skills

We live and breathe data. So naturally, we try to make our internal processes as
data-driven as possible. Time-tracking allows us to determine our teams'
bandwidth and throughput so we checkin religiously. We do this using a
[a handful of tools](https://stories.thinkingmachin.es/time-tracking-dashboard/)
that we can use without interrupting our work.

For this exam, you are given an anonymized dump of our checkins for the past
year. Your goal is to:

- [ ] Decrypt the PGP-encrypted data
- [ ] Clean the data
- [ ] Load it to your choice of database
- [ ] Create a web service that displays a per-user filtered view of the checkins

Bonus points for:

- Python
- A publicly accessible deployment of your service
- Documentation
- Tests
- Diagrams

We value:

- Communication
- Reproducibility
- Pragmatism
- Code hygiene

## Submission

Submit your code by sharing a __private repo__ to any of the following users:

- https://github.com/marksteve/
- https://github.com/florobarotjr/
- https://github.com/syk0saje/
