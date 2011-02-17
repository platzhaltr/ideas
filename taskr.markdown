# Todo Manager #

* Todos provided as a webservice
* Light weight clients for accessing these todos

## Features ##

* Dependecies
 * only offer todos that are available now 
* Quick Add for todos (via keyboard shortcut)
* RESTful HTTP service
* webhooks for extensions
 * SMS

## KISS ##

* jeder Task ist ein reiner String
* "/" definiert Tag
* "@" definiert Kontext
* "#" als mögliches Tag (ala twitter)

# Language Processing #

## An einem bestimmten Tag ##

am weekday|zahl|zahl.|zahl monat|zahl. monat

tokenize 

Montag
Dienstag
Mittwoch
Donnerstag
Freitag
Samstag
Sonntag

Ignore Case

Trie aufbauen
