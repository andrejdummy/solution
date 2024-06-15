# Solana Auditor Entry Task

1) The first task is focused on **programming** in Rust. The goal is to write:
- **efficient**,
- **readable** and
- **extensible** code
2) The second task is focused on the **analysis** of the Solana hack. The goal is to write a technical report. The preferred language is English.

You have a maximum of 10 days to finish both tasks. Good luck.

## Rust

### Introduction

The mysterious device is reproducing a virus. After the first four presses, it creates 1, 2, 3, and 5 copies of the virus. With each subsequent click, the viruses multiply, so that the viruses created by the last, the last but one, and the last but three clicks create one copy of themselves. Find out how many viruses are there in the world after you click the button X times.

### Input and output

In the first line of the input is the number `1<=T<=1000` - it determines the number of questions (number of following lines). In each of the next T lines, there is an integer `4<=X<=10^10`. For each X, count how many viruses there are in the world. Since there can be many, just list its remainder after dividing by `10^9 + 7`.

#### Example:
- Input
```shell
3
7
5
47
```
- Output
```
64
20
349633386
```

In the fifth click, the viruses from the first, third and fourth clicks multiply, so 1+3+5=9. Together with the remaining eleven, there are 20 viruses.

### Additional requirements
- The preferred implementation language is Rust but C/C++ is also an acceptable choice.

- Along with the implementation, we also want a `Readme.md` that describes the solution, or you can mention anything you think is relevant.

- The final solution push to the Github repository.

## Analysis of the Solana hack

### Introduction
During the first 5 months of 2022, DeFi hacks have amounted up to $1.4 billion in financial losses. Even though one of the largest hacks was conducted on Solana (Wormhole), Solana's statistics are actually really good compared to other major L1's - both in occurrences and the total amount stolen. Good news: Over 30 major hacks have been conducted since January 2022 and only 3 of them happened on Solana ecosystem.

### Your task:
Write a report describing [Wormhole Hack](https://x.com/wormhole/status/1489001949881978883).

### The report should contain the following sections:
- General description of what happened
- Exploit description (step-by-step)
- Add any arbitrary sections you think are necessary.

### Additional requirements
- It should be a technical report (similar to a post-mortem).
The form is up to you; it can be Tex, Google docs, MD/ADOC file, or anything else.
- The preferred language is English.
- Final report push to the Github repository.
