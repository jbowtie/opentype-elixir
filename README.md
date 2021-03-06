# OpenType

[![Build Status](https://travis-ci.org/jbowtie/opentype-elixir.svg?branch=master)](https://travis-ci.org/jbowtie/opentype-elixir)
[![codecov](https://codecov.io/gh/jbowtie/opentype-elixir/branch/master/graph/badge.svg)](https://codecov.io/gh/jbowtie/opentype-elixir)
[![Hex Version](https://img.shields.io/hexpm/v/opentype.svg)](https://hex.pm/packages/opentype)


This pure Elixir module provides facilities for working with OpenType and TrueType fonts. To date it is able to parse them, perform glyph
substitution and positioning, and handle shaping for European and cursive scripts (specifically scripts like Arabic, Syriac and N'ko).

Output for supported scripts is roughly beta quality -- additional work on mark positioning in particular is required.

Shapers for Indic, Thai, Korean and Uniscribe-compatible scripts require further development.

## Installation

The package can be installed by adding `opentype` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:opentype, "~> 0.5.0"}]
end
```

