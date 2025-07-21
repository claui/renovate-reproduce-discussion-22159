# 22159

## Current behavior

Renovate attempts to update:

- the `commons-io` package to an ancient version `20030203.*`, and

- the `commons-collections` package to the ancient version `20040616`.

For a detailed writeup, see https://github.com/renovatebot/renovate/discussions/22159#discussion-5190942.

## Expected behavior

Those ancient versions should have been ignored, because:

1. these libraries are so widely used and the user can expect an OOBE
   without hiccups like these; and

2. the
   [web interface on MVN Repository](https://mvnrepository.com/artifact/commons-io/commons-io)
   also manages to sort the ancient versions correctly.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/22159
