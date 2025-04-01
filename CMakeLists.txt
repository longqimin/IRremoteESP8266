# CMakeFiles.txt inside "IRemoteESP8266" folder
cmake_minimum_required(VERSION 3.5)


set(srcs
src/ir_Airton.cpp
src/ir_Airwell.cpp
src/ir_Aiwa.cpp
src/ir_Amcor.cpp
src/ir_Argo.cpp
src/ir_Arris.cpp
src/ir_Bosch.cpp
src/ir_Carrier.cpp
src/ir_ClimaButler.cpp
src/ir_Coolix.cpp
src/ir_Corona.cpp
src/ir_Daikin.cpp
src/ir_Delonghi.cpp
src/ir_Denon.cpp
src/ir_Dish.cpp
src/ir_Doshisha.cpp
src/ir_Ecoclim.cpp
src/ir_Electra.cpp
src/ir_EliteScreens.cpp
src/ir_Epson.cpp
src/ir_Fujitsu.cpp
src/ir_GICable.cpp
src/ir_GlobalCache.cpp
src/ir_Goodweather.cpp
src/ir_Gorenje.cpp
src/ir_Gree.cpp
src/ir_Haier.cpp
src/ir_Hitachi.cpp
src/ir_Inax.cpp
src/ir_JVC.cpp
src/ir_Kelon.cpp
src/ir_Kelvinator.cpp
src/ir_Lasertag.cpp
src/ir_Lego.cpp
src/ir_LG.cpp
src/ir_Lutron.cpp
src/ir_Magiquest.cpp
src/ir_Metz.cpp
src/ir_Midea.cpp
src/ir_MilesTag2.cpp
src/ir_Mirage.cpp
src/ir_Mitsubishi.cpp
src/ir_MitsubishiHeavy.cpp
src/ir_Multibrackets.cpp
src/ir_MWM.cpp
src/ir_NEC.cpp
src/ir_Neoclima.cpp
src/ir_Nikai.cpp
src/ir_Panasonic.cpp
src/ir_Pioneer.cpp
src/ir_Pronto.cpp
src/ir_RC5_RC6.cpp
src/ir_RCMM.cpp
src/ir_Rhoss.cpp
src/ir_Samsung.cpp
src/ir_Sanyo.cpp
src/ir_Sherwood.cpp
src/ir_Sony.cpp
src/ir_Symphony.cpp
src/ir_Tcl.cpp
src/ir_Technibel.cpp
src/ir_Teco.cpp
src/ir_Teknopoint.cpp
src/ir_Toshiba.cpp
src/ir_Toto.cpp
src/ir_Transcold.cpp
src/ir_Trotec.cpp
src/ir_Truma.cpp
src/ir_Vestel.cpp
src/ir_Voltas.cpp
src/ir_Whirlpool.cpp
src/ir_Whynter.cpp
src/ir_Wowwee.cpp
src/ir_Xmp.cpp
src/ir_York.cpp
src/ir_Zepeal.cpp
src/IRac.cpp
src/IRtimer.cpp
src/IRrecv.cpp
src/IRsend.cpp
src/IRtext.cpp
src/IRutils.cpp

)

set(includedirs
src
src/locale
)



set(srcs ${srcs})

idf_component_register(INCLUDE_DIRS ${includedirs} SRCS ${srcs} REQUIRES "arduino")

target_compile_definitions(${COMPONENT_LIB} PRIVATE -D ESP32 -D ARDUINO)


# idf_component_register(SRCS 
#                     INCLUDE_DIRS "src/."
#                     REQUIRES "arduino" # Library requires Arduino
#                     )

project(IRemoteESP8266)