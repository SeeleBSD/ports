COMMENT =	ForensicArtifacts.com Artifact Repository

MODPY_EGG_VERSION = 20200118
DISTNAME =	artifacts-${MODPY_EGG_VERSION}
PKGNAME =	py-${DISTNAME}
REVISION =	4

CATEGORIES =	security

HOMEPAGE =	https://github.com/ForensicArtifacts/artifacts

MAINTAINER =	Remi Pointel <rpointel@openbsd.org>

# Apachev2
PERMIT_PACKAGE =	Yes

MODULES =		lang/python
MODPY_PI =		Yes
MODPY_PYBUILD =	setuptools

FLAVORS =	python3
FLAVOR =	python3

RUN_DEPENDS =	textproc/py-yaml${MODPY_FLAVOR}
TEST_DEPENDS =	devel/py-yapf${MODPY_FLAVOR}
MAKE_ENV +=	LC_CTYPE='en_US.UTF-8'

.include <bsd.port.mk>
