.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

==================
Purchase Order UBL
==================

This module adds support for UBL, the `Universal Business Language (UBL) <http://ubl.xml.org/>`_ standard, on purchase orders. The UBL 2.1 standard became the `ISO/IEC 19845 <http://www.iso.org/iso/catalogue_detail.htm?csnumber=66370>`_ standard in December 2015 (cf the `official announce <http://www.prweb.com/releases/2016/01/prweb13186919.htm>_`).

With this module, when you generate the purchase order or RFQ report:

* on a draft/RFQ/Bid Received purchase order, the PDF file will have an embedded XML *Request For Quotation* file compliant with the UBL 2.1 or 2.0 standard.

* on an approved purchase order, the PDF file will have an embedded XML *Order* file compliant with the UBL 2.1 or 2.0 standard.

If your supplier has Odoo and has installed the module *sale_order_import_ubl*, he will be able to import the PDF file and it will automatically create the quotation/sale order.

Configuration
=============

No configuration is needed.

Usage
=====

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/226/8.0

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/OCA/edi/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Contributors
------------

* Alexis de Lattre <alexis.delattre@akretion.com>

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.
