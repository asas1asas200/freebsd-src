PACKAGE=	tests

TESTSDIR=	${TESTSBASE}/sys/net/if_ovpn

ATF_TESTS_SH+=	if_ovpn
ATF_TESTS_C+=	if_ovpn_c

LIBADD+=	nv

TESTS_SUBDIRS+=	ccd

${PACKAGE}FILES+= \
	ca.crt \
	client.crt \
	client.key \
	client2.crt \
	client2.key \
	dh.pem \
	server.crt \
	server.key \
	user.pass \
	utils.subr

.include <bsd.test.mk>
