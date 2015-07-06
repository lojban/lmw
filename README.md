http://mw.lojban.org
===

## Lojbanic MediaWiki issues
* editing pages is slow. emailing problems?
* Metrolook has bugs like https://github.com/paladox/Metrolook/issues/109

## Todo. Improve performance
comment out these lines

```
require_once( "$IP/extensions/LogoFunctions/LogoFunctions.php" );//you can change the logo
require_once("$IP/extensions/CSS/CSS.php");
require_once "$IP/skins/Vector/Vector.php";
require_once "$IP/extensions/Mantle/Mantle.php";
require_once( 'extensions/Wikilog/Wikilog.php' );
require_once("$IP/extensions/WikiForum/WikiForum.php");
require_once("$IP/extensions/WebChat/WebChat.php");
require_once("$IP/extensions/DeleteBatch/DeleteBatch.php");
require_once( "$IP/extensions/Collection/Collection.php" );
```

## ToDo
* Flow extension, a replacement of Talk tabs should be available in beta version in 2014. Please install it when it's ready to use. https://www.mediawiki.org/wiki/Extension:Flow
* http://mw.lojban.org/papri/Talk:proga:LMW_-_Lojbanic_MediaWiki
## Other places reporting issues
* http://mw.lojban.org/papri/proga:LMW_-_Lojbanic_MediaWiki#ToDo_and_the_future_of_le_uitki

## Migrating

for the new location of it:

* dont move ./files, instead redirect them back to gleki's profile
* similarly don't move ./extensions/ilmentufa
* the rest can be safely moved

