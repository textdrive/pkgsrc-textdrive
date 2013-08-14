# $NetBSD:$
#

DISTNAME=	virtualenv-1.10.1
PKGNAME=	${PYPKGPREFIX}-${DISTNAME}
CATEGORIES=	devel
MASTER_SITES=	http://pypi.python.org/packages/source/v/virtualenv/

MAINTAINER=	jacques@textdrive.com
HOMEPAGE=	http://wwwi.virtualenv.org/
COMMENT=	Virtual Python Environment builder
LICENSE=	mit

PKG_DESTDIR_SUPPORT=	user-destdir

PLIST_SUBST+=		PYVERSSUFFIX="${PYVERSSUFFIX}"

.include "../../lang/python/egg.mk"
.include "../../mk/bsd.pkg.mk"
