# PavelBu Lab Tools

A standalone Blazor WebAssembly site for small browser-only technical utilities.

## Tools

- Radiation dose-rate notes and dose unit conversion
- Electronics Ohm's law and LED resistor math
- IT data size conversion and payload encoding
- X-Ray distance/mAs reference math

## Local run

```powershell
$env:DOTNET_CLI_HOME = Join-Path (Get-Location) '.dotnet-home'
dotnet run
```

## GitHub Pages

The workflow in `.github/workflows/deploy.yml` publishes the Blazor WebAssembly output to GitHub Pages on pushes to `main` or `master`.
