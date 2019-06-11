# building/running

# Dotnet core notes

- JSON config is replaced to use Json.NET
- `Application.StartupPath` is not available in .NET core, current directory will be used instead
- Removed Windows.Form references from `Program.cs`
- Il2CppDummyDll can not be included as resource because of this issue: https://github.com/microsoft/msbuild/issues/2221 so it will instead be read from `Il2CppDummyDll.dll.template`
