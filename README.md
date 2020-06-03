# DiabloBlazor <img src="https://devblogs.microsoft.com/aspnet/wp-content/uploads/sites/16/2019/04/BrandBlazor_nohalo_1000x.png" width="50" height="50" />

Based on the excellent [DiabloWeb](https://github.com/d07RiV/diabloweb) which, in turn, is based on the likewise excellent [Devilution](https://github.com/diasurgical/devilution).

As the name implies, DiabloBlazor swaps out React used in DiabloWeb for Blazor, making it a double WebAssembly app: a WebAssembly (C#) OS installable, offline capable PWA hosting a WebAssembly (C++) game. It also leverages TypeScript instead of JavaScript (except for the JavaScript glue code generated by Emscripten).

You can go to [DiabloBlazor on GitHub Pages](https://n-stefan.github.io/diabloblazor) to try it out. The PWA offline capability is disabled on GitHub Pages because initial caching takes too long. It is however enabled when deployed locally.

The development server can be found here: [DiabloBlazorServer](https://github.com/n-stefan/diabloblazorserver).

IDE: latest Visual Studio Community 2019 Preview with the Web Compiler extension installed.
