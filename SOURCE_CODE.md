# FAQ about source code

## Can we expect Luna Park's code to be open source in the future?

We recognize the value of open source and we're definitely open to the idea of making the Luna Park visual scripting editor open source in the future. However, currently, the code is closely intertwined with our webapp, which won't be open source. Separating the code would require an immense amount of time and resources, which we're not able to commit to right now.

## Can the git repo for Luna Park be made open source since the NPM package source is already available?

We understand the desire for open source and appreciate the accessibility it provides. However, the NPM package source is only a transpiled version of the codebase, and tree-shaking is used to remove any irrelevant code that we're not ready to share. As a result, there is much more to our codebase than what is available through the NPM package.

## How can we be assured of the security of Luna Park if the code is not open source?

We understand the concerns regarding security, but it's important to note that reviewing the entire codebase of a package can be a daunting task. Even if Luna Park were open source, it's unlikely that every user would be able to thoroughly review the entire codebase. However, we ensure that our packages are not obfuscated, allowing for efficient analysis by automated security tools.

## What happens if Luna Park is no longer maintained in the future?

We take this concern seriously, and have addressed it in our licensing terms. If we ever cease active maintenance of Luna Park, we are committed to releasing the entire codebase under a Creative Commons license. This ensures that the code remains accessible and can continue to be used and developed by the community.
