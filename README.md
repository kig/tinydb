# TinyDb

TinyDB or `tinydb` is a small-footprint, in-memory database, designed for the [Zeno](https://gitlab.com/zeno-src/zeno) editor.

This database aims to provide an easy frontend to an efficiant in-memory database (that can also be dumped to a file). It purposefully disallows duplicate items to be sorted due to constrains with hash tables.