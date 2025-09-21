### Zymplectic :: Cutting edge numerical integration done easy, fast, accurate and beautiful
- Zymplectic is an accurate and fast numerical integration platform specialized for Hamiltonian physics and intended for scientific and educational purposes
- Zymplectic is NOT a sandbox physics tool and is NOT intended for parallel computing tasks 

### Core features:
- Built-in explict symplectic integration algorithms for (non)separable and (non)autonomous Hamiltonian systems
- Largest public collection of symplectic integration coefficients (source file integrators.zym)
- Comprehensive library of Hamiltonian dynamical systems (about 100 examples written in c-style c++ code)
- Non-intrusive, fully offline, requires no installation and does not modify files outside its directory
- Works straight out of the box (7z zip file) with no dependencies and requires no setup
- Practical GUI to compile and simulate dynamical systems by a single click
- Graphics by simple and convenient functions based on OpenGL
- Performance and flexibility of MinGW-w64 compilers

`Only win64 supported at this time`

### How to use:
- Download Zymplectic (bundled with clang or gcc) and extract files to a folder
- Run Zymplectic.exe
- Start any of the included example c++ scripts or write your own Hamiltonian systems using provided templates

### For information about the project, please refer to:
- Project website https://zymplectic.com/
- Reddit https://www.reddit.com/r/Zymplectic/
- YouTube https://www.youtube.com/c/Zymplectic

### Release history:
v.0.12.7 (2025.09.22) - draw.trackb added, x track fix, script improvements, new example scripts<br/>
<details>
<summary>Older releases</summary>
v.0.12.6 (2025.07.27) - draw.rods can loop, @ fix, improved documentation, new example scripts<br/>
v.0.12.5 (2025.05.23) - draw.sphere, draw.polygon optimized, new integrators, new example script, QOL<br/>
v.0.12.4 (2025.04.11) - added export/import for track, minor gui fixes, new example scripts<br/>
v.0.12.3 (2025.01.14) - native graphics and Z.OnDrawAdd supports multiple trails, new example scripts<br/>
v.0.12.2 (2024.11.22) - digits increased for several integrators, new compositions in integrators.zym<br/>
v.0.12.1 (2024.10.14) - optimized rod/hrod graphics, some scripts optimized, new example script<br/>
v.0.12.0 (2024.09.06) - added periodic time, optimized sphere and other graphics, new example script<br/>
v.0.11.3 (2024.07.05) - added high order integrators, example scripts, colormaps, integrator export<br/>
v.0.11.2 (2024.05.20) - added draw.rods, fixed rod/spring orientation issues, new example script<br/>
v.0.11.1 (2024.02.03) - new sequential colormaps, new example scripts, lighting fix for some primitives<br/>
v.0.11.0 (2023.12.15) - added draw.box, added up(x) header, fixed reset issues, new example scripts<br/>
v.0.10.4 (2023.07.29) - fixed several benchmark issues including crash that would occur in abs benchmark<br/>
v.0.10.3 (2023.07.20) - added "quick benchmark", integrators and example script. Abs benchmark fixed<br/>
v.0.10.2 (2023.05.25) - optimized most graphical shapes, draw.spring (2D) removed, new example scripts<br/>
v.0.10.1 (2023.05.09) - fixed track canvas issue, fixed flicker for draw.surf, new example script<br/>
v.0.10.0 (2023.04.25) - full 3D interfacing, GUI improved, numerous fixes e.g. start stutter, new scripts<br/>
v.0.9.6 (2023.04.07) - fixed 3D cursor position display, added speed toggle, new example scripts<br/>
v.0.9.5 (2023.03.30) - added 3D mouseX/Y detection, several graphical fixes, new example script<br/>
v.0.9.4 (2023.02.18) - several fixes, e.g. 3D track interface, improved Poincaré scripts, new scripts<br/>
v.0.9.3 (2023.01.25) - track overhaul, updated licenses, UI tweaks and fixes, new example script, QOL<br/>
v.0.9.2 (2023.01.02) - fixed crash involving draw.surf, added draw.track_get, several scripts improved<br/>
v.0.9.1 (2022.11.30) - minor fixes, 3D cam ctrl/shift speeds, clang version update, new example scripts<br/>
v.0.9.0 (2022.10.08) - paused start, numerous fixes and UI improvements, example scripts added/updated<br/>
v.0.8.7 (2022.08.21) - added draw.surfopt, optimized draw.surf, fixed cone normals, new example script<br/>
v.0.8.6 (2022.08.05) - fixed scaled draw.surf normals, initial camera issue fixed, new example script<br/>
v.0.8.5 (2022.07.16) - numerous small fixes, added draw.rgb(v) and simplified scripts, new example script<br/> 
v.0.8.4 (2022.06.30) - added 5 sequential colormaps, fixed track resolution scaling, new example script<br/>
v.0.8.3 (2022.05.24) - graphics recoded and optimized, added blend trails and fog clipping, fixed script<br/>
v.0.8.2 (2022.05.05) - added multisample anti-aliasing, added draw.cone, fixed draw.cam affect and reset<br/>
v.0.8.1 (2022.04.20) - fixed crash, fixed/improved several scripts, freeglut update, new example script<br/>
v.0.8.0 (2022.04.08) - improved graphing fidelity, +6 RKN methods, crash fixes, new example scripts, QOL<br/>
v.0.7.7 (2022.01.24) - fixed camera, loading and flag issues when changing script, new example script<br/>
v.0.7.6 (2021.12.23) - added draw.spheres, in-script compiler flags, optimizations and new example script<br/>
v.0.7.5 (2021.12.07) - fixed ScreenX update, fixed zero-parameters script load, new example script<br/>
v.0.7.4 (2021.11.16) - fixed native surf, draw.surf now works for 2D display, added draw.depth<br/>
v.0.7.3 (2021.11.01) - graphics timer overhaul fixing stutter and fps cap, fixed special case "@" issue<br/>
v.0.7.2 (2021.10.16) - fixed trail crash, VSync stutter fixed, fixed cdir path issue, new example script<br/>
v.0.7.1 (2021.10.09) - added spring function argument, optimized N-pendulum, added script<br/>
v.0.7.0 (2021.09.24) - timer system overhaul, draw.trailRGB added, crash fixes, new example script<br/>
v.0.6.5 (2021.08.27) - multi-trail supported, axes/UI changes and fixes, added, new example script<br/>
v.0.6.4 (2021.08.11) - added -D_DIM#, added example script, improved UI, fixed surf-rescale hanging<br/>
v.0.6.3 (2021.07.25) - fixed two 1080p+ memory issues, updated and added example scripts<br/>
v.0.6.2 (2021.07.14) - added pause (spacebar), various initialization fixes, added example scripts<br/>
v.0.6.1 (2021.07.08) - 4K resolution is now fully support, fixed 3D text, clang version update<br/>
v.0.6.0 (2021.06.29) - added 3D text, texts now rely on \0, attempt fix for shared drives, new examples<br/>
v.0.5.2 (2021.05.25) - fixed potential trail crash, added UI scaling for 1080p, added example scripts<br/>
v.0.5.1 (2021.05.05) - fixed crash in 3D mode, added new example script and draw.linesize<br/>
v.0.5.0 (2021.04.03) - 3D surface added, @ fix, track_add renamed to track, improved some example scripts<br/>
v.0.4.4 (2021.03.08) - fixed "@" comment issue, tweaked compilation process, added new example files<br/>
v.0.4.3 (2021.02.10) - "@" now functions as a macro power operator (experimental). Example codes altered<br/>
v.0.4.2 (2021.02.05) - fixed status layout in 3D mode. Added new example codes<br/>
v.0.4.1 (2021.01.19) - improved 3D models and enabled culling. Licenses updated (more permissive)<br/>
v.0.4.0 (2020.11.27) - added trail function, improved UI and natives. New naming conventions<br/>
v.0.3.2 (2020.10.01) - added new natives. improved surface of section scripts<br/>
v.0.3.1 (2020.09.09) - added new events and fixed trajectory tracking issues. GCC version update<br/>
v.0.3.0 (2020.08.20) - 3D graphical display is now supported. Several example systems added<br/>
v.0.2.6 (2020.05.01) - energy surface is now compatible for separable systems. Fixed scripted resolution<br/>
v.0.2.5 (2020.03.02) - surface of section examples. UI updates. New native functions (e.g. draw.spring)<br/>
v.0.2.4 (2020.02.20) - reduced latency for non-separable systems. Fixed rare crash when stopping simulation<br/>
v.0.2.3 (2020.02.08) - RGB and RWB colormap. Scripts can initialize by commandline. Code cleanup<br/>
v.0.2.2 (2020.01.23) - added interactive features (experimental). Corrected various errors in scripts<br/>
v.0.2.1 (2020.01.10) - updated clang, modified UI text<br/>
v.0.2.0 (2020.01.07) - new naming conventions and various improvements in performance and interface<br/>
v.0.1.5 (2019.11.17) - memory fix, added integrators and naming convention changes<br/>
v.0.1.4 (2019.11.11) - codes are now fully compatible with c++<br/>
v.0.1.3 (2019.10.31) - clear gradient toggle and new naming convention in integrators.zym<br/>
v.0.1.2 (2019.10.28) - implemented new composite algorithms. Many fixes and new naming conventions<br/>
v.0.1.1 (2019.10.09) - implemented custom track features<br/>
v.0.1.0 (2019.10.02) - first released<br/>
</details>
