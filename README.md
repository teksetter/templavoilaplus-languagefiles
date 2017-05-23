# TemplaVoilà+ Language Files
This is the repository for the language files which can be used in TemplaVoilà Plus.

As I've no open pottle (or any other) server yet and management over http://translation.typo3.org isn't possible for now, I'll try to manage the language files here.
From time to time they will be uploaded to the place where TYPO3 can download them.

You can contribute to this files via githubs pull requests.

In TemplaVoilà Plus is implemented to use versionized language files, for this feature the major version number of your TemplaVoilà Plus installation is used.

Directory structure:
- First level contains the major version number
- Second level contains the language ISO code as TYPO3 core uses it
- The language files will be directly under this second level

For the language zip files on my server the language files get moved to their correct place (templavoilaplus/Resources/Private/Language) before packed into the zip.
Result Example: http://ter.templavoila.plus/templavoilaplus-v7/t/e/templavoilaplus-l10n/templavoilaplus-l10n-de.zip
