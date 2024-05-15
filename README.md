# ir-codes
This is no software project, rather just a collection of IR codes I've gathered from here and there with the interest that they are publicly available, and that nobody has to go through the steps I had to go through to get them.


## Disclaimer

If the [IRDB project](https://github.com/probonopd/irdb/) has the information, I will probably delete them from here (unless it's another format), so check that amazing project.

I really believe IR codes could keep some hardware alive and useful, which is something we truly need in the era of climate change, so we can reduce electronic waste as much as possible.


## Related info


### Databases

Here's some databases I've consulted in my journey.

- As I've said [IRDB](https://github.com/probonopd/irdb/) so far looks to me like the best project regarding IR code databases, but create an issue if you disagree, please. Just go there, download, and convert to your format.
- [Global Caché's Control Tower database](https://irdb.globalcache.com/). A bit of a weird system that requires an account.
- [JP1 remotes](http://www.hifi-remote.com/forums/index.php?sid=186aaa46242250975d10e8d9e3f0fdbe), also need an account to download stuff.
- [LIRC database](https://lirc-remotes.sourceforge.net/remotes-table.html). May do the job.


### Conversion software

Conversion software I've used.

- [IrScrutinizer](https://github.com/bengtmartensson/IrScrutinizer). This software is very much complete and works. It reminded me how much I hate Java stuff, tho. But **I am so thankful for this** software (and the AppImage packaging is amazing).
- [RemoteManager](https://controlremote.sourceforge.io/). Necessary for being able to convert JP1 codes into GIRR codes (so then you can put them in `IrScrutinizer` to convert to whatever). Sometimes I wish Java was just a dream. I wish I had time to make a modernized version of this and `IrScrutinizer`. I couldn't find a self-contained version, so get ready to waste some time with Java stuff.

Again, if you have some other option out there, please let's start a discussion on this repo, I really want to know more about this world.
