# herdstat

> **Warning**
> `herdstat` is work in progress and neither feature complete nor tested thoroughly.

`herdstat` is a tool for analyzing and visualizing metrics of Open Source projects hosted on GitHub. As of today its
functionality is limited to generate GitHub-style contribution graphs for individual repository or complete GitHub
organisations.

## `herdstat` Contribution Graph

The `herdstat`-generated contribution graph for the [herdstat organization](https://github.com/herdstat) looks like
this:

<img src="contribution-graph.svg" alt="herdstat contribution graph" width="100%">

## Namesake

`herdstat` is composed of the words _herd_, which means a group of people who usually have a common bond, and _stat_,
which is a well-known Linux command line utility that displays detailed information about files. So replacing _file_
with _open source community_ (= _herd_) does the trick in understanding why we have chosen that name.

## Org Structure

The [herdstat organization](https://github.com/herdstat) currently contains the following repositories:

- [herdstat](https://github.com/herdstat/herdstat) hosts the `herdstat` CLI that implements most of herdstat's
  functionality.
- [herdstat-action](https://github.com/herdstat/herdstat-action) contains the codebase for the `herdstat` GitHub action.
- [herdstat-example](https://github.com/herdstat/herdstat-example) is a sample repository showcasing basic usage of
  the `herdstat` GitHub action.