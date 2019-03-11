Thank you for contributing! Every PR is different, but here are some high level rules that should help make it a success. This isn't an exhaustive list, but these are some bullet points that should help make contributing easy.

* When writing your code consider users first, Pion is only as good as what people can build with it!
  - Try to conform to the WebRTC JS API as closely as possible. Users should be able to use API if they know another implementation already.
  - Should be actionable. Many parts of the WebRTC API don't apply to our use cases, use your best judgement.
  - If you are creating something new, create an example to demo it and help users explore it quickly!
  - Separate into reusable modules so others can easily read and reuse your work.
* Create a issue before coding, make sure it will accepted by the community. Gather feedback.
* Create your PR early. Even if the code isn't complete this gives others the chance to know your working on it.
* Make sure all the linters and tests pass, for extra credit try to even raise the code coverage!
  - The rules are available [here](https://github.com/pions/webrtc/blob/master/.travis.yml) and can easily be run locally
* Install the commit message hook `ln -r -s .github/lint-commit-message.sh .git/hooks/commit-msg`
  - This is tested in CI, the rules are available [here](https://github.com/pions/webrtc/blob/master/.github/lint-commit-message.sh)

Once your PR is ready you just need one review by a Pion organization member, then you can merge to master. To become a Pion organization member developer you need to just have one PR merged to master.
