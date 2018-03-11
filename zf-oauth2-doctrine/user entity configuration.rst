User Entity Configuration
=========================


This repository supplies every entity you need to implement OAuth2
except the User entity.  The reason is so the User entity can be
decoupled from the OAuth2 Doctrine repository instead to be linked
dynamically at run time.  This allows, among other benefits, the ability
to create an ERD without modifying the `OAuth2-orm.module.xml` module.

The User entity must implement ``ZF\OAuth2\Doctrine\Entity\UserInterface``

The User entity for the unit test for this module is a good template to start from:
`https://github.com/api-skeletons/zf-oauth2-doctrine/blob/master/test/asset/module/Doctrine/src/Entity/User.php <https://github.com/api-skeletons/zf-oauth2-doctrine/blob/master/test/asset/module/Doctrine/src/Entity/User.php>`_

.. note::
  Maintained by `API Skeletons <https://apiskeletons.com>`_.

:raw-html:`<script async src="https://www.googletagmanager.com/gtag/js?id=UA-64198835-3"></script><script>window.dataLayer = window.dataLayer || [];function gtag(){dataLayer.push(arguments);}gtag('js', new Date());gtag('config', 'UA-64198835-3');</script>`
