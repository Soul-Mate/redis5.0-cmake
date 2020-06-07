add_library(hiredis STATIC
        async.c
        dict.c
        hiredis.c
        net.c
        read.c
        sds.c
        test.c
        )