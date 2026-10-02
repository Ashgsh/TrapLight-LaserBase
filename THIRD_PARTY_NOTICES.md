# Third-party libraries

TrapLight LaserBase uses unmodified Qt 6.11.2 libraries through dynamic linking.
Qt Core, GUI, Widgets, Network, SQL, PrintSupport and SVG are licensed under LGPL-3.0; their bundled third-party components retain their respective licenses.
License and copyright texts are included in licenses/. Complete upstream Qt Base, SVG and Translations source archives are available beside this application in the v0.7.0 GitHub release:
https://github.com/Ashgsh/TrapLight-LaserBase/releases/tag/v0.7.0
Upstream: https://download.qt.io/official_releases/qt/6.11/6.11.2/submodules/

You may replace the dynamically linked Qt DLLs and plugins with compatible builds, including modified builds. Close the application, preserve a backup and replace the relevant DLLs/plugins in its portable folder; run LaserBase.exe again. No application signature check prevents replacing those libraries. Reverse engineering for debugging modifications to these libraries is permitted. These rights are not restricted by the application's proprietary status.

GCC 13.1 runtime libraries are distributed under GPL with the GCC Runtime Library Exception. MinGW-w64 and winpthreads license texts are included separately. Their sources are available from https://gcc.gnu.org/releases.html and https://www.mingw-w64.org/.
These dependency sources are not the source code of TrapLight LaserBase.
