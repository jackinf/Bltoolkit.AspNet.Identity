<div align="center">

# BLToolkit ASP.NET Identity

### ASP.NET Identity store backed by the BLToolkit data layer

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Identity](https://img.shields.io/badge/ASP.NET_Identity-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![BLToolkit](https://img.shields.io/badge/BLToolkit-555555?style=for-the-badge&logoColor=white)
[![Repo](https://img.shields.io/badge/GitHub-jackinf%2FBltoolkit.AspNet.Identity-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jackinf/Bltoolkit.AspNet.Identity)

</div>

## Overview

`Bltoolkit.AspNet.Identity` is intended to provide an [ASP.NET Identity](https://learn.microsoft.com/aspnet/identity/) persistence layer implemented on top of [BLToolkit](https://github.com/igor-tkachev/bltoolkit), a lightweight .NET ORM. The goal is to let applications use the standard ASP.NET Identity membership APIs (users, roles, claims, logins) while storing the underlying data through BLToolkit instead of the default Entity Framework provider.

> **Note:** This repository is currently a placeholder. The tracked tree contains only this README and an empty `AGENTS.md` — no source code, project files, or solution have been committed yet.

## Status

This project is in an early / stub state. There is no buildable code in the repository at this time:

- No `.sln` / `.csproj` project files
- No source under a `src/` directory
- No package or dependency manifests

When implementation begins, the typical pieces for a BLToolkit-backed Identity store would include:

- A `UserStore` implementing the ASP.NET Identity store interfaces (`IUserStore`, `IUserPasswordStore`, `IUserRoleStore`, etc.)
- A `RoleStore` for role management
- BLToolkit table mappings for the Identity entities

## Tech Stack

| Area | Technology |
| --- | --- |
| Language | C# |
| Platform | .NET / ASP.NET |
| Membership | ASP.NET Identity |
| Data access | BLToolkit ORM |

## Getting Started

### Prerequisites

- A Visual Studio / .NET build toolchain
- BLToolkit and the ASP.NET Identity core packages

### Installation

```bash
git clone https://github.com/jackinf/Bltoolkit.AspNet.Identity.git
cd Bltoolkit.AspNet.Identity
```

### Running

There are no build or run steps available yet — the repository does not contain a solution or project file to build. Once source code and a `.csproj`/`.sln` are added, this section should be updated with the real `dotnet build` / `msbuild` commands.
