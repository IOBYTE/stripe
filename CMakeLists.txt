cmake_minimum_required(VERSION 3.16.3)
project(stripe)
add_executable ( stripe add.c common.c free.c global.h init.h local.h newpolve.h
		 options.h output.h outputex.h partial.h queue.c sgi_triang.c
		 sgi_triangex.c stripe.c struct.c structex.c ties.c util.c add.h
		 common.h free.h init.c local.c newpolve.c options.c output.c
		 outputex.c partial.c polverts.h queue.h sgi_triang.h sgi_triangex.h
		 stripeman.txt struct.h structex.h ties.h util.h)
