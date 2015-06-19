cc_library(
  name = "stringpiece",
  srcs = ["re2/stringpiece.cc"],
  export_incs = ["."],
)

cc_library(
  name = "re2",
  srcs = [
    "re2/bitstate.cc",
    "re2/compile.cc",
    "re2/dfa.cc",
    "re2/filtered_re2.cc",
    "re2/mimics_pcre.cc",
    "re2/nfa.cc",
    "re2/onepass.cc",
    "re2/parse.cc",
    "re2/perl_groups.cc",
    "re2/prefilter.cc",
    "re2/prefilter_tree.cc",
    "re2/prog.cc",
    "re2/re2.cc",
    "re2/regexp.cc",
    "re2/set.cc",
    "re2/simplify.cc",
    "re2/tostring.cc",
    "re2/unicode_casefold.cc",
    "re2/unicode_groups.cc",
    "util/hash.cc",
    "util/rune.cc",
    "util/stringprintf.cc",
    "util/strutil.cc",
    "util/valgrind.cc",
  ],
  deps = [
    ":stringpiece",
    "#pthread",
  ],
)

cc_library(
  name = "test",
  srcs = [
    "re2/testing/backtrack.cc",
    "re2/testing/dump.cc",
    "re2/testing/regexp_generator.cc",
    "re2/testing/string_generator.cc",
    "re2/testing/tester.cc",
    "util/pcre.cc",
    "util/random.cc",
    "util/test.cc",
  ],
  deps = [
    ":re2",
  ],
)

cc_test(
  name = "charclass_test",
  srcs = [
    "re2/testing/charclass_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "compile_test",
  srcs = [
    "re2/testing/compile_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "filtered_re2_test",
  srcs = [
    "re2/testing/filtered_re2_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "mimics_pcre_test",
  srcs = [
    "re2/testing/mimics_pcre_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "parse_test",
  srcs = [
    "re2/testing/parse_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "possible_match_test",
  srcs = [
    "re2/testing/possible_match_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "re2_test",
  srcs = [
    "re2/testing/re2_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "re2_arg_test",
  srcs = [
    "re2/testing/re2_arg_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "regexp_test",
  srcs = [
    "re2/testing/regexp_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "required_prefix_test",
  srcs = [
    "re2/testing/required_prefix_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "search_test",
  srcs = [
    "re2/testing/search_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "set_test",
  srcs = [
    "re2/testing/set_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "simplify_test",
  srcs = [
    "re2/testing/simplify_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)

cc_test(
  name = "string_generator_test",
  srcs = [
    "re2/testing/string_generator_test.cc",
  ],
  deps = [
    ":re2",
    ":test",
  ],
)
