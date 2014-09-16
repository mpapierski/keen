cmake_minimum_required (VERSION 2.6)
project (keen C)

set (SOURCES
	gelib.c
	id_ca.c
	id_in.c
	id_mm.c
	id_rf.c
	id_sd.c
	id_us.c
	id_us_s.c
	id_vw.c
	jam_io.c
	kd_act1.c
	kd_act2.c
	kd_demo.c
	kd_keen.c
	kd_main.c
	kd_play.c
	lzhuf.c
	soft.c)

set (HEADERS
	audiokdr.h
	gelib.h
	graphkdr.h
	id_ca.h
	id_heads.h
	id_in.h
	id_mm.h
	id_rf.h
	id_sd.h
	id_us.h
	id_vw.h
	jam_io.h
	kd_def.h
	lzhuff.h
	lzw.h
	sl_file.h
	soft.h)

add_executable (keen
	${SOURCES}
	${HEADERS})

