<h1>Background</h1>
<h2>Game Engine</h2>
Bugsnax uses the <a href="https://irrlicht.sourceforge.io/">Irrlicht Engine</a>, an "open source realtime 3D engine written in C++". You can find out more about this engine in the link before. 

<h2>Common File Types</h2>
<b>.XML [Text]</b> - XML files contain the XML language. This is a markup language without predefined tags. Whilst commonly used for data storage, it functions similarly to a script within the engine. Examples of this can be seen below.
<br><b>.IRR [Text]</b> - IRR files contain XML and function the same way as stated above.
<br><b>.OBJ [Model]</b> - Wavefront .OBJ is a model filetype. These models **do not support animations or <a href=https://docs.blender.org/manual/en/latest/animation/armatures/introduction.html>armatures</a> (skeletons)**. For this reason, these models are often used for props, accessories, and terrain in Bugsnax as they **only contain <a href=https://docs.blender.org/manual/en/latest/modeling/meshes/index.html>mesh</a> data**.
<br><b>.X [Model]</b> - DirectX .X is a model filetype. These models **do support animations and armatures** and are therefore used for animating both Grumpus and Bugsnak NPCs. 
<br><b>.DAE [Model]</b> - Collada .DAE files are an XML-based model format. These files are used infrequently throughout Bugsnax for models such as leaves.
<br><b>.DDS [Texture]</b> - DirectDraw Surface .DDS files are a <a href=https://docs.unity3d.com/Manual/Textures.html>texture</a> filetype used to texture models in Bugsnax. They support <a href=https://docs.microsoft.com/en-us/windows/win32/direct3d9/texture-filtering-with-mipmaps>mipmaps</a> which allow the texture to change quality the closer/further you are from it to optimise rendering.
<br><b>.PNG [Texture]</b> - .PNG files are a very common image format that _can_ be used to texture any model in the game and are used to texture the UI within the game. These do not support mipmaps.
<br><b>.BANK [Audio]</b> - .BANK files are the compressed and encrypted files containing all audio used within the game. These .BANK files are used by <a href=https://www.fmod.com/studio>FMOD</a>, the sound engine within the game

<h2>Filesystem Structure</h2>
<br><b>\Bugsnax\</b> - This is the root folder. This is the where the executable file for Bugsnax can be found. This is also the directory that .ZIP files for mods are/should be placed.
<br><b>\Bugsnax\Content\</b> - This is the folder that contains all of the content for the game. You are not likely to need to put content in this folder directly.
<br><b>\Bugsnax\Content\Audio\</b> - This folder contains within its directories the different .BANK files for Bugsnax.
<br><b>\Bugsnax\Content\Config\</b> - This folder contains the configuration files for the game, including those for character profiles, levels, challenges, definitions (see below), sounds, etc.
<br><b>\Bugsnax\Content\Defintions\</b> - This folder contains Definition XML files that define different bits of informaion about all aspects of the game. It is not where most of the scripting exists, but often defines where those scripting files are, what Bugsnax and NPCs are in the game, and high-level configurations for the different apsects of the game. 
<br><b>\Bugsnax\Content\Font\</b> - This folder contains the fonts used in the game.
<br><b>\Bugsnax\Content\FX\</b> - This folder contains the textures of the different FX used in the game (e.g. water, snow)
<br><b>\Bugsnax\Content\Input\</b> - This defines the input for the input method (e.g. keyboard and mouse, controller) that the player is using in the game
<br><b>\Bugsnax\Content\Language\</b> - This folder contains the translations/subtitles for the game
<br><b>\Bugsnax\Content\Levels\</b> - This folder is the folder containing the bulk of the scripting for the game, almost entirely through the .IRR files. These .IRR files outline the scripting for the Grumpuses, Levels, Bugsnax, and other key aspects of the game. Some examples of these can be seen at the bottom of the document.
<br><b>\Bugsnax\Content\Models\</b> - This folder contains the all models and most textures (excluding FX and UI) used in the game, as well as some XML files that outline details about the Bugsnax and Grumpuses. 
<br><b>\Bugsnax\Content\NavMesh\</b> - This folder contains XML files containing compressed data about the <a href=https://en.wikipedia.org/wiki/Navigation_mesh>NavMeshes</a>. NavMeshes are navigation meshes that outline paths for NPCs, saying where they can go, where they can't go, and the paths they should take around a level. It is not yet known if there is a way to edit these NavMesh files.
<br><b>\Bugsnax\Content\Particles\</b> - This folder contains PNGs for the particles used throughout the game, and some XML files for these particles that store data about them.
<br><b>\Bugsnax\Content\Screens\</b> - This folder contains all of the images and graphics for the UI throughout the game.
<br><b>\Bugsnax\Content\Shaders\</b> - This folder contains the files of the many <a href=https://en.wikipedia.org/wiki/Shader>shaders</a> used throughout the game. Shaders apply effects to models within the game (e.g. a shader is what makes Grumpuses look furry).

<h2>Debug Menu</h2>
Placeholder

<h1>Installing Mods</h1>
<h2>Using Vortex</h2>
Placeholder

<h2>Manual Installation</h2>
Placeholder


<h1>Compiling and Uploading</h1>
Placeholder


<h1>Creating Mods</h1>
<h2>Modding Tools and Resources</h2>
<h3Tools</h3>
Placeholder

<h3>Tips and Best Practice</h3>
Placeholder

<h2>Changing Textures</h2>
Placeholder

<h2>Adding/Replacing Bugsnax</h2>
Placeholder

<h2>Adding/Changing Maps</h2>
Placeholder

<h2>Adding/Changing Props and Models</h2>
Placeholder

<h2>Adding/Changing Grumpus Accessories</h2>
Placeholder

<h2>Changing UI and Graphics</h2>
Placeholder

<h2>Adding/Changing Sounds</h2>
Placeholder


<h1>XML Code Library</h1>
Placeholder


<h1>XML Examples</h1>
<h2>Textures</h2>
Placeholder

<h2>Bugsnax</h2>
Placeholder

<h2>Maps</h2>
Placeholder

<h2>Props and Models</h2>
Placeholder

<h2>UI and Graphics</h2>
Placeholder

<h2>Sounds</h2>
Placeholder
