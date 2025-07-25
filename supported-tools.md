# ALE Supported Languages and Tools

This plugin supports the following languages and tools. All available
tools will be run in combination, so they can be complementary.

<!--
Keep the table rows sorted alphabetically by the language name,
and the tools in the tools column sorted alphabetically by the tool
name. That seems to be the fairest way to arrange this table.

Remember to also update doc/ale.txt, which has a similar list with different
formatting.
-->

**Legend**

|      Key      |             Definition                                            |
| ------------- | ----------------------------------------------------------------- |
| :floppy_disk: | May only run on files on disk (see: `help ale-lint-file-linters`  |
|   :warning:   | Disabled by default                                               |

---

* Ada
  * [ada_language_server](https://github.com/AdaCore/ada_language_server)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [gcc](https://gcc.gnu.org)
  * [gnatpp](https://docs.adacore.com/gnat_ugn-docs/html/gnat_ugn/gnat_ugn/gnat_utility_programs.html#the-gnat-pretty-printer-gnatpp) :floppy_disk:
* Ansible
  * [ansible-language-server](https://github.com/ansible/ansible-language-server/)
  * [ansible-lint](https://github.com/willthames/ansible-lint) :floppy_disk:
* API Blueprint
  * [drafter](https://github.com/apiaryio/drafter)
* APKBUILD
  * [apkbuild-fixer](https://gitlab.alpinelinux.org/Leo/atools)
  * [apkbuild-lint](https://gitlab.alpinelinux.org/Leo/atools)
  * [secfixes-check](https://gitlab.alpinelinux.org/Leo/atools)
* AsciiDoc
  * [alex](https://github.com/get-alex/alex)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [languagetool](https://languagetool.org/) :floppy_disk:
  * [proselint](http://proselint.com/)
  * [redpen](http://redpen.cc/)
  * [textlint](https://textlint.github.io/)
  * [vale](https://github.com/ValeLint/vale)
  * [write-good](https://github.com/btford/write-good)
* ASM
  * [gcc](https://gcc.gnu.org)
  * [llvm-mc](https://llvm.org)
* Astro
  * [eslint](http://eslint.org/)
  * [prettier](https://github.com/prettier/prettier)
* AVRA
  * [avra](https://github.com/Ro5bert/avra)
* Awk
  * [gawk](https://www.gnu.org/software/gawk/)
* Bash
  * [bashate](https://github.com/openstack/bashate)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [language-server](https://github.com/mads-hartmann/bash-language-server)
  * shell [-n flag](https://www.gnu.org/software/bash/manual/bash.html#index-set)
  * [shellcheck](https://www.shellcheck.net/)
  * [shfmt](https://github.com/mvdan/sh)
* Bats
  * [shellcheck](https://www.shellcheck.net/)
* Bazel
  * [buildifier](https://github.com/bazelbuild/buildtools)
* BibTeX
  * [bibclean](http://ftp.math.utah.edu/pub/bibclean/)
* Bicep
  * [bicep](https://github.com/Azure/bicep) :floppy_disk:
* Bindzone
  * [checkzone](https://bind9.readthedocs.io/en/stable/manpages.html#named-checkzone-zone-file-validation-tool)
* BitBake
  * [oelint-adv](https://github.com/priv-kweihmann/oelint-adv)
* Bourne Shell
  * shell [-n flag](http://linux.die.net/man/1/sh)
  * [shellcheck](https://www.shellcheck.net/)
  * [shfmt](https://github.com/mvdan/sh)
* C
  * [astyle](http://astyle.sourceforge.net/)
  * [ccls](https://github.com/MaskRay/ccls)
  * [clang](http://clang.llvm.org/)
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [clangcheck](http://clang.llvm.org/docs/ClangCheck.html) :floppy_disk:
  * [clangd](https://clang.llvm.org/extra/clangd.html)
  * [clangtidy](http://clang.llvm.org/extra/clang-tidy/) :floppy_disk:
  * [cppcheck](http://cppcheck.sourceforge.net)
  * [cpplint](https://github.com/cpplint/cpplint)
  * [cquery](https://github.com/cquery-project/cquery)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [flawfinder](https://www.dwheeler.com/flawfinder/)
  * [gcc](https://gcc.gnu.org/)
  * [uncrustify](https://github.com/uncrustify/uncrustify)
* C#
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [csc](http://www.mono-project.com/docs/about-mono/languages/csharp/) :floppy_disk: see:`help ale-cs-csc` for details and configuration
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [dotnet-format](https://github.com/dotnet/format)
  * [mcs](http://www.mono-project.com/docs/about-mono/languages/csharp/) see:`help ale-cs-mcs` for details
  * [mcsc](http://www.mono-project.com/docs/about-mono/languages/csharp/) :floppy_disk: see:`help ale-cs-mcsc` for details and configuration
  * [uncrustify](https://github.com/uncrustify/uncrustify)
* C++ (filetype cpp)
  * [astyle](http://astyle.sourceforge.net/)
  * [ccls](https://github.com/MaskRay/ccls)
  * [clang](http://clang.llvm.org/)
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [clangcheck](http://clang.llvm.org/docs/ClangCheck.html) :floppy_disk:
  * [clangd](https://clang.llvm.org/extra/clangd.html)
  * [clangtidy](http://clang.llvm.org/extra/clang-tidy/) :floppy_disk:
  * [clazy](https://github.com/KDE/clazy) :floppy_disk:
  * [cppcheck](http://cppcheck.sourceforge.net)
  * [cpplint](https://github.com/google/styleguide/tree/gh-pages/cpplint) :floppy_disk:
  * [cquery](https://github.com/cquery-project/cquery)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [flawfinder](https://www.dwheeler.com/flawfinder/)
  * [gcc](https://gcc.gnu.org/)
  * [uncrustify](https://github.com/uncrustify/uncrustify)
* C3
  * [c3lsp](https://github.com/pherrymason/c3-lsp)
* Cairo
  * [scarb](https://docs.swmansion.com/scarb/) :floppy_disk:
  * [starknet](https://starknet.io/docs)
* Chef
  * [cookstyle](https://docs.chef.io/cookstyle.html)
  * [foodcritic](http://www.foodcritic.io/) :floppy_disk:
* Clojure
  * [clj-kondo](https://github.com/borkdude/clj-kondo)
  * [cljfmt](https://github.com/weavejester/cljfmt)
  * [joker](https://github.com/candid82/joker)
* CloudFormation
  * [cfn-python-lint](https://github.com/awslabs/cfn-python-lint)
* CMake
  * [cmake-format](https://github.com/cheshirekow/cmake_format)
  * [cmake-lint](https://github.com/cheshirekow/cmake_format)
  * [cmakelint](https://github.com/cmake-lint/cmake-lint)
* CoffeeScript
  * [coffee](http://coffeescript.org/)
  * [coffeelint](https://www.npmjs.com/package/coffeelint)
* Crystal
  * [ameba](https://github.com/veelenga/ameba) :floppy_disk:
  * [crystal](https://crystal-lang.org/) :floppy_disk:
* CSS
  * [VSCode CSS language server](https://github.com/hrsh7th/vscode-langservers-extracted)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [css-beautify](https://github.com/beautify-web/js-beautify)
  * [csslint](http://csslint.net/)
  * [fecs](http://fecs.baidu.com/)
  * [prettier](https://github.com/prettier/prettier)
  * [stylelint](https://github.com/stylelint/stylelint)
* Cucumber
  * [cucumber](https://cucumber.io/)
* CUDA
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [clangd](https://clang.llvm.org/extra/clangd.html)
  * [nvcc](http://docs.nvidia.com/cuda/cuda-compiler-driver-nvcc/index.html) :floppy_disk:
* Cypher
  * [cypher-lint](https://github.com/cleishm/libcypher-parser)
* Cython (pyrex filetype)
  * [cython](http://cython.org/)
* D
  * [dfmt](https://github.com/dlang-community/dfmt)
  * [dls](https://github.com/d-language-server/dls)
  * [dmd](https://dlang.org/dmd-linux.html)
  * [uncrustify](https://github.com/uncrustify/uncrustify)
* Dafny
  * [dafny](https://rise4fun.com/Dafny) :floppy_disk:
* Dart
  * [analysis_server](https://github.com/dart-lang/sdk/tree/master/pkg/analysis_server)
  * [dart-analyze](https://github.com/dart-lang/sdk/tree/master/pkg/analyzer_cli) :floppy_disk:
  * [dart-format](https://github.com/dart-lang/sdk/tree/master/utils/dartfmt)
  * [dartfmt](https://github.com/dart-lang/sdk/tree/master/utils/dartfmt)
  * [language_server](https://github.com/natebosch/dart_language_server)
* desktop
  * [desktop-file-validate](https://www.freedesktop.org/wiki/Software/desktop-file-utils/)
* Dhall
  * [dhall-format](https://github.com/dhall-lang/dhall-lang)
  * [dhall-freeze](https://github.com/dhall-lang/dhall-lang)
  * [dhall-lint](https://github.com/dhall-lang/dhall-lang)
* Dockerfile
  * [dockerfile_lint](https://github.com/projectatomic/dockerfile_lint)
  * [dockerlinter](https://github.com/buddy-works/dockerfile-linter)
  * [dprint](https://dprint.dev)
  * [hadolint](https://github.com/hadolint/hadolint)
* Elixir
  * [credo](https://github.com/rrrene/credo)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell) :warning:
  * [dialyxir](https://github.com/jeremyjh/dialyxir)
  * [dogma](https://github.com/lpil/dogma) :floppy_disk:
  * [elixir-ls](https://github.com/elixir-lsp/elixir-ls) :warning:
  * [lexical](https://github.com/lexical-lsp/lexical) :warning:
  * [mix](https://hexdocs.pm/mix/Mix.html) :warning: :floppy_disk:
* Elm
  * [elm-format](https://github.com/avh4/elm-format)
  * [elm-ls](https://github.com/elm-tooling/elm-language-server)
  * [elm-make](https://github.com/elm/compiler)
* Erb
  * [erb](https://apidock.com/ruby/ERB)
  * [erb-formatter](https://github.com/nebulab/erb-formatter)
  * [erblint](https://github.com/Shopify/erb-lint)
  * [erubi](https://github.com/jeremyevans/erubi)
  * [erubis](https://github.com/kwatch/erubis)
  * [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)
  * [ruumba](https://github.com/ericqweinstein/ruumba)
* Erlang
  * [SyntaxErl](https://github.com/ten0s/syntaxerl)
  * [dialyzer](http://erlang.org/doc/man/dialyzer.html) :floppy_disk:
  * [elvis](https://github.com/inaka/elvis) :floppy_disk:
  * [erlang-mode](https://www.erlang.org/doc/apps/tools/erlang_mode_chapter.html) (The Erlang mode for Emacs)
  * [erlang_ls](https://github.com/erlang-ls/erlang_ls)
  * [erlc](http://erlang.org/doc/man/erlc.html)
  * [erlfmt](https://github.com/WhatsApp/erlfmt)
* Fish
  * fish [-n flag](https://linux.die.net/man/1/fish)
  * [fish_indent](https://fishshell.com/docs/current/cmds/fish_indent.html)
* Fortran
  * [fortitude](https://github.com/PlasmaFAIR/fortitude)
  * [gcc](https://gcc.gnu.org/)
  * [language_server](https://github.com/hansec/fortran-language-server)
* Fountain
  * [proselint](http://proselint.com/)
* FusionScript
  * [fusion-lint](https://github.com/RyanSquared/fusionscript)
* Git Commit Messages
  * [gitlint](https://github.com/jorisroovers/gitlint)
* Gleam
  * [gleam_format](https://github.com/gleam-lang/gleam)
  * [gleamlsp](https://github.com/gleam-lang/gleam)
* GLSL
  * [glslang](https://github.com/KhronosGroup/glslang)
  * [glslls](https://github.com/svenstaro/glsl-language-server)
* Go
  * [bingo](https://github.com/saibing/bingo) :warning:
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell) :warning:
  * [go build](https://golang.org/cmd/go/) :warning: :floppy_disk:
  * [go mod](https://golang.org/cmd/go/) :warning: :floppy_disk:
  * [go vet](https://golang.org/cmd/vet/) :floppy_disk:
  * [gofmt](https://golang.org/cmd/gofmt/)
  * [gofumpt](https://github.com/mvdan/gofumpt)
  * [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) :warning:
  * [golangci-lint](https://github.com/golangci/golangci-lint) :warning: :floppy_disk:
  * [golangserver](https://github.com/sourcegraph/go-langserver) :warning:
  * [golines](https://github.com/segmentio/golines)
  * [gopls](https://github.com/golang/go/wiki/gopls)
  * [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) :warning: :floppy_disk:
  * [gotype](https://godoc.org/golang.org/x/tools/cmd/gotype) :warning: :floppy_disk:
  * [revive](https://github.com/mgechev/revive) :warning: :floppy_disk:
  * [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) :warning: :floppy_disk:
* Go HTML Templates
  * [djlint](https://djlint.com/)
* GraphQL
  * [eslint](http://eslint.org/)
  * [gqlint](https://github.com/happylinks/gqlint)
  * [prettier](https://github.com/prettier/prettier)
* Groovy
  * [npm-groovy-lint](https://github.com/nvuillam/npm-groovy-lint)
* Hack
  * [hack](http://hacklang.org/)
  * [hackfmt](https://github.com/facebook/hhvm/tree/master/hphp/hack/hackfmt)
  * [hhast](https://github.com/hhvm/hhast) :warning: (see `:help ale-integration-hack`)
* Haml
  * [haml-lint](https://github.com/brigade/haml-lint)
* Handlebars
  * [djlint](https://djlint.com/)
  * [ember-template-lint](https://github.com/rwjblue/ember-template-lint)
* Haskell
  * [brittany](https://github.com/lspitzner/brittany)
  * [cabal-ghc](https://www.haskell.org/cabal/)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [floskell](https://github.com/ennocramer/floskell)
  * [fourmolu](https://github.com/fourmolu/fourmolu)
  * [ghc](https://www.haskell.org/ghc/)
  * [ghc-mod](https://github.com/DanielG/ghc-mod)
  * [hdevtools](https://hackage.haskell.org/package/hdevtools)
  * [hfmt](https://github.com/danstiner/hfmt)
  * [hie](https://github.com/haskell/haskell-ide-engine)
  * [hindent](https://hackage.haskell.org/package/hindent)
  * [hlint](https://hackage.haskell.org/package/hlint)
  * [hls](https://github.com/haskell/haskell-language-server)
  * [ormolu](https://github.com/tweag/ormolu)
  * [stack-build](https://haskellstack.org/) :floppy_disk:
  * [stack-ghc](https://haskellstack.org/)
  * [stylish-haskell](https://github.com/jaspervdj/stylish-haskell)
* HCL
  * [packer-fmt](https://github.com/hashicorp/packer)
  * [terraform-fmt](https://github.com/hashicorp/terraform)
* HTML
  * [VSCode HTML language server](https://github.com/hrsh7th/vscode-langservers-extracted)
  * [alex](https://github.com/get-alex/alex)
  * [angular](https://www.npmjs.com/package/@angular/language-server)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [djlint](https://www.djlint.com/)
  * [eslint](https://github.com/BenoitZugmeyer/eslint-plugin-html)
  * [fecs](http://fecs.baidu.com/)
  * [html-beautify](https://beautifier.io/)
  * [htmlhint](http://htmlhint.com/)
  * [prettier](https://github.com/prettier/prettier)
  * [proselint](http://proselint.com/)
  * [rustywind](https://github.com/avencera/rustywind)
  * [tidy](http://www.html-tidy.org/)
  * [write-good](https://github.com/btford/write-good)
* HTML Angular
  * [djlint](https://djlint.com/)
* HTML Django
  * [djlint](https://djlint.com/)
* HTTP
  * [kulala_fmt](https://github.com/mistweaverco/kulala-fmt)
* Hurl
  * [hurlfmt](https://hurl.dev)
* Idris
  * [idris](http://www.idris-lang.org/)
* Ink
  * [ink-language-server](https://github.com/ephread/ink-language-server)
* Inko
  * [inko](https://inko-lang.org/) :floppy_disk:
* ISPC
  * [ispc](https://ispc.github.io/) :floppy_disk:
* Java
  * [PMD](https://pmd.github.io/)
  * [checkstyle](http://checkstyle.sourceforge.net) :floppy_disk:
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [eclipselsp](https://github.com/eclipse/eclipse.jdt.ls)
  * [google-java-format](https://github.com/google/google-java-format)
  * [javac](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
  * [javalsp](https://github.com/georgewfraser/vscode-javac)
  * [uncrustify](https://github.com/uncrustify/uncrustify)
* JavaScript
  * [biome](https://biomejs.dev/)
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [deno](https://deno.land/)
  * [dprint](https://dprint.dev/)
  * [eslint](http://eslint.org/)
  * [fecs](http://fecs.baidu.com/)
  * [flow](https://flowtype.org/)
  * [jscs](https://jscs-dev.github.io/)
  * [jshint](http://jshint.com/)
  * [prettier](https://github.com/prettier/prettier)
  * [prettier-eslint](https://github.com/prettier/prettier-eslint-cli)
  * [prettier-standard](https://github.com/sheerun/prettier-standard)
  * [standard](http://standardjs.com/)
  * [tsserver](https://github.com/Microsoft/TypeScript/wiki/Standalone-Server-%28tsserver%29)
  * [xo](https://github.com/sindresorhus/xo)
* Jinja
  * [djlint](https://djlint.com/)
* JSON
  * [VSCode JSON language server](https://github.com/hrsh7th/vscode-langservers-extracted)
  * [biome](https://biomejs.dev/)
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell) :warning:
  * [dprint](https://dprint.dev)
  * [eslint](http://eslint.org/) :warning:
  * [fixjson](https://github.com/rhysd/fixjson)
  * [jq](https://stedolan.github.io/jq/) :warning:
  * [json.tool](https://docs.python.org/3/library/json.html#module-json.tool) :warning:
  * [jsonlint](https://github.com/zaach/jsonlint)
  * [prettier](https://github.com/prettier/prettier)
  * [spectral](https://github.com/stoplightio/spectral)
* JSON5
  * [eslint](http://eslint.org/) :warning:
* JSONC
  * [biome](https://biomejs.dev/)
  * [eslint](http://eslint.org/) :warning:
* Jsonnet
  * [jsonnet-lint](https://jsonnet.org/learning/tools.html)
  * [jsonnetfmt](https://jsonnet.org/learning/tools.html)
* Julia
  * [languageserver](https://github.com/JuliaEditorSupport/LanguageServer.jl)
* Kotlin
  * [kotlinc](https://kotlinlang.org) :floppy_disk:
  * [ktlint](https://ktlint.github.io)
  * [languageserver](https://github.com/fwcd/KotlinLanguageServer) see `:help ale-integration-kotlin` for configuration instructions
* LaTeX
  * [alex](https://github.com/get-alex/alex)
  * [chktex](http://www.nongnu.org/chktex/)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [lacheck](https://www.ctan.org/pkg/lacheck)
  * [proselint](http://proselint.com/)
  * [redpen](http://redpen.cc/)
  * [texlab](https://texlab.netlify.com)
  * [textlint](https://textlint.github.io/)
  * [vale](https://github.com/ValeLint/vale)
  * [write-good](https://github.com/btford/write-good)
* Lean 4
  * [lake](https://github.com/leanprover/lean4)
* Less
  * [lessc](https://www.npmjs.com/package/less)
  * [prettier](https://github.com/prettier/prettier)
  * [stylelint](https://github.com/stylelint/stylelint)
* LLVM
  * [llc](https://llvm.org/docs/CommandGuide/llc.html)
* Lua
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [lua-format](https://github.com/Koihik/LuaFormatter)
  * [lua-language-server](https://github.com/LuaLS/lua-language-server)
  * [luac](https://www.lua.org/manual/5.1/luac.html)
  * [luacheck](https://github.com/mpeterv/luacheck)
  * [luafmt](https://github.com/trixnz/lua-fmt)
  * [selene](https://github.com/Kampfkarren/selene)
  * [stylua](https://github.com/johnnymorganz/stylua)
* Mail
  * [alex](https://github.com/get-alex/alex)
  * [languagetool](https://languagetool.org/) :floppy_disk:
  * [proselint](http://proselint.com/)
  * [vale](https://github.com/ValeLint/vale)
* Make
  * [checkmake](https://github.com/mrtazz/checkmake)
* Markdown
  * [alex](https://github.com/get-alex/alex)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [languagetool](https://languagetool.org/) :floppy_disk:
  * [markdownlint](https://github.com/DavidAnson/markdownlint) :floppy_disk:
  * [marksman](https://github.com/artempyanykh/marksman)
  * [mdl](https://github.com/mivok/markdownlint)
  * [pandoc](https://pandoc.org)
  * [prettier](https://github.com/prettier/prettier)
  * [proselint](http://proselint.com/)
  * [pymarkdown](https://github.com/jackdewinter/pymarkdown)
  * [redpen](http://redpen.cc/)
  * [remark-lint](https://github.com/wooorm/remark-lint)
  * [textlint](https://textlint.github.io/)
  * [vale](https://github.com/ValeLint/vale)
  * [write-good](https://github.com/btford/write-good)
* MATLAB
  * [mlint](https://www.mathworks.com/help/matlab/ref/mlint.html)
* Mercury
  * [mmc](http://mercurylang.org) :floppy_disk:
* NASM
  * [nasm](https://www.nasm.us/) :floppy_disk:
* Nickel
  * [nickel_format](https://github.com/tweag/nickel#formatting)
* Nim
  * [nim check](https://nim-lang.org/docs/nimc.html) :floppy_disk:
  * [nimlsp](https://github.com/PMunch/nimlsp)
  * nimpretty
* nix
  * [alejandra](https://github.com/kamadorueda/alejandra)
  * [deadnix](https://github.com/astro/deadnix)
  * [nix-instantiate](http://nixos.org/nix/manual/#sec-nix-instantiate)
  * [nixfmt](https://github.com/serokell/nixfmt)
  * [nixpkgs-fmt](https://github.com/nix-community/nixpkgs-fmt)
  * [rnix-lsp](https://github.com/nix-community/rnix-lsp)
  * [statix](https://github.com/nerdypepper/statix)
* nroff
  * [alex](https://github.com/get-alex/alex)
  * [proselint](http://proselint.com/)
  * [write-good](https://github.com/btford/write-good)
* Nunjucks
  * [djlint](https://djlint.com/)
* Objective-C
  * [ccls](https://github.com/MaskRay/ccls)
  * [clang](http://clang.llvm.org/)
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [clangd](https://clang.llvm.org/extra/clangd.html)
  * [uncrustify](https://github.com/uncrustify/uncrustify)
* Objective-C++
  * [clang](http://clang.llvm.org/)
  * [clangd](https://clang.llvm.org/extra/clangd.html)
  * [uncrustify](https://github.com/uncrustify/uncrustify)
* OCaml
  * [dune](https://dune.build/)
  * [merlin](https://github.com/the-lambda-church/merlin) see `:help ale-ocaml-merlin` for configuration instructions
  * [ocamlformat](https://github.com/ocaml-ppx/ocamlformat)
  * [ocamllsp](https://github.com/ocaml/ocaml-lsp)
  * [ocp-indent](https://github.com/OCamlPro/ocp-indent)
  * [ols](https://github.com/freebroccolo/ocaml-language-server)
* Odin
  * [ols](https://github.com/DanielGavin/ols)
* OpenApi
  * [ibm_validator](https://github.com/IBM/openapi-validator)
  * [prettier](https://github.com/prettier/prettier)
  * [yamllint](https://yamllint.readthedocs.io/)
* OpenSCAD
  * [SCA2D](https://gitlab.com/bath_open_instrumentation_group/sca2d) :floppy_disk:
  * [scadformat](https://github.com/hugheaves/scadformat)
* Packer (HCL)
  * [packer-fmt-fixer](https://github.com/hashicorp/packer)
* Pascal
  * [ptop](https://www.freepascal.org/tools/ptop.var)
* Pawn
  * [uncrustify](https://github.com/uncrustify/uncrustify)
* Perl
  * [perl -c](https://perl.org/) :warning:
  * [perl-critic](https://metacpan.org/pod/Perl::Critic)
  * [perltidy](https://metacpan.org/pod/distribution/Perl-Tidy/bin/perltidy)
* Perl6
  * [perl6 -c](https://perl6.org) :warning:
* PHP
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [intelephense](https://github.com/bmewburn/intelephense-docs)
  * [langserver](https://github.com/felixfbecker/php-language-server)
  * [phan](https://github.com/phan/phan) see `:help ale-php-phan` to instructions
  * [php -l](https://secure.php.net/)
  * [php-cs-fixer](https://cs.symfony.com)
  * [phpactor](https://github.com/phpactor/phpactor)
  * [phpcbf](https://github.com/squizlabs/PHP_CodeSniffer)
  * [phpcs](https://github.com/squizlabs/PHP_CodeSniffer)
  * [phpmd](https://phpmd.org)
  * [phpstan](https://github.com/phpstan/phpstan)
  * [pint](https://github.com/laravel/pint) :beer:
  * [psalm](https://getpsalm.org) :floppy_disk:
  * [tlint](https://github.com/tightenco/tlint)
* PO
  * [alex](https://github.com/get-alex/alex)
  * [msgfmt](https://www.gnu.org/software/gettext/manual/html_node/msgfmt-Invocation.html)
  * [proselint](http://proselint.com/)
  * [write-good](https://github.com/btford/write-good)
* Pod
  * [alex](https://github.com/get-alex/alex)
  * [proselint](http://proselint.com/)
  * [write-good](https://github.com/btford/write-good)
* Pony
  * [ponyc](https://github.com/ponylang/ponyc)
* PowerShell
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [powershell](https://github.com/PowerShell/PowerShell)
  * [psscriptanalyzer](https://github.com/PowerShell/PSScriptAnalyzer)
* Prolog
  * [swipl](https://github.com/SWI-Prolog/swipl-devel)
* proto
  * [buf-format](https://github.com/bufbuild/buf) :floppy_disk:
  * [buf-lint](https://github.com/bufbuild/buf) :floppy_disk:
  * [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
  * [protoc-gen-lint](https://github.com/ckaznocha/protoc-gen-lint) :floppy_disk:
  * [protolint](https://github.com/yoheimuta/protolint) :floppy_disk:
* Pug
  * [pug-lint](https://github.com/pugjs/pug-lint)
* Puppet
  * [languageserver](https://github.com/lingua-pupuli/puppet-editor-services)
  * [puppet](https://puppet.com)
  * [puppet-lint](https://puppet-lint.com)
* PureScript
  * [purescript-language-server](https://github.com/nwolverson/purescript-language-server)
  * [purs-tidy](https://github.com/natefaubion/purescript-tidy)
  * [purty](https://gitlab.com/joneshf/purty)
* Python
  * [autoflake](https://github.com/myint/autoflake) :floppy_disk:
  * [autoimport](https://lyz-code.github.io/autoimport/)
  * [autopep8](https://github.com/hhatto/autopep8)
  * [bandit](https://github.com/PyCQA/bandit) :warning:
  * [black](https://github.com/psf/black)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [flake8](http://flake8.pycqa.org/en/latest/)
  * [flakehell](https://github.com/flakehell/flakehell)
  * [isort](https://github.com/timothycrosley/isort)
  * [mypy](http://mypy-lang.org/)
  * [prospector](https://github.com/PyCQA/prospector) :warning: :floppy_disk:
  * [pycln](https://github.com/hadialqattan/pycln)
  * [pycodestyle](https://github.com/PyCQA/pycodestyle) :warning:
  * [pydocstyle](https://www.pydocstyle.org/) :warning:
  * [pyflakes](https://github.com/PyCQA/pyflakes)
  * [pyflyby](https://github.com/deshaw/pyflyby) :warning:
  * [pylama](https://github.com/klen/pylama) :floppy_disk:
  * [pylint](https://www.pylint.org/) :floppy_disk:
  * [pylsp](https://github.com/python-lsp/python-lsp-server) :warning:
  * [pyre](https://github.com/facebook/pyre-check) :warning:
  * [pyrefly](https://github.com/facebook/pyrefly) :warning:
  * [pyright](https://github.com/microsoft/pyright)
  * [refurb](https://github.com/dosisod/refurb) :floppy_disk:
  * [reorder-python-imports](https://github.com/asottile/reorder_python_imports)
  * [ruff](https://github.com/charliermarsh/ruff)
  * [ruff-format](https://docs.astral.sh/ruff/formatter/)
  * [unimport](https://github.com/hakancelik96/unimport)
  * [vulture](https://github.com/jendrikseipp/vulture) :warning: :floppy_disk:
  * [yapf](https://github.com/google/yapf)
* QML
  * [qmlfmt](https://github.com/jesperhh/qmlfmt)
  * [qmllint](https://github.com/qt/qtdeclarative/tree/5.11/tools/qmllint)
* R
  * [languageserver](https://github.com/REditorSupport/languageserver)
  * [lintr](https://github.com/jimhester/lintr)
  * [styler](https://github.com/r-lib/styler)
* Racket
  * [racket-langserver](https://github.com/jeapostrophe/racket-langserver/tree/master)
  * [raco](https://docs.racket-lang.org/raco/)
  * [raco_fmt](https://docs.racket-lang.org/fmt/)
* Re:VIEW
  * [redpen](http://redpen.cc/)
* ReasonML
  * [merlin](https://github.com/the-lambda-church/merlin) see `:help ale-reasonml-ols` for configuration instructions
  * [ols](https://github.com/freebroccolo/ocaml-language-server)
  * [reason-language-server](https://github.com/jaredly/reason-language-server)
  * [refmt](https://github.com/reasonml/reason-cli)
* Rego
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [opacheck](https://www.openpolicyagent.org/docs/latest/cli/#opa-check)
  * [opafmt](https://www.openpolicyagent.org/docs/latest/cli/#opa-fmt)
* REST
  * [kulala_fmt](https://github.com/mistweaverco/kulala-fmt)
* reStructuredText
  * [alex](https://github.com/get-alex/alex)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [proselint](http://proselint.com/)
  * [redpen](http://redpen.cc/)
  * [rstcheck](https://github.com/myint/rstcheck)
  * [textlint](https://textlint.github.io/)
  * [vale](https://github.com/ValeLint/vale)
  * [write-good](https://github.com/btford/write-good)
* Robot
  * [rflint](https://github.com/boakley/robotframework-lint)
* Roc
  * [roc_annotate](https://github.com/roc-lang/roc)
  * [roc_format](https://github.com/roc-lang/roc)
  * [roc_language_server](https://github.com/roc-lang/roc)
* RPM spec
  * [rpmlint](https://github.com/rpm-software-management/rpmlint) :warning: (see `:help ale-integration-spec`)
* Ruby
  * [brakeman](http://brakemanscanner.org/) :floppy_disk:
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [debride](https://github.com/seattlerb/debride)
  * [packwerk](https://github.com/Shopify/packwerk) :floppy_disk:
  * [prettier](https://github.com/prettier/plugin-ruby)
  * [rails_best_practices](https://github.com/flyerhzm/rails_best_practices) :floppy_disk:
  * [reek](https://github.com/troessner/reek)
  * [rubocop](https://github.com/bbatsov/rubocop)
  * [ruby](https://www.ruby-lang.org)
  * [rubyfmt](https://github.com/fables-tales/rubyfmt)
  * [rufo](https://github.com/ruby-formatter/rufo)
  * [solargraph](https://solargraph.org)
  * [sorbet](https://github.com/sorbet/sorbet)
  * [standardrb](https://github.com/testdouble/standard)
  * [steep](https://github.com/soutaro/steep)
  * [syntax_tree](https://github.com/ruby-syntax-tree/syntax_tree)
* Rust
  * [cargo](https://github.com/rust-lang/cargo) :floppy_disk: (see `:help ale-integration-rust` for configuration instructions)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [rls](https://github.com/rust-lang-nursery/rls) :warning:
  * [rust-analyzer](https://github.com/rust-analyzer/rust-analyzer) :warning:
  * [rustc](https://www.rust-lang.org/) :warning:
  * [rustfmt](https://github.com/rust-lang-nursery/rustfmt)
* Salt
  * [salt-lint](https://github.com/warpnet/salt-lint)
* Sass
  * [sass-lint](https://www.npmjs.com/package/sass-lint)
  * [stylelint](https://github.com/stylelint/stylelint)
* Scala
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [fsc](https://www.scala-lang.org/old/sites/default/files/linuxsoft_archives/docu/files/tools/fsc.html)
  * [metals](https://scalameta.org/metals/)
  * [sbtserver](https://www.scala-sbt.org/1.x/docs/sbt-server.html)
  * [scalac](http://scala-lang.org)
  * [scalafmt](https://scalameta.org/scalafmt/)
  * [scalastyle](http://www.scalastyle.org)
* SCSS
  * [prettier](https://github.com/prettier/prettier)
  * [sass-lint](https://www.npmjs.com/package/sass-lint)
  * [scss-lint](https://github.com/brigade/scss-lint)
  * [stylelint](https://github.com/stylelint/stylelint)
* Slim
  * [slim-lint](https://github.com/sds/slim-lint)
* SML
  * [smlnj](http://www.smlnj.org/)
* Solidity
  * [forge](https://github.com/foundry-rs/forge)
  * [solc](https://solidity.readthedocs.io/)
  * [solhint](https://github.com/protofire/solhint)
  * [solium](https://github.com/duaraghav8/Solium)
* SQL
  * [dprint](https://dprint.dev)
  * [pgformatter](https://github.com/darold/pgFormatter)
  * [sql-lint](https://github.com/joereynolds/sql-lint)
  * [sqlfluff](https://github.com/sqlfluff/sqlfluff)
  * [sqlfmt](https://github.com/jackc/sqlfmt)
  * [sqlformat](https://github.com/andialbrecht/sqlparse)
  * [sqlint](https://github.com/purcell/sqlint)
* Stylus
  * [stylelint](https://github.com/stylelint/stylelint)
* SugarSS
  * [stylelint](https://github.com/stylelint/stylelint)
* Svelte
  * [prettier](https://github.com/prettier/prettier)
  * [svelteserver](https://github.com/sveltejs/language-tools/tree/master/packages/language-server)
* Swift
  * [Apple swift-format](https://github.com/apple/swift-format)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [sourcekit-lsp](https://github.com/apple/sourcekit-lsp)
  * [swiftformat](https://github.com/nicklockwood/SwiftFormat)
  * [swiftlint](https://github.com/realm/SwiftLint)
* systemd
  * [systemd-analyze](https://www.freedesktop.org/software/systemd/man/systemd-analyze.html) :floppy_disk:
* Tcl
  * [nagelfar](http://nagelfar.sourceforge.net) :floppy_disk:
* Terraform
  * [checkov](https://github.com/bridgecrewio/checkov)
  * [terraform](https://github.com/hashicorp/terraform)
  * [terraform-fmt-fixer](https://github.com/hashicorp/terraform)
  * [terraform-ls](https://github.com/hashicorp/terraform-ls)
  * [terraform-lsp](https://github.com/juliosueiras/terraform-lsp)
  * [tflint](https://github.com/wata727/tflint)
  * [tfsec](https://github.com/aquasecurity/tfsec)
* Texinfo
  * [alex](https://github.com/get-alex/alex)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [proselint](http://proselint.com/)
  * [write-good](https://github.com/btford/write-good)
* Text
  * [alex](https://github.com/get-alex/alex) :warning:
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [languagetool](https://languagetool.org/) :floppy_disk:
  * [proselint](http://proselint.com/) :warning:
  * [redpen](http://redpen.cc/) :warning:
  * [textlint](https://textlint.github.io/) :warning:
  * [vale](https://github.com/ValeLint/vale) :warning:
  * [write-good](https://github.com/btford/write-good) :warning:
* Thrift
  * [thrift](http://thrift.apache.org/)
  * [thriftcheck](https://github.com/pinterest/thriftcheck)
* TOML
  * [dprint](https://dprint.dev)
* TypeScript
  * [biome](https://biomejs.dev/)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [deno](https://deno.land/)
  * [dprint](https://dprint.dev/)
  * [eslint](http://eslint.org/)
  * [fecs](http://fecs.baidu.com/)
  * [prettier](https://github.com/prettier/prettier)
  * [standard](http://standardjs.com/)
  * [tslint](https://github.com/palantir/tslint)
  * [tsserver](https://github.com/Microsoft/TypeScript/wiki/Standalone-Server-%28tsserver%29)
  * typecheck
* Typst
  * [typstyle](https://github.com/Enter-tainer/typstyle)
* V
  * [v](https://github.com/vlang/v/) :floppy_disk:
  * [vfmt](https://github.com/vlang/v/)
* VALA
  * [uncrustify](https://github.com/uncrustify/uncrustify)
  * [vala_lint](https://github.com/vala-lang/vala-lint) :floppy_disk:
* Verilog
  * [hdl-checker](https://pypi.org/project/hdl-checker)
  * [iverilog](https://github.com/steveicarus/iverilog)
  * [slang](https://github.com/MikePopoloski/slang)
  * [verilator](http://www.veripool.org/projects/verilator/wiki/Intro)
  * [vlog](https://www.mentor.com/products/fv/questa/)
  * [xvlog](https://www.xilinx.com/products/design-tools/vivado.html)
  * [yosys](http://www.clifford.at/yosys/) :floppy_disk:
* VHDL
  * [ghdl](https://github.com/ghdl/ghdl)
  * [vcom](https://www.mentor.com/products/fv/questa/)
  * [xvhdl](https://www.xilinx.com/products/design-tools/vivado.html)
* Vim
  * [vimls](https://github.com/iamcco/vim-language-server)
  * [vint](https://github.com/Kuniwak/vint)
* Vim help
  * [alex](https://github.com/get-alex/alex) :warning:
  * [proselint](http://proselint.com/) :warning:
  * [write-good](https://github.com/btford/write-good) :warning:
* Vue
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [prettier](https://github.com/prettier/prettier)
  * [vls](https://github.com/vuejs/vetur/tree/master/server)
  * [volar](https://github.com/johnsoncodehk/volar)
* WGSL
  * [naga](https://github.com/gfx-rs/naga)
* XHTML
  * [alex](https://github.com/get-alex/alex)
  * [cspell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell)
  * [proselint](http://proselint.com/)
  * [write-good](https://github.com/btford/write-good)
* XML
  * [xmllint](http://xmlsoft.org/xmllint.html)
* YAML
  * [actionlint](https://github.com/rhysd/actionlint)
  * [circleci](https://circleci.com/docs/2.0/local-cli) :floppy_disk: :warning:
  * [gitlablint](https://github.com/elijah-roberts/gitlab-lint)
  * [prettier](https://github.com/prettier/prettier)
  * [spectral](https://github.com/stoplightio/spectral)
  * [swaglint](https://github.com/byCedric/swaglint) :warning:
  * [yaml-language-server](https://github.com/redhat-developer/yaml-language-server)
  * [yamlfix](https://lyz-code.github.io/yamlfix)
  * [yamlfmt](https://github.com/google/yamlfmt)
  * [yamllint](https://yamllint.readthedocs.io/)
  * [yq](https://github.com/mikefarah/yq)
* YANG
  * [yang-lsp](https://github.com/theia-ide/yang-lsp)
* Yara
  * [yls](https://github.com/avast/yls)
* Zeek
  * [zeek](http://zeek.org) :floppy_disk:
* Zig
  * [zigfmt](https://github.com/ziglang/zig)
  * [zlint](https://github.com/DonIsaac/zlint)
  * [zls](https://github.com/zigtools/zls)
