# WAE9Loader

WAEnhancer9 sideload version ( FULL version )

***Please note that now apple expires certificates in 7 days for free developer account*** 

- https://www.reddit.com/r/jailbreak/comments/4hotx3/news_free_developer_account_installs_reduced_to_7/

***For Help Visit:*** https://www.reddit.com/r/sideloaded

### WAEnhancer9 Features 

1 - support notifications ( even if the bundle it isn't net.whatsapp.WhatsApp )
2 - native IPAD UI
3 - full description : http://imokhles.com/waenhancer9/

### How-To:

- Open "WAE9Loader.xcodeproj"

- Click "WAE9Loader" on top left -> Then under targets click "WAE9Loader" again

- Click on the General tab:

- Change the Bundle Identifier to something unique (i.e com.YOURNAME.waenhancer9)

- Click on the team dropdown and select "Personal Team" or your developer account name

- Click the Play button on the top left and the sideloaded app will start building
 
- ***Please note that if this is the first time you are building the app, on your phone go to Settings -> General -> Devices and Trust the new profile***

Configuration (modify values in SIDELOADER_OPTIONS):
  - ***OVERWRITE_ORIGINAL_APP:*** If you want push notifications keep this true. If you want to install a duplicate app without push notifications set this to false
  - ***CREATE_IPA_FILES:*** If you set this to true after every build you will see an WAEnhancer9 IPA in the products directory inside your project folder.

Let me know if this works for you at http://twitter.com/imokhles


Credits:
  This project was inspired by work that https://twitter.com/eni9889 did on https://github.com/eni9889/ppsideloader