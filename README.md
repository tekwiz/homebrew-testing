**ALL FORMULAE IN THIS REPOSITORY ARE BEING TESTED, INCLUDING FORMULAE IN THE MASTER BRANCH.**
This repository should not be used for production systems.

# Homebrew Testing - TekWiz
This tap contains core formulae that are in testing from
[tekwiz/homebrew-core](https://github.com/tekwiz/homebrew-core).

## Current list of formulae in testing
* [fontforge](Formula/fontforge.rb)

## How do I install these formulae?
Just `brew tap tekwiz/testing` and then `brew install tekwiz/testing/<formula>`.

You can also install via URL:

    brew install https://raw.githubusercontent.com/tekwiz/homebrew-testing/master/<formula>.rb

## Contributing
This repository has no policy for accepting contributions; however, if you think you have a valid
contribution, feel free to submit a pull request.  Be sure to follow the
[Homebrew Code of Conduct][code-of-conduct] and the [GitHub Flow][github-flow]

[code-of-conduct]: https://github.com/Homebrew/brew/blob/master/CODEOFCONDUCT.md "Homebrew Code of Conduct"
[github-flow]: https://guides.github.com/introduction/flow/ "GitHub Guides: Understanding the GitHub Flow"

## Troubleshooting & Documentation
See [Troubleshooting in the Homebrew Core readme][core-troubleshooting].

See [Documentation in the Homebrew Core readme][core-documentation].

[core-troubleshooting]: https://github.com/Homebrew/homebrew-core#troubleshooting "Homebrew Core Readme: Troubleshooting"
[core-documentation]: https://github.com/Homebrew/homebrew-core#documentation "Homebrew Core Readme: Documentation"

## License

Copyright 2016 Travis D. Warlick, Jr.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this code except in
compliance with the License which can be found in [LICENSE.txt](LICENSE.txt). You may also obtain a
copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License
is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
implied. See the License for the specific language governing permissions and limitations under the
License.

### Homebrew Core license notice

The original formulae are licensed under the following copyright:

> Copyright 2009-2016 Homebrew contributors.
>
> Redistribution and use in source and binary forms, with or without
> modification, are permitted provided that the following conditions
> are met:
>
>  1. Redistributions of source code must retain the above copyright
>     notice, this list of conditions and the following disclaimer.
>  2. Redistributions in binary form must reproduce the above copyright
>     notice, this list of conditions and the following disclaimer in the
>     documentation and/or other materials provided with the distribution.
>
> THIS SOFTWARE IS PROVIDED BY THE AUTHOR "AS IS" AND ANY EXPRESS OR
> IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
> OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
> IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT,
> INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT
> NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
> DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
> THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
> (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF
> THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
