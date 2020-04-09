---
title: EinsteinDB
description: Distributed Relativistic SQL for OLAP/OLTP with Immutable Append-Log
date: "2020-03-04 01:21:23"
image: assets/img/einsteindbscaled.png
category: Markdown
background: "#353b48"
---
Inspired by HBase and AllegroGraph, EinsteinDB is the furue of High Throughput, Low Latency, on-premise; causal consistent, relativistic linearizable, MySQL compatible databases.

EinstienDB allows you to have the best of both worlds: A Key-Value store a-a BerkeleyDB and a second level which is intended to be a domain schema mutable relational knowledge graph.

Developers need not worry about foreign key constraints, compound uniqueness, indexing, synchronizing; EinsteinDB allows for a new spectrum of the world we live in. 





## Embedded, Flexible, and ACID compliant.

Unlike other traditional NewSQL databases out there, EinsteinDB written in rust and powered by a Haskell Byzantine Fault Tolerant Raft Consesus for Distributed Systems. EinsteinDB is a distributed storage system for managing structured data, and some flexibly unstructured datum, designed to scale horizontally by provisioning and launching sentinel replicas which hanrdle petabytes across thousands of commodity servers.



# Command Query Responsibility Segregation



1. Causets, EinsteinDB's tuples structure themselves allowing the separation of the command from the query.
2. Enable range typed table partition.
3. Full text search, transactability, durable storage, and small memory footprings with SQLite
4. from Datalog to SQL execution.

⋅⋅⋅EinsteinDB's layered storage brings forth a transaction log with first class citizen rights across the Supercolumnar database. 

⋅⋅⋅.⋅⋅ ⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
* Or minuses
* Or pluses

## Links

```Markdown
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com> and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link](https://www.mozilla.org)

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions](http://slashdot.org)

Or leave it empty and use the [link text itself](http://www.reddit.com).

URLs and URLs in angle brackets will automatically get turned into links. http://www.example.com or <http://www.example.com> and sometimes example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

## Blockquotes

```Markdown
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
```

> Blockquotes are very handy in email to emulate reply text. This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

[Reference 1](https://daringfireball.net/projects/markdown/syntax#philosophy) [Reference 2](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)