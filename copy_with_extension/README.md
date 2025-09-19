[![Pub Package](https://img.shields.io/pub/v/copy_with_extension.svg)](https://pub.dev/packages/copy_with_extension)

Defines the annotation used by [copy_with_extension_gen](https://pub.dev/packages/copy_with_extension_gen) to generate `copyWith` extensions.

For usage details, see [copy_with_extension_gen](https://pub.dev/packages/copy_with_extension_gen).

For insight into how this package works, see [my blog post](https://alexander-kirsch.com/blog/dart-extensions).

---

## Enhancement

- add new flag `allowNullForNonNullableFields` to `@CopyWith()` so as to allow passing `null` to non-nullable arguments in copywith call