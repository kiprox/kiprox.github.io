---
title:  "Google Drive Unlimited"
subtitle: "Team or Shared Drives with Dark Mode."
author: "Candro"
avatar: "img/authors/wferr.png"
image: "img/a.jpg"
date:   2020-12-06 08:12:11
---

## How to

* Current Version `2.0.0`
* Beta Version (Latest)
* If you want to deploy main drive leave the option ROOT as it is.
* If you want to deploy your Team Drive/Shared Drive/Folder then copy the ID and replace it with ROOT.
* Eg. if you open this shared drive `https://drive.google.com/drive/u/0/folders/0AOM2i7MQiuWIUk9PVA` - `0AOM2i7MQiuWIUk9PVA` is its ID.
* Authenticate and copy the code from Google and paste it into Authorization Code Box.
* Click on Get Code to Generate Code and Copy it for later use.
* Now Create Cloudflare account and verify email or login with existing account.
* Find Workers and Open it.
* Create your sub-domain or continue if already done.
* Select the Free Plan.
* Click on Create a Worker.
* You can rename the workers at top of the page.
* Now paste the code you copied before.
* Click on Save and Deploy.
* Done. (May take time for some users due to new account or cache issues)

## Brand Customization and Dark Mode

* In Latest Release, you can rebrand the Index as per your needs.
* Line 57 will help you select light or dark theme where false is light and true will be dark theme.
* After that each line has its own custom feature. Edit as per your needs.
* You can remove credit option but we request you not to.
* See Below code to understand Customization.

## Search Limitations

* Search only works if you use Shared Drive ID or root.
* Search won't work or the bar won't appear if you're using Folder ID inside from root or Shared Drive.

## Known Bugs

* Current Path at File Destination shows `/`, which shouldn't appear.
* Light Mode Text Hover Underline needs to be fixed.
* Size and Modified Date should float on right side.
* .zip/.rar files on Search doesn't works.

## Upcoming Changes

* Clear Path to Navigate inside Previous Folders (currenty shows inside menu).
* 3rd Party Video and Audio Players.
* Icons from other Index for better view.
* Custom Switch to Turn Off/On the Size and Modified Date Element.
* Custom Dimensions for Logo.
* Adding Links to other Indexes.
* Adding More Features from other Indexes.
* Click to Copy Download Button

## Support this Project

[![Support](https://cdn.buymeacoffee.com/buttons/v2/default-white.png)](https://www.buymeacoffee.com/candro)
