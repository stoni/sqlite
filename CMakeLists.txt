cmake_minimum_required (VERSION 2.6)
project (sqlite3)

#if(WIN32)
#	set (PLATFORM_LIBS Ws2_32.lib Psapi.lib Iphlpapi.lib)
#endif(WIN32)

#SQLITE3 static lib
set (SRC sqlite3.c)
add_library(sqlite3 ${SRC})

