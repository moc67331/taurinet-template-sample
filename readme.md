# ⚠️ Warning

This is a sample project, and unofficially.    
It is no longer supported or maintained.

# TauriNET Template

This project is a TauriNET template creator (similar to this one):  
https://github.com/RubenPX/TauriNET/

# Quick Start

1. Install pnpm, the .NET 8 SDK, and the Rust toolchain.

2. Clone this project  

3. Run the following command in this folder:
```sh
dotnet run --project .\setup\setup.csproj
```

Or install the project as a .NET template and run `dotnet new`
```sh
dotnet new install .\

# change directory to your target folder and run  
dotnet new tauri-net
```

4. Remove unnecessary folders (It's setup scripts)  
```bat
REM for windows on cmd.exe
rmdir /s /q .\setup
```

```sh
# for osx or linux
rm -rf ./setup
```
