# Roblox Multilauncher | Multi-Instance Support for Roblox

Roblox MultiLauncher is a lightweight, multi-instance Roblox launcher that allows you to bypass Roblox's default singleton restriction, enabling you to run multiple accounts simultaneously. Unlike the official Roblox client, which automatically shuts down new instances when launched, Roblox MultiLauncher lets you easily manage multiple sessions without interference. With seamless system tray integration, you can keep the app running in the background, ensuring a smooth and efficient experience while playing or testing across multiple Roblox accounts.

## Disclaimer

This project is a **fork** of the original [MultiBloxy](https://github.com/Zgoly/MultiBloxy). The code provided here is offered under the **MIT License** unless otherwise stated. By using this app, you agree to the terms of the license. For more information on the license and usage, refer to the [LICENSE](LICENSE) file in the repository.

This fork includes **enhancements**, **bug fixes**, and **optimizations** for better performance and compatibility with the latest versions of Roblox and Windows.

## Key Features

- **Multi-Instance Support**: Easily run multiple Roblox instances simultaneously.
- **System Tray Integration**: Minimize the app to the system tray for quick access and background operation.
- **Lightweight and Efficient**: Optimized for minimal resource consumption and fast performance.

## Prerequisites

- **Windows 7 (SP1), 8.x (8, 8.1), 10, 11** (Tested on Windows 11)
- **.NET SDK 9** (or higher)  
  Install via the following command:
  ```powershell
  winget install Microsoft.DotNet.SDK.9
  ```
- **.NET Framework 4.8 Developer Pack**  
  Download from the official .NET website:  
  [Download .NET Framework 4.8 Developer Pack](https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-developer-pack-offline-installer)

## Installation Instructions

### 1. Clone the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/Xelvanta/roblox-multilauncher <your/installation/directory>
cd <your/installation/directory>
```

### 2. Install Dependencies
Ensure that you have the necessary **.NET SDK** and **.NET Framework** installed. If they are missing, follow the installation instructions in the **Prerequisites** section.

### 3. Build the App
To build the app, run the following command in the `MultiBloxy` directory of the project (where the `.csproj` and `.cs` files are located):

```bash
dotnet build
```

This will compile the application and place the output in the `bin\Debug` or `bin\Release` folder, depending on the build configuration.

## Running the App

### 1. Run the App from the Command Line
After building the app, run it using the following command:

```bash
dotnet run
```

Alternatively, navigate to the output directory (`bin\Debug` or `bin\Release`) and run the executable directly:

```bash
cd bin\Debug
MultiBloxy.exe
```

### 2. Access the App via the System Tray
Once the app is running, it will minimize to the **system tray**. You will find an icon for **roblox-multilauncher** there.

- **Right-click** on the icon to access the app's menu and manage accounts.

## License

This project is a **fork** of the original [MultiBloxy](https://github.com/Zgoly/MultiBloxy) and is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

## Troubleshooting

- **Missing .NET SDK or Framework**: Ensure that both the **.NET SDK 9** (or higher) and the **.NET Framework 4.8 Developer Pack** are installed.
- **Build Errors**: If you encounter build errors, verify that your environment meets all prerequisites. You may need to clean and rebuild the project using:
  ```bash
  dotnet clean
  dotnet build
  ```

## Contributing

Contributions are welcome! If you have ideas for new features or optimizations, feel free to fork the repo and submit a pull request.

## Community Support

For support or inquiries, please contact us at [enquiry.information@proton.me](mailto:enquiry.information@proton.me).  
Follow us on GitHub: [https://github.com/Xelvanta](https://github.com/Xelvanta)

---

By **Xelvanta Group Systems**  
For more tools and apps, visit our [official GitHub page](https://github.com/Xelvanta).