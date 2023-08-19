# Test Breaking Protobufs

This test repo has a github action which fails CI if a backwards incompatible change is introduced to `items.proto`.

An example of a backwards compatible change passing CI can be found here: [Backwards compatible change](https://github.com/Takashiidobe/test-breaking-protobufs/pull/2), and an example of a backwards incompatible change (which breaks CI) can be found here: [Backwards incompatible change](https://github.com/Takashiidobe/test-breaking-protobufs/pull/1)
