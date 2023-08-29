# Nested Package Bug

## Steps to Reproduce:

1. Save pubspec.yaml at root to trigger `pub get` via Dart Code (VSCode extension).

## Observed Result

```bash
[nested_package_bug] dart pub get
Resolving dependencies...
Got dependencies!
Resolving dependencies in ./example...
Because example depends on flutter_test from sdk which doesn't exist (the Flutter SDK is not available), version solving failed.

Flutter users should run `flutter pub get` instead of `dart pub get`.
exit code 69
```
