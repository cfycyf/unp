include ../Make.defines

PROGS =	daytimetcpcli daytimetcpcli1 daytimetcpcli2 daytimetcpcli3 \
		daytimetcpsrv daytimetcpsrv1 daytimetcpsrv2 daytimetcpsrv3 \
		daytimetcpcliv6 daytimetcpsrvv6 \
		byteorder

all:	${PROGS}
LIBS =  -lpthread
daytimetcpcli:	daytimetcpcli.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli.o ../lib/error.o ${LIBS}

daytimetcpcli1:	daytimetcpcli1.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli1.o ../lib/error.o ${LIBS}

daytimetcpcli2:	daytimetcpcli2.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli2.o ../lib/error.o ${LIBS}

daytimetcpcli3:	daytimetcpcli3.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli3.o ../lib/error.o ${LIBS}

daytimetcpsrv:	daytimetcpsrv.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv.o ../lib/error.o ${LIBS}

daytimetcpsrv1:	daytimetcpsrv1.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv1.o ../lib/error.o ${LIBS}

daytimetcpsrv2:	daytimetcpsrv2.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv2.o ../lib/error.o ${LIBS}

daytimetcpsrv3:	daytimetcpsrv3.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv3.o ../lib/error.o ${LIBS}

daytimetcpcliv6:	daytimetcpcliv6.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpcliv6.o ../lib/error.o ${LIBS}

daytimetcpsrvv6:	daytimetcpsrvv6.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrvv6.o ../lib/error.o ${LIBS}

byteorder:	byteorder.o ../lib/error.o
		${CC} ${CFLAGS} -o $@ byteorder.o ../lib/error.o ${LIBS}

clean:
		rm -f ${PROGS} ${CLEANFILES}
