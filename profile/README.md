Apertium is a [rule-based machine translation](https://en.wikipedia.org/wiki/Rule-based_machine_translation)
toolchain and ecosystem, with many of our tools based on
[finite-state transducers](https://en.wikipedia.org/wiki/Finite-state_transducer).

Our language agnostic tools are native and written in
[C++](https://en.wikipedia.org/wiki/C++). The various development helpers are
mostly in [Python](https://python.org/).

Our language data is in various formats, including XML and other human-editable
texts. Language data is split into single-language packages that can analyse
and generate a given language, and translation pairs that perform transfer and
transformation between two languages. The single-language packages are shared
amongst many pairs.

If you wish to contribute to the language agnostic native tools
you'll need to know C++.

If you wish to contribute language data to Apertium, your contributions should
fit in our [existing pipeline](https://wiki.apertium.org/wiki/Apertium_system_architecture).
That is, it should be rule-based and deterministic. We will happily
[help you learn](https://wiki.apertium.org/wiki/Contact) our formats and
methods, and we know from experience it is possible to learn and use Apertium
in short time.

We do not currently include any [statistical](https://en.wikipedia.org/wiki/Statistical_machine_translation)
or [neural](https://en.wikipedia.org/wiki/Neural_machine_translation) machine
translation tools or methods. We are often asked if contributions can be made
with statistical or neural systems, but for now they cannot.

For more information about how to contribute, see [Contributing](https://wiki.apertium.org/wiki/Contributing).
