# Book of Papers

The purpose of this collection is to form a starting point from which Engineering Teams can base future conversations.

# Causality in Distributed Systems

Vector Clocks are used to resolve siblings in Riak.

* [Time, Clocks, and the Ordering of Events in a Distributed System - Leslie Lamport](https://raw.githubusercontent.com/ChristopherBiscardi/papers/master/papers/time-clocks-and-the-ordering-of-events-in-a-distributed-system.pdf)
  - Precursor to Vector Clocks
* [Timestamps in Message-Passing Systems That Preserve the Partial Ordering - Colin J. Fidge](https://raw.githubusercontent.com/ChristopherBiscardi/papers/master/papers/timestamps-in-message-passing-systems-that-preserve-the-partial-ordering.pdf)
  - Vector Clocks

# Notes
* [Notes on Distributed Systems](https://raw.githubusercontent.com/ChristopherBiscardi/papers/master/papers/notes-on-distributed-systems.pdf)

# Dynamo
* [Dynamo: Amazon’s Highly Available Key-value Store](https://raw.githubusercontent.com/ChristopherBiscardi/papers/master/papers/dynamo.pdf)
  - Riak, Cassandra, etc


# Type Systems

* [On Understanding Types, Data Abstraction, and Polymorphism - Luca Cardelli, Peter Wegner](https://raw.githubusercontent.com/ChristopherBiscardi/papers/master/papers/on-understanding-types-data-abstraction-and-polymorphism.pdf)
  - Covers a fairly large field. ADTs, Quantification, Type Inference, Typed λ-Calculus.
  
# Concurrent Data Access

* [There is no Fork: an Abstraction for Efﬁcient, Concurrent, and Concise Data Access](https://raw.githubusercontent.com/ChristopherBiscardi/papers/master/papers/there-is-no-fork-an-abstraction-for-efficient-concurrent-and-concise-data-access)
  - Covers Haxl, A Facebook open source lib for concurrent data access and caching in Haskell
  
# Recursion Schemes

[Functional Programming with Bananas, Lenses, Envelopes and Barbed Wire](https://raw.githubusercontent.com/ChristopherBiscardi/papers/master/papers/functional-programming-with-bananas-lenses-envelopes-and-barbed-wire.pdf)

###### Quick Reference:
<table border="1">
<tbody><tr>
<th colspan="3">Folds</th>
</tr>
<tr>
<th>Scheme</th>
<th>Description</th>
</tr>
<tr>
<td><a href="http://knol.google.com/k/edward-kmett/catamorphisms/">catamorphism</a></td>
<td>tears down a structure level by level</td>
</tr>
<tr>
<td>paramorphism</td>
<td>tears down a structure with primitive recursion</td>
</tr>
<tr>
<td>zygomorphism</td>
<td>tears down a structure with the aid of a helper function</td>
</tr>
<tr>
<td>histomorphism</td>
<td>tears down a structure with the aid of the previous answers it has given.  </td>
</tr>
<tr>
<td>prepromorphism</td>
<td>tears down a structure after repeatedly applying a natural transformation</td>
</tr>
<tr>
<th colspan="3">Unfolds</th>
</tr>
<tr>
<th>Scheme</th>
<th>Description</th>
</tr>
<tr>
<td>anamorphism</td>
<td>builds up a structure level by level</td>
</tr>
<tr>
<td>apomorphism</td>
<td>builds up a structure opting to return a single level or an entire branch at each point</td>
</tr>
<tr>
<td>futumorphism</td>
<td>builds up a structure multiple levels at a time </td>
</tr>
<tr>
<td>postpromorphism</td>
<td>builds up a structure and repeatedly transforms it with a natural transformation</td>
</tr>
<tr>
<th colspan="3">Refolds</th>
</tr>
<tr>
<th>Scheme</th>
<th>Description</th>
</tr>
<tr>
<td>hylomorphism</td>
<td>builds up and tears down a virtual structure</td>
</tr>
<tr>
<td>chronomorphism</td>
<td>builds up a virtual structure with a futumorphism and tears it down<br>
  with a histomorphism</td>
</tr>
<tr>
<td>synchromorphism</td>
<td>a high level transformation between data structures using a third data structure to queue intermediate results</td>
</tr>
<tr>
<td>exomorphism</td>
<td>a high level transformation between data structures from a trialgebra to a bialgebraga</td>
</tr>
<tr>
<td>metamorphism</td>
<td>a hylomorphism expressed in terms of bialgebras</td>
</tr>
<tr>
<td>metamorphism</td>
<td>A fold followed by an unfold; change of representation</td>
</tr>
<tr>
<td>dynamorphism</td>
<td>builds up a virtual structure with an anamorphism and tears it down with a histomorphism</td>
</tr>
<tr>
<td><a href="http://arxiv.org/abs/cs/0609040">Elgot algebra</a></td>
<td>builds up a structure and tears it down but may shortcircuit the process during construction</td>
</tr>
<tr>
<td><a href="http://comonad.com/reader/2008/elgot-coalgebras/">Elgot coalgebra</a></td>
<td>builds up a structure and tears it down but may shortcircuit the process during deconstruction</td>
</tr>
</tbody></table>