## Zymplectic :: Cutting edge numerical integration done easy, fast, accurate and beautiful
- Numerical integration platform intended for scientific and educational purposes
- Highly accurate and efficient engine for simulating dynamical systems using the world's largest selection of symplectic integrators
- Non-intrusive, fully offline, requires no installation and does not modify files outside its directory
- Works straight out of the box (7z zip file) with no dependencies and requires no setup
- Includes more than 80 example dynamical systems to be compiled and run with a single click in a practical user interface

`Only win64 supported at this time. Integrator coefficients and Hamiltonian systems can otherwise be extracted from text files`

### How to use:
- Download Zymplectic (bundled with clang or gcc) and extract files to folder
- Run Zymplectic.exe
- Start any of the included example c++ scripts or write your own Hamiltonian systems using provided templates

### For information about the project, please refer to
- Project website https://zymplectic.com/
- Reddit https://www.reddit.com/r/Zymplectic/
- YouTube https://www.youtube.com/c/Zymplectic

### Release history:

- v.0.12.0 (2024.09.06) - added periodic time, optimized sphere and other graphics, new example script
- v.0.11.3 (2024.07.05) - added high order integrators, example scripts, colormaps, integrator export
- v.0.11.2 (2024.05.20) - added draw.rods, fixed rod/spring orientation issues, new example script
- v.0.11.1 (2024.02.03) - new sequential colormaps, new example scripts, lighting fix for some primitives
- v.0.11.0 (2023.12.15) - added draw.box, added up(x) header, fixed reset issues, new example scripts 
- v.0.10.4 (2023.07.29) - fixed several benchmark issues including crash that would occur in abs benchmark
- v.0.10.3 (2023.07.20) - added "quick benchmark", integrators and example script. Abs benchmark fixed
- v.0.10.2 (2023.05.25) - optimized most graphical shapes, draw.spring (2D) removed, new example scripts
- v.0.10.1 (2023.05.09) - fixed track canvas issue, fixed flicker for draw.surf, new example script
- v.0.10.0 (2023.04.25) - full 3D interfacing, GUI improved, numerous fixes e.g. start stutter, new scripts
- v.0.9.6 (2023.04.07) - fixed 3D cursor position display, added speed toggle, new example scripts
- v.0.9.5 (2023.03.30) - added 3D mouseX/Y detection, several graphical fixes, new example script
- v.0.9.4 (2023.02.18) - several fixes, e.g. 3D track interface, improved Poincaré scripts, new scripts
- v.0.9.3 (2023.01.25) - track overhaul, updated licenses, UI tweaks and fixes, new example script, QOL 
- v.0.9.2 (2023.01.02) - fixed crash involving draw.surf, added draw.track_get, several scripts improved
- v.0.9.1 (2022.11.30) - minor fixes, 3D cam ctrl/shift speeds, clang version update, new example scripts
- v.0.9.0 (2022.10.08) - paused start, numerous fixes and UI improvements, example scripts added/updated
- v.0.8.7 (2022.08.21) - added draw.surfopt, optimized draw.surf, fixed cone normals, new example script
- v.0.8.6 (2022.08.05) - fixed scaled draw.surf normals, initial camera issue fixed, new example script
- v.0.8.5 (2022.07.16) - numerous small fixes, added draw.rgb(v) and simplified scripts, new example script  
- v.0.8.4 (2022.06.30) - added 5 sequential colormaps, fixed track resolution scaling, new example script
- v.0.8.3 (2022.05.24) - graphics recoded and optimized, added blend trails and fog clipping, fixed script
- v.0.8.2 (2022.05.05) - added multisample anti-aliasing, added draw.cone, fixed draw.cam affect and reset
- v.0.8.1 (2022.04.20) - fixed crash, fixed/improved several scripts, freeglut update, new example script
- v.0.8.0 (2022.04.08) - improved graphing fidelity, +6 RKN methods, crash fixes, new example scripts, QOL
- v.0.7.7 (2022.01.24) - fixed camera, loading and flag issues when changing script, new example script
- v.0.7.6 (2021.12.23) - added draw.spheres, in-script compiler flags, optimizations and new example script
- v.0.7.5 (2021.12.07) - fixed ScreenX update, fixed zero-parameters script load, new example script
- v.0.7.4 (2021.11.16) - fixed native surf, draw.surf now works for 2D display, added draw.depth
- v.0.7.3 (2021.11.01) - graphics timer overhaul fixing stutter and fps cap, fixed special case "@" issue
- v.0.7.2 (2021.10.16) - fixed trail crash, VSync stutter fixed, fixed cdir path issue, new example script
- v.0.7.1 (2021.10.09) - added spring function argument, optimized N-pendulum, added script
- v.0.7.0 (2021.09.24) - timer system overhaul, draw.trailRGB added, crash fixes, new example script
- v.0.6.5 (2021.08.27) - multi-trail supported, axes/UI changes and fixes, added, new example script
- v.0.6.4 (2021.08.11) - added -D_DIM#, added example script, improved UI, fixed surf-rescale hanging
- v.0.6.3 (2021.07.25) - fixed two 1080p+ memory issues, updated and added example scripts
- v.0.6.2 (2021.07.14) - added pause (spacebar), various initialization fixes, added example scripts
- v.0.6.1 (2021.07.08) - 4K resolution is now fully support, fixed 3D text, clang version update
- v.0.6.0 (2021.06.29) - added 3D text, texts now rely on \0, attempt fix for shared drives, new examples
- v.0.5.2 (2021.05.25) - fixed potential trail crash, added UI scaling for 1080p, added example scripts
- v.0.5.1 (2021.05.05) - fixed crash in 3D mode, added new example script and draw.linesize
- v.0.5.0 (2021.04.03) - 3D surface added, @ fix, track_add renamed to track, improved some example scripts
- v.0.4.4 (2021.03.08) - fixed "@" comment issue, tweaked compilation process, added new example files
- v.0.4.3 (2021.02.10) - "@" now functions as a macro power operator (experimental). Example codes altered
- v.0.4.2 (2021.02.05) - fixed status layout in 3D mode. Added new example codes
- v.0.4.1 (2021.01.19) - improved 3D models and enabled culling. Licenses updated (more permissive)
- v.0.4.0 (2020.11.27) - added trail function, improved UI and natives. New naming conventions
- v.0.3.2 (2020.10.01) - added new natives. improved surface of section scripts
- v.0.3.1 (2020.09.09) - added new events and fixed trajectory tracking issues. GCC version update
- v.0.3.0 (2020.08.20) - 3D graphical display is now supported. Several example systems added
- v.0.2.6 (2020.05.01) - energy surface is now compatible for separable systems. Fixed scripted resolution
- v.0.2.5 (2020.03.02) - surface of section examples. UI updates. New native functions (e.g. draw.spring)
- v.0.2.4 (2020.02.20) - reduced latency for non-separable systems. Fixed rare crash when stopping simulation
- v.0.2.3 (2020.02.08) - RGB and RWB colormap. Scripts can initialize by commandline. Code cleanup
- v.0.2.2 (2020.01.23) - added interactive features (experimental). Corrected various errors in scripts
- v.0.2.1 (2020.01.10) - updated clang, modified UI text
- v.0.2.0 (2020.01.07) - new naming conventions and various improvements in performance and interface
- v.0.1.5 (2019.11.17) - memory fix, added integrators and naming convention changes
- v.0.1.4 (2019.11.11) - codes are now fully compatible with c++
- v.0.1.3 (2019.10.31) - clear gradient toggle and new naming convention in integrators.zym
- v.0.1.2 (2019.10.28) - implemented new composite algorithms. Many fixes and new naming conventions
- v.0.1.1 (2019.10.09) - implemented custom track features
- v.0.1.0 (2019.10.02) - first released
