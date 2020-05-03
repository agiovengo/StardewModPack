hello! thanks for downloading my mod!

here is how to add fennec foxes to BFAV and your game:

	1) extract your downloaded file from nexus (neonify fennec foxes.rar) into Stardew Valley/Mods
	
	2) go into the folder called "neonify fennec foxes" and take both the [JA] and the [BFAV] folders out, putting them into the Stardew Valley/Mods SEPERATELY. the JA folder is for the custom fox items, bfav for the foxes themselves. At this point, you can leave the ja folder alone

	3) go into the BFAV folder and copy the file called "animal_shop_fennecfox.png". go to Stardew Valley/Mods again and find your Paritee's Better Farm Animal Variety folder, paste the png into Paritee's Better Farm Animal Variety/assets

	4) go to the bfav config file and copy/paste this text in on the line after another already added animal's bracket. this may sound kind of confusing so leave a comment if something isn't working

    "Fennec Fox": {
      "Types": [
        "Fennec Fox",
        "Albino Fennec Fox"
      ],
      "Buildings": [
        "Big Barn",
        "Deluxe Barn"
      ],
      "AnimalShop": {
        "Name": "Fennec Fox",
        "Description": "These foxes love to dig! They'll leave part of what they find for you.",
        "Price": "10000",
        "Icon": "assets\\animal_shop_fennecfox.png"
      }
    }


for reference, this is what it'd look like as the last animal in the config file, and after another animal

    },
    "Deer": {
      "Types": [
        "Deer"
      ],
      "Buildings": [
        "Deluxe Barn"
      ],
      "AnimalShop": {
        "Name": "Deer",
        "Description": "These shy deer are fully domesticated, and will produce rich milk.",
        "Price": "10000",
        "Icon": "assets\\animal_shop_deer.png"
      }
    },
    "Fennec Fox": {
      "Types": [
        "Fennec Fox,"
        "Albino Fennec Fox"
      ],
      "Buildings": [
        "Big Barn,"
        "Deluxe Barn"
      ],
      "AnimalShop": {
        "Name": "Fennec Fox",
        "Description": "These foxes love to dig! They'll leave part of what they find for you.",
        "Price": "10000",
        "Icon": "assets\\animal_shop_fennecfox.png"
      }
    }
  }
}


I'm really new to this whole modding thing, please let me know if I wrote something wrong here >>