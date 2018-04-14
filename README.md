**What is ipfs-personal?** 

This repository is for the personal website of Chris Spannos and is hosted on the InterPlanetary File System peer-to-peer hypermedia protocol. It is built using HTML5. The theme is "Forty" by HTML5 UP (html5up.net) under the CCA 3.0 license.

**How does it work?**

How it works, assuming you have IPFS installed and its daemon running, is to add the directory containing your website:

```
$ ls mysite
img index.html
$ ipfs add -r mysite
added QmcMN2wqoun88SVF5own7D5LUpnHwDA6ALZnVdFXhnYhAs mysite/img/spacecat.jpg
added QmS8tC5NJqajBB5qFhcA1auav14iHMnoMZJWfmr4k3EY6w mysite/img
added QmYh6HbZhHABQXrkQZ4aRRSoSa6bb9vaKoHeumWex6HRsT mysite/index.html
added QmYeAiiK1UfB8MGLRefok1N7vBTyX8hGPuMXZ4Xq1DPyt7 mysite/
```

The very last hash next to the folder name is the one you want.

**Important note:** These steps are copied from IPFS documentation. If using them, please refere instead to IPFS for Websites for complete and up to date documentation: https://ipfs.io/docs/examples/example-viewer/example#../websites/README.md

**Who will use this repo or project?**

The website is built, maintained and administered by Chris. 

**What is the goal of this project?**

This website is used to feature new content related to themes of technology, decentralization, autonomy and social justice.
