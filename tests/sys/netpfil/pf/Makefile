# $FreeBSD$

PACKAGE=	tests

TESTSDIR=       ${TESTSBASE}/sys/netpfil/pf

ATF_TESTS_SH+=	pass_block \
		forward \
		fragmentation \
		set_tos

${PACKAGE}FILES+=	utils.subr \
			pft_ping.py

${PACKAGE}FILESMODE_pft_ping.py=	0555

.include <bsd.test.mk>
