COMMENT =	minimal OPC UA client GUI

MODPY_EGG_VERSION =	0.8.0

DISTNAME =	opcua-client-${MODPY_EGG_VERSION}
PKGNAME =	opcua-client-gui-${MODPY_EGG_VERSION}
REVISION =	5

CATEGORIES =	misc

MAINTAINER =		Alexander Bluhm <bluhm@openbsd.org>

# GPLv3
PERMIT_PACKAGE =	Yes

MODULES =		lang/python

RUN_DEPENDS =		graphics/py-pyqtgraph${MODPY_FLAVOR} \
			misc/freeopcua/py-opcua${MODPY_FLAVOR}>=0.98.1 \
			misc/freeopcua/py-opcua-widgets${MODPY_FLAVOR}>=0.5.4 \
			x11/py-qt5${MODPY_FLAVOR}

MODPY_PI =		Yes
MODPY_SETUPTOOLS =	Yes

.include <bsd.port.mk>
