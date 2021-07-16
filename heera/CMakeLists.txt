cmake_minimum_required(VERSION 3.19)
project(heera-wallpapers-main)

set(BACKGROUNDS
	heera-01.jpg
	heera-02.jpg
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/heera/)
install(FILES ATTRIBUTION DESTINATION /usr/share/licenses/heera-wallpapers/HEERA_BACKGROUNDS_ATTRIBUTION)
