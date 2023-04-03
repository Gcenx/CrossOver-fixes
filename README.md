# CrossOver-fixes


Heres a quick fix for macOS Ventura 13.3 until CW pushes a new update.

- Download the attached archive
- Open Terminal and run the following command
> xattr -drs com.apple.quarantine ~/Downloads
- extract the archive
- copy/paste these files into
> CrossOver.app/Contents/SharedSupport/CrossOver/bin
- (replace when prompted)

CrossOver should now run like normal

# Disclaimer
While this change gets CrossOver functioning again modifying CrossOver isn't supported by CodeWeavers.\
They've already imported the exact same fixes into there nightly builds and a release should land shortly.

<br>

The _only_ reason I've decided to provide a fix for this is downgrading Apple Silicon systems can be rather complicated.
