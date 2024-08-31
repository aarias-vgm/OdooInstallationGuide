# ODOO 15 INSTALLATION GUIDE

1. :arrow_down: Download _Odoo Community_ for Windows from the [official website][odoo-url].

1. :gear: Run installer.

1. :open_file_folder: Select as installation path a folder named “Odoo” created in ``[user]\documents\``.

1. :page_facing_up: Copy the contents of your organization's folder with **Odoo 15 Enterprise addons**[^odoo-15-enterprise-url] and paste the whole content into ``[path]\Odoo\server\odoo\addons\``.

1. :arrows_counterclockwise: Restart service **"odoo-server-15.0"** on Windows Services.

1. :globe_with_meridians: Search for url [```http://localhost:8069/```](http://localhost:8069/)

> [!CAUTION]
> ⚠️ Please DO NOT SELECT the “Program Files” or its nested folders as the installation path. If you have done it :skull:, please use the **appropriate uninstaller tool**[^uninstaller-tool-url] tool to uninstall both programs **Odoo 15.0** and **PostgreSQL 12**.

[odoo-url]: https://www.odoo.com/es_ES/page/download

[^odoo-15-enterprise-url]: Please ask your supervisor for this folder.
[^uninstaller-tool-url]: Please ask your supervisor for this folder.