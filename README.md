Scope
This document covers the configuration of the NSDB Control Center, integration of necessary libraries into your .NET C# application, and coding functions required for database operations.

----------------
Prerequisites
----------------

Software Requirements
- .NET Framework
- NSDB Control Center
- nsdb.dll
- nsdata_lib.dll

Hardware Requirements
- A server to host the NSDB Control Center
- Client machines with network access to the server

----------------
Configuration
----------------

Preparing the Environment
- Install the NSDB Control Center: Ensure that the NSDB Control Center is installed and configured on your server. This will provide the user interface (UI) for managing the database.
- Add Necessary DLLs: Place the nsdb.dll and nsdata_lib.dll files into the bin folder of your application.

Importing DLLs
In your .NET C# project, import the nsdb.dll to enable the use of NSDB functions.
