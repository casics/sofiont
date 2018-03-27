Softiont<img width="120px" align="right" src=".graphics/noun_719164_cc.svg">
================

_Softiont_ is the _Software Interface Ontology_, a controlled vocabulary of software interfaces.  It is intended to help describe the types of user and program interfaces offered by a software system.

*Authors*:      [Michael Hucka](http://github.com/mhucka) and [Matthew J. Graham](https://github.com/doccosmos)<br>
*Repository*:   [https://github.com/casics/softiont](https://github.com/casics/softiont)<br>
*License*:      Unless otherwise noted, this content is licensed under the [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) license.

☀ Introduction
-----------------------------

One of the goals of the CASICS project is to describe software systems using controlled vocabularies, so that users can more easily find exactly the kind of software they are looking for.  One of the dimensions along which we wanted to categorize software is the kind of interfaces offered for (human) users as well as other software.  For example, does a given software tool provide a graphical user interface meant to be used on a desktop computer, or a command-line interface, or is it a programming toolkit offering only an API?  We began by using the [Software Ontology (SWO)](https://github.com/allysonlister/swo), which was the only ontology we could find that provided the kind of terms we needed, but we ultimately found we needed a bit more depth than SWO offered.  So we began to develop our own ontology of interface types.

_Softiont_ provides terms for both human interface types and programmatic (API) interface types.  The terms can be used to describe the types of interfaces provided to users of a software system, where "user" is taken broadly to mean both human users and software programs.  A given software tool may provide more than one type of interface, of course, and it is perfectly reasonable to use as many Softiont terms as applicable to describe the software tool.

<!--
Some examples of using Softiont terms:

* `ls` is a command-line program available in most Unix-like systems.  It provides only one interface:

    **Softiont** ➜ `User Interface` ➜ `Text-Base User Interface` ➜ `Command-Line Interface`
-->

⁇ Getting help and support
--------------------------

If you find an issue, please submit it in [the GitHub issue tracker](https://github.com/casics/softiont/issues) for this repository.

♬ Contributing &mdash; info for developers
------------------------------------------

A lot remains to be done on CASICS in many areas.  We would be happy to receive your help and participation if you are interested.  Please feel free to contact the developers either via GitHub or the mailing list [casics-team@googlegroups.com](casics-team@googlegroups.com).

Everyone is asked to read and respect the [code of conduct](CONDUCT.md) when participating in this project.

❤️ Acknowledgments
------------------

This material is based upon work supported by the [National Science Foundation](https://nsf.gov) under Grant Number 1533792 (Principal Investigator: Michael Hucka).  Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.

The icon for Softiont is "API" [by mikicon &ndash; icon #719164 in the Noun Project](https://thenounproject.com/search/?q=api&i=719164).  It is used under the terms of a Creative Commons license.

<br>
<div align="center">
  <a href="https://www.nsf.gov">
    <img width="105" height="105" src=".graphics/NSF.svg">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.caltech.edu">
    <img width="100" height="100" src=".graphics/caltech-round.svg">
  </a>
</div>
