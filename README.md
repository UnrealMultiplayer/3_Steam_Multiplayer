# Unreal Multiplayer Course - Section 3 - Steam Multiplayer

Connect your games P2P over steam. This game introduces Unreal's Online Sub-System (OSS) and shows you how to use it with the Steamworks API. By the end of the section, you will be able to connect player through Steam lobbies.

### 0 Introduction to Steam Multiplayer ###

+ We overview the section topic.

### 1 Getting The Steamworks SDK ###

+ Introducing Steamworks.
+ Downloading the Steamworks SDK.
+ Steamworks and the Online Sub-System.

### 2 Building SpaceWar In Visual Studio ###

+ Introducing the Steamworks example project.
+ Updating the project.
+ Downloading & installing DirectX SDK.
+ Fixing the build errors.

### 3 Building SpaceWar In Xcode ###

+ Introducing the Steamworks example project.
+ Applying recommended settings.
+ Running with Steam.

### 4 Testing Steam Lobbies ###

+ Finding a testing partner.
+ Testing servers.
+ Testing lobbies.

### 5 The Online Sub-System ###

+ Importing PuzzlePlatforms.
+ Capabilities of Online Sub-Systems.
+ Including the OSS module.
+ Getting a pointer to the sub-system.

### 6 NULL Sub-System For Testing ###

+ Role of the NULL sub-system.
+ Configuring the NULL service.
+ Printing the current service name.

### 7 Memory Management In C++ ###

+ Stack vs Heap.
+ Manual memory management.
+ Reference counting with `TSharedPtr`.
+ Garbage Collection of UObjects.

### 8 Creating Online Sessions ###

+ Creating a session.
+ Asynchronous operations and delegates.
+ Creating a session on host.

### 9 Destroying Online Sessions ###

+ Asynchronous destruction.
+ Checking if a session exists.
+ Destroy the session if we need to.

### 10 Finding Online Sessions ###

+ `FindSessions` and `TShareRef`.
+ Handling `OnFindSessionsCompleteDelegates`.

### 11 Query Parameters & Session Settings ###

+ Configuring Session Settings.
+ Adding query parameters.
+ Iterating over a `TArray`

### 12 Lists Of Widgets With ScrollBox ###

+ Introduction to the `ScrollBox`.
+ Creating a row widget.
+ Add rows in C++.

### 13 Populating The Server List ###

+ Expose the text property.
+ Setting a server list from GameInstance.
+ Clearing the previous list.
+ Requesting a refresh.