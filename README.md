# fat-jar-spec
A proof of concept for a common specification of a fat jar structure.

Inspired by a [thread](https://groups.google.com/forum/#!topic/microprofile/sWOal05ORT0) in MicroProfile.io maling list.
It is just a proof of concept for me to play with, but the vision is to support the discussion and raise it as a sub-project of MicroProfile.io initiative.
Cooperation is welcome.

## The Specification Document

The [spec](spec) directory contains the written specification.
The root file of the specification is [SUMMARY](spec/SUMMARY.adoc).

## The reference implementation

The [impl](impl) directory contains the reference specification.
The reference specification is a sample project for each type of executable archive. 
Each sample project produces 1 or more artefacts that are reference examples of an executable archive described in this specification.
It is not meant to be used as a reusable project, but to provide a simple working example.
