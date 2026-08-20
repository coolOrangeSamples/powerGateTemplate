[Menu](../README.md) [Home](./home.md)
## Technology: C# SDK

_If we get a .Net DLL for the ERP API, then we have prepared an interface of what we required._

Follow these steps to create your implementation of the interface:
1. Create a new solution in Visual Studio, the new project should have the following settings:
   1. Output Type: `Class Library`
   1. Target `.Net framework: 4.8` or higher
   1. Platform Target: `Any CPU`
1. Reference the assembly powerGateServer.SDK:
   1. Download and install the latest powerGateServer from the [powerGate download page](https://www.coolorange.com/powergate-download-page)
   1. Reference `powerGateServer.SDK.dll` from the installation directory `C:\Program Files\coolOrange\powerGateServer\`
1. Copy the interface and required types:
   1. [Interfaces](https://github.com/coolOrangeSamples/powerGateTemplate/blob/0dafc22b0be3d243376245856155fed163bd7949/Files/powerGateServerPlugin/DemoERPPlugin/ErpSystem.cs)
   1. [Metadata](https://github.com/coolOrangeSamples/powerGateTemplate/blob/0dafc22b0be3d243376245856155fed163bd7949/Files/powerGateServerPlugin/DemoERPPlugin/ItemsService.cs#L9-L21)
1. Create your implementation of `IErpManager`
1. **Very important:** Changes to the interface should be avoided, but if necessary, propose a new interface to coolOrange in order to approve it.
