# Raft/Paxos and other consensus algorithms, Vaidhy

Presented by [Vaidhy][presenter]

Paxos and Raft are two algorithms for getting one answer from a group of
unreliable processors. Some of the more popular use-cases for such algorithms
are leader election, distributed locking, distributed log replication and so on.

Paxos was originally presented by Leslie Lamport in a very entertaining paper
(that was rejected for publication many times). However, generalized Paxos is
considered extremely hard to implement.

Raft was born as a easy to understand consensus algorithm and had several
implementations to its credit.

In this session, I am planning to go over the problem of distributed log
replication, walk through Paxos and its derivatives and then go through Raft. We
can take a quick shot at implementing it, if time permits.

## Links
- [Paper][paper]
- [Raft Visualization][visualization]
- [Slides and Code][slides]
- [Part-time Parliament][parttime]
- [Complete Thesis][thesis]
- [Paxos made simple][simple]
- [Slides and Code][slides]
- [Meetup Page][meetup]


[presenter]: https://twitter.com/
[paper]: ./raft.pdf
[slides]: ./slides.pdf
[parttime]: ./lamport-paxos.pdf
[simple]: ./paxos-simple.pdf
[thesis]: ./thesis.pdf
[meetup]: http://www.meetup.com/Papers-we-love-Bangalore/events/218615831/
[visualization]: http://thesecretlivesofdata.com/raft/
