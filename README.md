# dkserve

An HTTP server built for the [DevKit](https://github.com/u1teriormotives/DevKit) framework in C#

How to use:

- Build from source (`git clone https://github.com/u1teriormotives/dkserve.git`, `dotnet publish -c Release -r your-architecture --self-contained true /p:PublishSingleFile=true`; yes, there will be a better way to build/publish later on, but the long command is necessary – make sure you *change* that which says `your-architecture` to your architecture (e.g., win-x64, osx-arm64, etc.))
- Add the resulting file (found as bin/Release/net10.0/your-architecture/publish/dkserve) to your `$PATH`
- Run via whatever you named the binary

The server runs off of a `DKRoute.json` file ([example](https://github.com/u1teriormotives/DevKit/blob/main/Routing/DKRoute.json))
in your current directory. See the main repository for more information.
