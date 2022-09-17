# Unity Project Layout

This folder structure is the industry standard for all projects.

```
-- Assets 
|
---- <PROJECT NAME> = This is replaced with the name of your project.
|   | 
|   ---- <Art>
|   |   |
|   |   ---- <Animation> = Any animation related assets, can be clips or controllers 
|   |   ---- <Geometry> = Any models made for the game
|   |   ---- <Materials> = Any materials that are being used
|   |   ---- <Shaders> = Any shaders made for the game
|   |   ---- <Textures> = Any textures made for the game
|   |   ---- <UI> = Any UI sprites that get made for the game
|   ---- <Audio>
|   |   |
|   |   ---- <BGM> = Any background music files 
|   |   ---- <SFX> = Any sound effect files
|   |   ---- <Ambient> = Any ambient sound files
|   |   ---- <Voice Overs> = Any voice over clips that may be used
|   |
|   ---- <Prefabs> = Any prefabs needed for the game
|   |   ---- <Characters> = Any character related prefabs, both NPC and player
|   |   ---- <Environment> = Any environment prefabs
|   |   ---- <UI> = Any UI element prefabs
|   |   ---- <Other> = Any prefabs that don't fit into other categories
|   |
|   ---- <Scenes>
|   |   |
|   |   ---- <Production> = The scenes that will be used in actual builds
|   |   ---- <Testing> = The scenes that are being used to test individual parts of the game. Both art and prog related
|   |
|   ---- <Scripts>
|   |   | 
|   |   ---- <Player> = Any scripts related to the player
|   |   ---- <Managers> = Any global managers for the game
|   |   ---- <UI> = Any UI components
|   |   ---- <ETC> = Add more folders as appropriate for game components
|   |
---- <Dependencies>
|   |
|   ---- <Asset Store Asset #1>
|   ---- <Asset Store Asset #2>
|   ---- <Asset Store Asset #3>
---- <Plugins>

```