# zero-storage-cloud
🚀 Proof of Concept for sharing files merely using URLs - without any server storage! 

***

A single `.html` file that can generate download links for your (rather small) files. Note that the GitHub pages demo is severely limited.

Needless to say, normal [Base64 Data URIs](https://developer.mozilla.org/en-US/docs/Web/URI/Reference/Schemes/data) would make much more sense in most use cases since they're widely supported.

Still, this demonstration has some advantages, such as the ability to trigger direct downloads. Base64 requires JavaScript for that.

## Limitations

- GitHub Pages limits URLs to under ~6000 characters, which should equal to about 6KB.
- The actual `index.html`, when selfhosted, can easily handle files with hundreds of KBs on modern desktop browsers. This includes short (very) low quality videos.
- From my understanding, it'd be impossible to [hotlink](https://de.wikipedia.org/wiki/Hotlinking) images links generated using this tool.

![](https://pixvid.org/images/2025/03/06/5-67.webp)

**This image takes up <6KB, the maximum GitHub pages allows in URLs.**

*Image by <a href="https://pixabay.com/users/idat-18128501/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7511632">Ida</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7511632">Pixabay</a>*
