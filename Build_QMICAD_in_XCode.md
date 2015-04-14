#CMake
1. Change in `CMakeLists.txt`
   - [ ] `COMMAND mv        ${QMICAD_DIST_DIR}/lib/qmicad${CMAKE_SHARED_LIBRARY_SUFFIX}  ${QMICAD_DIST_DIR}/qmicad`
   - [ ] `COMMAND cp    -rp ${QMICAD_DIST_DIR}/lib/libqmicad${CMAKE_SHARED_LIBRARY_SUFFIX} ${QMICAD_DIST_DIR}/qmicad`
   - [x] `COMMAND mv        ${QMICAD_DIST_DIR}/lib/Debug/qmicad${CMAKE_SHARED_LIBRARY_SUFFIX}  ${QMICAD_DIST_DIR}/qmicad`
   - [x] `COMMAND cp    -rp ${QMICAD_DIST_DIR}/lib/Debug/libqmicad${CMAKE_SHARED_LIBRARY_SUFFIX} ${QMICAD_DIST_DIR}/qmicad`
  
2. Use cmake to generate `.xcodeproject` for QMICAD.
3. show the build directory as `CHECKEDOUT_DIRECTORY/obj/`
4. `Configure`
5. `Generate`
6. It will generate `CHECKEDOUT_DIRECTORY/obj/PROJECT_NAME.xcodeproject`

#XCode
1. Open `CHECKEDOUT_DIRECTORY/obj/PROJECT_NAME.xcodeproject`
2. Build Project
4. Add `CHECKEDOUT_DIRECTORY` manually in the project by `Add files`
