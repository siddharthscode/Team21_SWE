# Readme for the usage of the plugins 

This project basically aims in automating the book acquisition process handled by the library staff members in the IITH Library through the Koha ILMS. We achieve our goal by developing different plugins to automate different steps involved in the book acquisition Process like :
- Indentation Plugin to generate an indent for the selected books.
- Quotation Plugin to generate a request for quotation for the approved indents that can be sent to the vendors.
- Status plugin to check the status of the indent at any given time.

## Files
All the plugins that we provide are zipped into a kpz file individually are are ready to be installed and used in Koha.  These zip files would basically contain all the template toolkit and perl module files necessary for the plugin to work . Below are the zip files for the plugins :
- Indentation plugin - [koha-plugin-indentation-final.kpz](https://github.com/siddharthscode/koha_plugin/blob/master/koha-plugin-indentation-final.kpz "koha-plugin-indentation-final.kpz")
- Quotation plugin -[koha-plugin-quotation-final.kpz](https://github.com/siddharthscode/koha_plugin_quotation/blob/master/koha-plugin-quotation-final.kpz "koha-plugin-quotation-final.kpz")
- Status plugin - [Koha_plugin_status_0.kpz](https://github.com/siddharthscode/koha_plugin_status/blob/master/Koha_plugin_status_0.kpz "Koha_plugin_status_0.kpz")


# Employment of the plugins

To utilize any plugin below mentioned steps are to be followed :
 1. Download the  kpz file corresponding to the plugin you want to use.
 2. Log in to the Koha webpage and click on **"Koha administration"**.  
 3. In the next page that you land into, click on the **"manage plugins"** link under the **"Plugins"** section.
 4. Click on the **"Upload plugin"** and select the kpz file of the plugin that you want to use. Once the file is uploaded , the plugin name gets displayed in the list of plugins as shown in the below image. ![Plugins in Koha](https://i.ibb.co/JK412DM/plugin.png)
 5. Now click on the **"Actions"** tab next to the plugin you want to run and click on the **"Run tool"** from the window of actions listed for that plugin.
 6. *Alternate way to run the plugin* :
	 -  Once the plugins' kpz file is uploaded, go back to Koha's homepage  
    and click on the **"Tools"** tab.
    - On the next page you land into, under the **"Tools plugins"** section click on any of the plugin you want to use.Refer to the below displayed image. ![enter image description here](https://i.ibb.co/6ZDXt9X/tools-plugins.jpg)
 8. The functionalities of the plugin that we provide can then be tested further.


