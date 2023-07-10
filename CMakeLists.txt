# Aerosols_GridComp/CMakeLists.txt

add_library(Aerosols_GridComp STATIC
	Aerosols_GridCompMod.F90
)
target_link_libraries(Aerosols_GridComp PUBLIC GeosCore)
