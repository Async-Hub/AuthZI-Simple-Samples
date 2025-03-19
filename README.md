# Adding a Custom NuGet Source in Visual Studio

To build samples, you need to add a [this NuGet source](https://dev.azure.com/async-hub/AuthZI/_artifacts/feed/Testing/connect) in Visual Studio. Follow the steps below:

1. Open Visual Studio.
2. Go to **Tools** > **Options**.
3. In the **Options** dialog, navigate to **NuGet Package Manager** > **Package Sources**.
4. Click the **+** button to add a new source.
5. Enter the following details:
    - **Name**: AuthZI-Testing (or any name you prefer)
    - **Source**: `https://pkgs.dev.azure.com/async-hub/AuthZI/_packaging/Testing/nuget/v3/index.json`
6. Click **Update** to save the changes.
7. Ensure the new source is checked/enabled in the list.

You can now restore and build the project using the custom NuGet source.
