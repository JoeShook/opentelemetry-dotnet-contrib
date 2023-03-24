# Changelog - OpenTelemetry.PersistentStorage.FileSystem

## 1.0.0-beta.2 (Unreleased)

* Going forward the NuGet package will be
  [`OpenTelemetry.PersistentStorage.FileSystem`](https://www.nuget.org/packages/OpenTelemetry.Extensions.FileSystem).
  Older versions will remain at
  [`OpenTelemetry.Extensions.PersistentStorage`](https://www.nuget.org/packages/OpenTelemetry.Extensions.PersistentStorage)
  [(#1079)](https://github.com/open-telemetry/opentelemetry-dotnet-contrib/pull/1079)

  Migration:

  * In code update namespaces (e.g. `using
    OpenTelemetry.Extensions.PersistentStorage` -> `using
    OpenTelemetry.Extensions.FileSystem`)

## 1.0.0-beta.1

* Invalid path or permissions issues will now result in `FileBlobProvider`
  initialization failure by throwing exception.
  ([#578](https://github.com/open-telemetry/opentelemetry-dotnet-contrib/pull/578))

## 1.0.0-alpha.4

* Update implementation to use
  Opentelemetry.Extensions.PersistentStorage.Abstractions.
  [363](https://github.com/open-telemetry/opentelemetry-dotnet-contrib/pull/363)

## 1.0.0-alpha.3

* Going forward the NuGet package will be
  [`OpenTelemetry.Extensions.PersistentStorage`](https://www.nuget.org/packages/OpenTelemetry.Extensions.PersistentStorage).
  Older versions will remain at
  [`OpenTelemetry.Contrib.Extensions.PersistentStorage`](https://www.nuget.org/packages/OpenTelemetry.Contrib.Extensions.PersistentStorage)
  [(#258)](https://github.com/open-telemetry/opentelemetry-dotnet-contrib/pull/258)

  Migration:

  * In code update namespaces (eg `using
    OpenTelemetry.Contrib.Extensions.PersistentStorage` -> `using
    OpenTelemetry.Extensions.PersistentStorage`)

## 1.0.0-alpha2

This is the first release for the
`OpenTelemetry.Contrib.Extensions.PersistentStorage` project.

For more details, please refer to the [README](README.md)