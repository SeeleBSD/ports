COMMENT=	provide information about the OS platform

MODPY_EGG_VERSION=	1.9.0
DISTNAME=	distro-${MODPY_EGG_VERSION}
PKGNAME=	py-${DISTNAME}

CATEGORIES=	sysutils

# Apache 2.0
PERMIT_PACKAGE=	Yes

FLAVORS=	python3
FLAVOR=		python3

MODULES=	lang/python
MODPY_PI=	Yes
MODPY_PYBUILD=	setuptools

TEST_DEPENDS=	devel/py-test-cov${MODPY_FLAVOR}

.include <bsd.port.mk>
