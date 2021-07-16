cmake_minimum_required(VERSION 3.19)
project(heera-wallpapers-community)

set(BACKGROUNDS
      beach.jpg
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/heera/)
install(FILES ATTRIBUTION DESTINATION /usr/share/licenses/heera-wallpapers-community/ATTRIBUTION)
