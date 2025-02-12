===============================
Product Harmonized System Codes
===============================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:0edb600eecba45eb87280a3c1a27dee0ecd0eaad0aafd710cf33b1bb93f1e602
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fintrastat--extrastat-lightgray.png?logo=github
    :target: https://github.com/OCA/intrastat-extrastat/tree/18.0/product_harmonized_system
    :alt: OCA/intrastat-extrastat
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/intrastat-extrastat-18-0/intrastat-extrastat-18-0-product_harmonized_system
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/intrastat-extrastat&target_branch=18.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module contains the objects for Harmonised System Codes (H.S.
codes). The full nomenclature is available from the World Customs
Organisation <`http://www.wcoomd.org/\\> <http://www.wcoomd.org/\>>`__.
These codes are usually required on the Proforma invoices that are
attached to the packages that are shipped abroad.

This module also handles the local/national extensions to the H.S.
codes. The import of the full nomenclature is not provided by this
module; it should be provided by localization modules.

You will also be able to configure the *country of origin* of a product,
which is often required on the proforma invoice for the customs.

This module should be usefull for all companies that export physical
goods abroad. This module is also used by the Intrastat modules for the
European Union, cf the *intrastat_product* module.

**Table of contents**

.. contents::
   :local:

Installation
============

This module is NOT compatible with the *account_intrastat* module from
Odoo Enterprise.

Usage
=====

As this module only depends on the *product* module and that module
doesn't provide any menu entry, this module lacks a menu entry for H.S.
Codes. A menu entry for H.S. codes is provided by the module
*product_harmonized_system_stock*.

Once the H.S. codes are created, you will be able to set the H.S. code
on a product (under the *Information* tab) or on a product category. On
the product form, you will also be able to set the *Country of Origin*
of a product (for example, if the product is *made in China*, select
*China* as *Country of Origin*).

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/intrastat-extrastat/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/intrastat-extrastat/issues/new?body=module:%20product_harmonized_system%0Aversion:%2018.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* brain-tec AG
* Akretion
* Noviat

Contributors
------------

- Alexis de Lattre, Akretion <alexis.delattre@akretion.com>
- Luc De Meyer, Noviat <info@noviat.com>
- Kumar Aberer, brain-tec AG <kumar.aberer@braintec-group.com>
- Nhan Tran <nhant@trobz.com>

Maintainers
-----------

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-alexis-via| image:: https://github.com/alexis-via.png?size=40px
    :target: https://github.com/alexis-via
    :alt: alexis-via
.. |maintainer-luc-demeyer| image:: https://github.com/luc-demeyer.png?size=40px
    :target: https://github.com/luc-demeyer
    :alt: luc-demeyer

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-alexis-via| |maintainer-luc-demeyer| 

This module is part of the `OCA/intrastat-extrastat <https://github.com/OCA/intrastat-extrastat/tree/18.0/product_harmonized_system>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
