# How Do I Benchmark Ruby Code?

## Learning Goals

- Use ruby's built in Benchmark module to benchmark ruby code

## Pre-check

Before reading about benchmarking in ruby, try your best to answer the following questions:

- What is the purpose of benchmarking code?
- What would you want to learn from running a benchmark?
- What kinds of things might throw off a benchmark, or make it unreliable?
- What is the difference between benchmarking and profiling?

## Reading

Read the [Benchmarking Your Code](https://rbspy.github.io/benchmarking-your-code/) guide from rbspy. It has a high-level overview of what benchmarking is and what it's for.

Next, read [How Do I Benchmark Ruby Code?](http://rubylearning.com/blog/2013/06/19/how-do-i-benchmark-ruby-code/) for a more weedsy look at how to use ruby's Benchmark module. Every time there is a code snippet, copy it into a text editor or irb and run it yourself to see the results.

## Post-check

- Read over your pre-check responses. Would you make any updates to them now?
- Did you get the same results for the benchmarks in the post? Why do you think you did or didn't?
- Which of the methods in ruby's Benchmark module do you think you'd use? Why?
- Find some code that you've written several different ways. Which way is fastest? (Bonus: Why is it fastest?)

## Further Reading

- Check out this post about [Ruby Hashes and Arrays](https://mensfeld.pl/2015/05/ruby-hash-initializing-why-do-you-think-you-have-a-hash-but-you-have-an-array/). What did the benchmarks mean in that case?
- Read the rest of the [rbspy docs](https://rbspy.github.io/), and in particular the [Questions to Ask When Optimizing](https://rbspy.github.io/optimization-questions/)
