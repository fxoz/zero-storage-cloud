# zero-storage-cloud
🚀 Proof of Concept for sharing files merely using URLs - no storage needed!

Needless to say, normal [Base64 Data URIs](https://developer.mozilla.org/en-US/docs/Web/URI/Reference/Schemes/data) would make much more sense in most use cases since they're widely supported.

Still, this demonstration has some advantages, such as the ability to trigger direct downloads. Base64 requires JavaScript for that.

Limitations:
- GitHub Pages limits URLs to under ~6000 characters
- The actual `index.html`, when selfhosted, can easily handle files with hundreds of KBs on modern desktop browsers.
