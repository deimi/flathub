flatpak-builder build-dir org.flatcam.FlatCAM.json --force-clean


~/tools/flatpak-builder-tools/pip/flatpak-pip-generator --requirements-file ~/tools/flatcam/requirements.txt --output flatcam_dependencies --no-build-isolation --runtime org.freedesktop.Sdk/x86_64/20.08

Problem with matplotlib, therefore the extra dependency includes
https://github.com/flatpak/flatpak-builder-tools/issues/47
