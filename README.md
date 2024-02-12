# Simple Chat Application with .NET 8 Blazor WebAssembly & SignalR

## Overview

This project is about to build a simple chat application using SignalR and Blazor WebAssembly in .NET 8. It shows the real-time communication capabilities between clients and servers, leveraging SignalR for managing chat messages and Blazor WebAssembly for a dynamic client-side user interface.
  ![Screenshot 2024-02-12 091600](https://github.com/bestcoolestp/DotNet_8_Blazor_SignalR_Chatapp/assets/108534975/5eac9644-17e3-4a29-b943-87cc1b99a1fd)

## Key Features

- **Real-Time Communication**: Utilizes SignalR to enable real-time messaging across clients connected to the chat application.
    ![Screenshot 2024-02-12 091535](https://github.com/bestcoolestp/DotNet_8_Blazor_SignalR_Chatapp/assets/108534975/85df8286-119a-4b0c-bd57-38816874c6fc)
- **Blazor WebAssembly**: Employs Blazor WebAssembly for creating interactive web UI components, enhancing user experience with client-side rendering.
- **Simplified Chat Hub**: Implements a ChatHub class to manage chat operations, facilitating the broadcasting of messages to all connected clients seamlessly.
- **Interactive UI Components**: Includes UI components for sending and receiving messages, demonstrating the integration of Blazor components with SignalR.
    ![Screenshot 2024-02-12 092049](https://github.com/bestcoolestp/DotNet_8_Blazor_SignalR_Chatapp/assets/108534975/8438221b-352f-4019-a294-5b52a028a9b2)
- **Ease of Use**: Designed to be straightforward for developers, showcasing the simplicity of building real-time applications with .NET technologies.

## Architecture

The application is structured around a client-server model, utilizing Blazor WebAssembly for the client-side and ASP.NET Core for the server-side:

- **Client**: Built with Blazor WebAssembly, the client-side manages the user interface, handling user inputs, displaying received messages, and maintaining the SignalR hub connection.
- **Server**: The server hosts the SignalR ChatHub, processing incoming chat messages and broadcasting them to all connected clients. It's built with ASP.NET Core and leverages SignalR's hub-and-spoke architecture for real-time communication.

## Getting Started

### Prerequisites

- .NET 8 SDK
- Visual Studio 2022 or later with the ASP.NET and web development workload
- A modern web browser supporting WebAssembly

### Setup

1. Clone the repository to your local machine.
2. Open the solution in Visual Studio.
3. Restore NuGet packages to resolve dependencies.

### Running the Application

1. Set the server project as the startup project.
2. Press F5 or click "Start" in Visual Studio to launch the application. The Blazor WebAssembly client will automatically connect to the SignalR server.
