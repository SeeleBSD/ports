COMMENT =	KDE monitor calibration tool
DISTNAME =	kgamma-${VERSION}

WANTLIB += ${COMPILER_LIBCXX} GL ICE KF6ColorScheme KF6ConfigCore
WANTLIB += KF6ConfigGui KF6ConfigWidgets KF6CoreAddons KF6I18n
WANTLIB += KF6KCMUtils KF6KCMUtilsCore KF6KCMUtilsQuick KF6WidgetsAddons
WANTLIB += Qt6Core Qt6Gui Qt6Network Qt6Qml Qt6Widgets SM X11
WANTLIB += Xext Xxf86vm m

MODKDE_TRANSLATIONS = Yes
MODKDE_DOCS = Yes

# Qt6::PdfQuickplugin
BUILD_DEPENDS =	x11/qt6/qtwebengine
RUN_DEPENDS =	x11/qt6/qtwebengine \
		devel/desktop-file-utils

LIB_DEPENDS =	devel/kf6/kconfig \
		devel/kf6/kcolorscheme \
		devel/kf6/kconfigwidgets \
		devel/kf6/kcoreaddons \
		devel/kf6/ki18n \
		devel/kf6/kcmutils \
		devel/kf6/kwidgetsaddons \
		x11/qt6/qtdeclarative

DEBUG_PACKAGES =	${BUILD_PACKAGES}

.include <bsd.port.mk>
