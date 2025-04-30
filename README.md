# EnvestNetBuddyAi

EnvestNetBuddyAi is a simple Blazor WebAssembly app with a chatbot interface powered by `Purple Pete Assistant`. It features a robot avatar that provides responses to user messages, typing animations, and a neat chat interface using `MudBlazor` components.

## Prerequisites

Before running the project, ensure that you have the following installed on your machine:

1. **.NET SDK** (6.0 or later):
   - You can download and install it from the official [Microsoft .NET download page](https://dotnet.microsoft.com/download).

2. **Visual Studio Code / Visual Studio** (Optional but recommended for development):
   - Visual Studio: [Download Visual Studio](https://visualstudio.microsoft.com/)
   - Visual Studio Code: [Download Visual Studio Code](https://code.visualstudio.com/)

3. **MudBlazor NuGet Package**:
   - This project uses the MudBlazor component library for UI elements. The library should be included in the project by default, but ensure it's properly installed with the following command:
     ```bash
     dotnet add package MudBlazor
     ```

## Getting Started

Follow these steps to get a copy of the project running on your local machine:

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/EnvestNetBuddyAi.git
cd EnvestNetBuddyAi
```

### 2. Install Dependencies

Ensure you have all the required dependencies installed. From the project directory, run:

```bash
dotnet restore
```

### 3. Run the Project

To start the application locally, run:

```bash
dotnet run
```

This will build and launch the project in your default browser. The application should be available at `https://localhost:5001` (or another port if specified).

### 4. Open the Project

If you're using **Visual Studio Code** or **Visual Studio**, open the project and press `F5` (or click the "Run" button) to start the application in debug mode.

---

## Features

- **Chat Interface:** A chat box where you can send messages to Purple Pete.
- **Typing Animation:** Bot replies are typed out one character at a time to mimic typing.
- **Robot Avatar:** Purple Pete's avatar changes while typing and responding.
- **Confluence Service (Optional):** Can fetch data from Confluence (requires the Confluence Service to be properly configured).

## File Structure

- `Pages/Home.razor`: Main page of the app with the chat interface and logic.
- `Components/`: Contains reusable UI components like the chat messages display.
- `Services/`: Contains services, e.g., `ConfluenceService`, used for fetching content.
- `wwwroot/`: Static files like avatars and CSS.

## Technologies Used

- **Blazor WebAssembly**: Front-end framework for building interactive web UIs with C#.
- **MudBlazor**: Component library for creating modern, responsive UI elements.
- **C# & .NET**: Backend and frontend logic written in C#.
