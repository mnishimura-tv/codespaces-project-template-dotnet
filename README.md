# Blazor Interview Environment with GitHub Codespaces

A clean Blazor Server template configured for technical interviews, with GitHub Codespaces support and pre-installed AI coding assistants.

## Purpose

This repository provides a ready-to-use development environment for conducting technical interviews focused on:
- Blazor Server development
- C# programming skills
- AI-assisted development workflows
- Component architecture and patterns

## Setup Instructions

You have two options for your interview environment:

### Option 1: Your Own Development Environment (Recommended)

**Requirements:**
- .NET 8 SDK ([download here](https://dotnet.microsoft.com/download))
- Your preferred IDE (VS Code, Visual Studio, or Rider)
- Your preferred AI assistant tools (GitHub Copilot, ChatGPT, Claude Code, etc.)

**Setup:**
```bash
git clone <repo-url>
cd codespaces-project-template-dotnet
cd src/BlazorApp
dotnet run
```

Navigate to `http://localhost:5000` to verify it's running.

### Option 2: GitHub Codespaces (No Local Setup Required)

If you don't have .NET installed locally, your interviewer can provide access to a pre-configured Codespaces environment with all tools installed.

## What's Included

- Clean Blazor Server template
- Basic project structure (Components/Pages/, Models/, Services/)
- Simple Counter example showing component state
- Bootstrap 5 for styling
- Dependency injection configured
- Hot reload enabled

## On Interview Day

- Have your environment ready and running
- Your interviewer will provide specific task requirements at the start of the interview
- Have your AI assistant tools accessible

## Project Structure

```
.
├── .devcontainer/          # Codespaces configuration
├── src/BlazorApp/
│   ├── Components/
│   │   ├── Layout/         # Layout components
│   │   ├── Pages/          # Routable page components
│   │   ├── Routes.razor    # Router configuration
│   │   └── App.razor       # Root component
│   ├── wwwroot/
│   │   ├── css/
│   │   └── sample-data/
│   │       └── weather.json  # Sample data
│   └── Program.cs          # Application configuration
└── README.md
```

## Features

### Pre-Configured AI Assistants
- GitHub Copilot
- GitHub Copilot Chat

### Development Tools
- .NET 8 SDK
- C# Dev Kit
- PowerShell
- IntelliCode

### Ready-to-Use Infrastructure
- Dependency injection configured
- Bootstrap 5 included
- Hot reload enabled
- Blazor routing setup
- Interactive Server render mode configured

## Running the Application

### Locally
```bash
cd src/BlazorApp
dotnet run
```

### In Codespaces
The application will build automatically. Run:
```bash
cd src/BlazorApp
dotnet run
```

Navigate to the forwarded port URL shown in the terminal.

## Getting Started

The template provides a minimal starting point:
- **Components/Pages/**: Build routable pages
- **Components/**: Create reusable components

Register new services in `Program.cs` using dependency injection.

## Resources

- [GitHub Codespaces docs](https://docs.github.com/codespaces/overview)
- [Blazor documentation](https://learn.microsoft.com/aspnet/core/blazor/)
- [.NET 8 documentation](https://learn.microsoft.com/dotnet/core/whats-new/dotnet-8)

## Origins

This template is forked from [Microsoft's .NET Codespaces Portfolio Template](https://github.com/github-education-resources/codespaces-project-template-dotnet), switching to server-side rendering and replacing the opinionated Portfolio with the basic Blazor starting app
