
# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.

# 🍕 Blazing Pizza

A full-stack pizza ordering application built with **ASP.NET Blazor**, demonstrating modern web development with C# and .NET.

## Overview

Blazing Pizza is an interactive web application where users can browse a menu of specialty pizzas, customize orders, and manage their cart — all powered by Blazor's component-based architecture.

## Tech Stack

- **Framework:** ASP.NET Blazor Server
- **Language:** C#
- **Database:** SQLite with Entity Framework Core
- **Frontend:** Razor Components, CSS
- **Architecture:** Component-based with dependency injection

## Features

- Browse and select from specialty pizzas
- Customize pizza orders with toppings and sizes
- Real-time order state management
- Persistent data storage with Entity Framework Core
- RESTful API controllers for order and menu management

## Project Structure
├── Model/              # Data models (Pizza, Order, Topping)
├── Pages/              # Blazor page components
├── Shared/             # Shared layout components
├── wwwroot/            # Static assets (CSS, images)
├── OrderController.cs  # Order API endpoint
├── SpecialsController.cs # Menu specials endpoint
├── PizzaStoreContext.cs  # EF Core database context
├── OrderState.cs       # Application state management
└── SeedData.cs         # Initial database seeding

## Getting Started

### Prerequisites
- [.NET SDK 6.0+](https://dotnet.microsoft.com/download)

### Run Locally
```bash
git clone https://github.com/luansud/BlazingPizza.git
cd BlazingPizza
dotnet run
```
Navigate to `https://localhost:5001` in your browser.

## Learning Context

This project was developed as part of the [Microsoft Learn Blazor tutorial](https://learn.microsoft.com/en-us/training/modules/build-blazor-webassembly-visual-studio-code/), extended with additional features and customizations.

## License

This project is licensed under MIT and CC-BY-4.0 licenses. See [LICENSE](LICENSE) and [LICENSE-CODE](LICENSE-CODE) for details.
