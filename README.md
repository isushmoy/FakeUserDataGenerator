# FakeUserDataGenerator

**FakeUserDataGenerator** is a Blazor Web App that generates random user data with customizable error application. This project demonstrates infinite scrolling, data generation for different regions, and supports export to CSV.

## Features

- **Random User Data Generation**: Generates fake user data (name, address, phone etc.) using the Bogus library.
- **Infinite Scrolling**: Automatically loads more user data as you scroll.
- **Error Injection**: Simulate data errors (e.g., in names or addresses) by applying customizable noise levels to the generated data.
- **Seed Control**: Change the seed value to regenerate identical data.
- **CSV Export**: Export currently displayed data to CSV with correct formatting.

## Technology Stack

- **C#** (primary programming language)
- **Blazor (Server)**
- **.NET 8**
- **Faker Library** for random data generation
- **Azure App Services** for deployment
