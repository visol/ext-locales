# Standard Labels for TYPO3

This extension brings standard labels such as week days and month names
to your fingertip.
 

## Usage

Within your extension, you may use the standard TYPO3 API to fetch localized 
labels.

For Backend usage:

```
$GLOBALS['LANG']->sL('LLL:EXT:locales/Resources/Private/Language/locallang.xlf:day.full.1');
```

For Frontend usage:

```
$GLOBALS['TSFE']->sL('LLL:EXT:locales/Resources/Private/Language/locallang.xlf:day.full.1');
```

Have fun, and please contribute to the translation on
https://translation.typo3.org/projects/TYPO3.ext.locales/
