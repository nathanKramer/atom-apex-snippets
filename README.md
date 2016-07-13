# Apex Snippets

[<img src="https://cdn-business.discourse.org/uploads/github_atom/490/d8548f4ce56f1599.png" width="48">](https://github.com/nathanKramer/atom-apex-snippets) [<img src="http://c758482.r82.cf2.rackcdn.com/sublime_text_icon_2181.png" width="48">](https://github.com/nathanKramer/apex-snippets)

This is the _Atom_ version
===========================

Note that these were originally generated from my [Sublime Text](https://github.com/nathanKramer/apex-snippets) repository.

There are several defects which I'm currently working through.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Installation](#installation)
- [Getting Started](#getting-started)
  - [Documenting Code](#documenting-code)
  - [Methods](#methods)
  - [Assertions and Debug](#assertions-and-debug)
  - [Visualforce](#visualforce)
  - [Queries and DML](#queries-and-dml)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Installation

I'm still pretty new to Atom, but this seems to work:

`cd ~/.atom && apm install modular-snippets && mkdir snippets && cd snippets && git clone https://github.com/nathanKramer/atom-apex-snippets`

## Getting Started

In order to make best use of these snippets, I would recommend reading them.

Here are a few good ones to start with.

### Documenting Code

When documenting a file, use [/*f](/filecomment.cson)

When documenting a method, use [/*](/comment.cson)

When documenting a test method, use [/*t](/test_method.cson)

### Methods

You can create apex methods with [method](/method.cson)

For void methods, use the very similar [methodv](/method.cson)

For test methods, use [test](/test_method.cson)

For test factory methods, use [trm](/test_record_method.cson)

### Assertions and Debug

Use [assert](/assert.cson) for plain assertions

Use [asserte](/assert_equals.cson) for equality assertions

Use [debug](/debug.cson) for debugging

### Visualforce

When adding Page messages in your controller (Error, Info, Fatal, Warning):

- [Ame](/add_message_error.cson)
- [Ami](/add_message_info.cson)
- [Amf](/add_message_fatal.cson)
- [Amw](/add_message_warning.cson)

To construct a standard controller, use [Aps](/initialise_standard_controller.cson)

To construct a standard set controller, use [Apss](/initialise_standard_set_controller.cson)

### Queries and DML

For a quick inline query use [query](/soql_query.cson)

For a larger query use [querybig](/soql_query_big.cson)

For a try catched insert with rollback, try [tcd](/safe_dml.cson)
