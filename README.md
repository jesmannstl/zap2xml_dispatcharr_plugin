# **Zap2xml\_Dispatcharr\_Plugin**



## **A plugin for** [**Dispatcharr**](https://github.com/dispatcharr/dispatcharr) **to automatically add EPG Data**

### 

### **Installation**



Download the Zip file and either place in the Dispatcharr Plugins folder or go to the Plugins page in Dispatcharr and Import Plugin.

Download channels.db and update in your Dispatcharr /data/plugins/zap2xml folder when available for updated channels



### **Usage**



**Lineup IDs:** Add one or multiple lineupId's (comma separated)

**Total Hours to Fetch:** Adjust in 6 hour increments Minimum 6 Maximum 360 (Note 348 is safer as the data is not always available for 360 hours)

**Delay Between Requests (sec):** The seconds between each 6 hour request.  5 is default but you can lower just want to avoid rate limiting on the website.

**HTTP User Agent:** By default it rotates between different desktop browser agents so should not need override

**Refresh Interval (hours):** Default 24 hours will automatically rerun.

**EPG Name:** Name saved to the Dispatcharr /data/epgs folder.  Default is Zap2xml and if multiple lineups will save as \_merged



### **FAQ's**



**Can you add country name not on** [**Valid Country Codes**](https://github.com/jesmannstl/zap2xml_dispatcharr_plugin/blob/main/Valid%20Country%20Codes.md) **page?**
No.  The original zap2xml only supported US and Canada but I was able to expand it for most supported countries in North and South America plus the Caribbean.  This method did not work for Europe or Australia.  The data provider itself does not support Asia, Africa or Antarctica.



**Where can I find a lineupId for this area?**
I created a lineup lookup for supported countries at [https://zap2xml.jesmann.com](https://zap2xml.jesmann.com) just select the country name and add the Zip/Postal Code and search.

