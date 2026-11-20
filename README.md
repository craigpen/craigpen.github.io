Holds `.well-known/assetlinks.json`, which tells Android that the Family wish lists app
(package `app.familyregistry.helper`) and https://craigpen.github.io/family-registry/ belong together,
so the app opens the site full-screen. Android only looks for it at the top of the domain, which
is why it lives here and not in `family-registry`. The fingerprint is the app's signing key (public).
The home page just goes on to the wish list.
