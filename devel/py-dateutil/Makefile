# Created by: Mario Sergio Fujikawa Ferreira <lioux@FreeBSD.org>
# $FreeBSD$

PORTNAME=	dateutil
PORTVERSION=	2.6.0
PORTREVISION=	1
CATEGORIES=	devel python
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	koobs@FreeBSD.org
COMMENT=	Extensions to the standard Python datetime module

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS?=	${PYTHON_PKGNAMEPREFIX}six>=1.5:devel/py-six

USES?=		python
USE_GITHUB=	yes
USE_PYTHON=	autoplist distutils

NO_ARCH=	yes

do-test:
	@cd ${WRKSRC} && ${PYTHON_CMD} ${PYDISTUTILS_SETUP} test

.include <bsd.port.mk>
