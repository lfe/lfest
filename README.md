# lfest [![Build Status](https://travis-ci.org/lfe/lfest.png?branch=master)](https://travis-ci.org/lfe/lfest)

<img src="resources/images/Banners-And-Confetti.png"/>

*REST macros and code for LFE on YAWS*

Introduction
============

Add content to me here!


Dependencies
------------

This project assumes that you have `rebar`_ installed somwhere in your
``$PATH``.

This project depends upon the following, which are installed to the ``deps``
directory of this project when you run ``make deps``:

* `LFE`_ (Lisp Flavored Erlang; needed only to compile)
* `lfeunit`_ (needed only to run the unit tests)


Installation
============

Just add it to your ``rebar.config`` deps:

.. code:: erlang

    {deps, [
        ...
        {lfest, ".*", {git, "git@github.com:YOURNAME/lfest.git", "master"}}
      ]}.


And then do the usual:

.. code:: bash

    $ rebar get-deps
    $ rebar compile


Usage
=====

Add content to me here!

.. Links
.. -----
.. _rebar: https://github.com/rebar/rebar
.. _LFE: https://github.com/rvirding/lfe
.. _lfeunit: https://github.com/lfe/lfeunit