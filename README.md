# CSharpFree
NetAcademia ingyenes C# bevezető

## Előkészületek
A tanfolyamon **Windows** operációs rendszeren futó [Visual Studio 2015 Community](https://www.visualstudio.com/vs/community/) fejlesztői keretrendszert fogunk használni.

### Visual Studio 2015 Community telepítése
A tanfolyamon ezt az alkalmazást fogjuk használni. Ingyenesen elérhető önálló fejlesztők, nyílt forráskódú projektek, akadémiai kutatók számára. Továbbá oktatási célokra és kis (max 5 fős) fejlesztőcsapatoknak.

Letölteni az előző linkről vagy [innen lehet](https://www.visualstudio.com/free-developer-offers/). Ehhez a tanfolyamhoz telepíteni az alapértelmezett beállításokkal elég.

Vagy, ha valaki szeret újat kipróbálni, akkor telepítheti [Chocolatey](https://chocolatey.org/) csomagkezelővel is. 

[Telepítés](https://chocolatey.org/install): ehhez indítsunk egy adminisztrátori parancssort ([elevated command prompt](http://www.computerhope.com/jargon/e/elevated.htm)), majd tegyük vágólapra ezt:

**@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"**

ha megvan, a parancssorunkba illesszük be és futtassuk le. 

Ezzel telepítettünk egy csomagkezelőt, innentől kezdve nem kell letölteni és telepíteni kattintgatásokkal az alkalmazásainkat, hanem a csomagkezelőnkre bizhatjuk a dolgot, legalábbis [jelenleg már több, mint 4000 alkalmazás esetében](https://chocolatey.org/packages).

Ha megvagyunk, a Visual Studio Community telepítése [adminisztrátori parancssorból így megy](https://chocolatey.org/packages/VisualStudio2015Community): 

**cinst visualstudio2015community**

Ezzel meg is vagyunk az előkészületekkel, a többit a tanfolyamon folytatjuk!