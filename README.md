# Blazor Rich Text Editor — Forum Post Editor

Simple demo showing a forum-style page built with the Syncfusion Blazor Rich Text Editor.

## Project Overview

- Displays a question and a list of answers.
- Provides a Rich Text Editor for composing replies with basic validation.
- Lets users post replies which appear in the answer list (sample data only).

## Prerequisites

- .NET 8.0 SDK
- Visual Studio 2022+ or VS Code
- Syncfusion Blazor packages (a license may be required)

## Quick setup

Installation

```bash
git clone https://github.com/SyncfusionExamples/blazor-richtexteditor-forum-post-editor.git
cd blazor-richtexteditor-forum-post-editor
```

Restore NuGet packages

```bash
dotnet restore
```

Run the application

```bash
dotnet run
```

## How to use

1. Open the running app in your browser.
2. Read the question and existing answers.
3. Type a reply in the editor, then click "Post Reply". The sample enforces a minimum length for replies.

## Troubleshooting

- If the app does not start, run `dotnet restore` and ensure the solution builds.
- If validation prevents posting, extend the reply text to meet the minimum length.

## Support

This sample is provided for demonstration purposes. For issues, open an issue in the repository.

## See also

- [Online examples](https://blazor.syncfusion.com/demos/rich-text-editor/overview?theme=fluent2)
- [Documentation](https://blazor.syncfusion.com/documentation/rich-text-editor/getting-started-webapp)
