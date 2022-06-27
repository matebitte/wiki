# Taking Notes

TL, DR: Depending on the area, I use a suitable tool. 

For **personal notes**, as well as blog and wiki drafts, I use [Standardnotes](https://standardnotes.com/), because it is the only app that consistently and thoughtfully implements strong encryption AND sucessfully passed a security audit. I organise my **creative work** or professional stuff in [Milanote](https://milanote.com/). For my **[public notes](https://note.decided.to/)** I use a combination of Github, Gitjournal and Visual Studio Code with some extensions.


<br/>

## Recommendations
My focus is on data protection/privacy through encryption and its verifiability through open source software.

### Databases
These apps work with a database that is then synced to devices via an internal sync mechanism.

- https://standardnotes.com (including blogging platform listed!)
- https://joplinapp.org
- https://www.etesync.com

Standardnotes is free for the essentials, but recently the really fancy stuff became more expensive. Now it's 5€-10€/month or you selfhost the extended server (ideally as a collective). Good UX design.

I think Joplin's feature set is great, unfortunately webDAV sync takes a long time, is sometimes unreliable and the UX just sucks on mobile.

Turtl is technically very good, also the collaborative books are fancy, unfortunately it is super ugly and there were no updates for a long time.

[Lunatask](https://lunatask.app/) is actually "only" an e2ee task management app, but can also take notes.

[Serenity Notes](https://www.serenity.re/en/notes) allows collaborative note-taking secured via e2ee, but the apps are still offline capable (unlike cyptpad). Currently more of a tech demo, not a finished product.

### Flat File 
These apps work locally, with simple text files on the device. These .md text files can be easily synced between all devices using Nextcloud, Syncthing or Git.

Advantage: switching between apps is easy, even windows notepad could read the files. With a static site generator, wikis / websites can be quickly made from the notes, an example is this wiki.

Disadvantage: e2ee is not easy and if implemented correctly, it dismantles the biggest advantage: simply tinkering a pipeline that generates a wiki is not possible with e2ee.

- https://notable.app/
- https://www.zettlr.com/
- https://foambubble.github.io/foam/

Zum bearbeiten auf Mobilgeräten ist https://gitjournal.io/ super.

### Cloud Solutions
[Nextcloud Notes](https://apps.nextcloud.com/apps/notes) is FOSS, works with files & has an open API that is used by mobile apps like [Quillnote](https://qosp.org). A similarly good FOSS solution is [carnet](https://www.getcarnet.app/). Unfortunately, there is no end-to-end encryption with either.

An e2ee, self-hosted cloud solution is [trilium](https://github.com/zadam/trilium). There is a mobile frontend, but no offline android app.

<br/>

## Special
### Proprietary Solutions
Those arent bad, I simply don't fancy closed source for my notes.

[ObsidianMD](https://obsidian.md/) is also nice, but not open source. Obsidian is a bit in between worlds, it works with local files but encrypted sync is built in, mobile apps exist. But for sync you have to pay 9$/month.

[Notesnook](https://notesnook.com/) also uses e2ee, but not as consistently as Standard Notes. The editor (TinyMCE) is great. The organisation with tags, colours and notebooks is flexible, but a bit too much for me.

[Inkdrop](https://www.inkdrop.app/) is proprietary, but e2ee and very hackable. Detailed docs on configs, as well as plugin and database APIs. Even your own sync server is possible. Costs: 5$/month.

[UpNote](https://getupnote.com/) is also nice, has some special features, but no e2ee and no focus on privacy. The same goes for [Supernotes](https://supernotes.app/) and [Nimbus](https://nimbusweb.me).

### Creative Work

Good collaborative whiteboards or virtual creative spaces don't currently do e2ee. But these are feature-rich and promise privacy.

- https://milanote.com/ (hybrid of whiteboard and notes)
- https://www.mural.co/ (collaborative whiteboard)
- https://miro.com/ (collaborative whiteboard)
- https://www.kdanmobile.com/noteledge
- https://www.zoho.com/notebook/

### Companies / Business Suites
Closely interwoven with CRM and Office are these:

- https://zenkit.com/en/hypernotes/
- https://www.zoho.com/notebook/

<br/>

## Questionable
...if you care about data privacy. These companies don't necessarily have the best reputation, even through their policies seem fine.

- https://www.google.com/keep/
- https://simplenote.com/
- https://evernote.com/
- https://www.microsoft.com/de-de/microsoft-365/onenote/
