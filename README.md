[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2cf2367f96904e08b47507cf8331cfa2)](https://www.codacy.com/app/HDVinnie/MediaInfo-Helper?utm_source=github.com&utm_medium=referral&utm_content=HDVinnie/MediaInfo-Helper&utm_campaign=badger)
[![Latest Stable Version](https://poser.pugx.org/hdvinnie/mediainfo-helper/v/stable)](https://packagist.org/packages/hdvinnie/mediainfo-helper) [![Total Downloads](https://poser.pugx.org/hdvinnie/mediainfo-helper/downloads)](https://packagist.org/packages/hdvinnie/mediainfo-helper)

# MediaInfo-Helper

A Laravel helper for parsing MediaInfo dumps.

## Install

Via Composer

``` bash
$ composer require hdvinnie/mediainfo-helper
```

## Usage

**Parsing a MediaInfo string**

Returns an array containing the parsed information.

```php
$parser = new MediaInfo();
$parsed = $parser->parse($mediaInfo);
```

## Testing

``` bash
$ composer test
```

## License
[The MIT License](LICENSE)
