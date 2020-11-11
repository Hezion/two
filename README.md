# NOVA-Child-Vorlage für Shop 5.0

Dieses Template dient als Vorlage für ein eigenes Child-Template des NOVA.
Es basiert auf dem NOVA-Theme "clear" und enthält alle (und nur die) Dateien, die mindestens in einem NOVA-Child-Template
vorhanden sein müssen.
- Alle notwendigen Style- und SASS-Dateien sind angelegt, beinhalten aber ausser den notwendigen Vererbungs-Includes 
keine eigenen Änderungen.

## Installation
**ACHTUNG!!!** Die NOVA-Child-Vorlage ist so angelegt, dass sie in das Verzeichnis *NOVAchild* des Template-Ordners
installiert werden muss, um korrekt zu funktionieren! Ggfs. muss der automatisch erstellte Ordner beim Entpacken aus dem Git-Download entsprechend
umbenannt werden.
Eine Änderung des Verzeichnisnamens ist nur möglich, wenn dazu auch die Namespace-Zeile (Zeile 3) in der Datei [Bootstrap.php](Bootstrap.php)
entsprechend zu **namespace Template\neuerVerzeichnisname;** geändert wird.

## Parent Theme ändern

Zum Ändern des Parent-Theme müssen lediglich die Pfade für die Imports in [nova-child.scss](themes/my-nova/sass/nova-child.scss)
und [_variables.scss](themes/my-nova/sass/_variables.scss) angepasst werden. Anschließend muss die nova-cild.css neu 
kompiliert werden

## Versionen

- [Shop 5.0](https://gitlab.com/jtl-software/jtl-shop/child-templates/NOVA-child-vorlage/tree/master)

## Related Links

[Templates](http://docs.jtl-shop.de/de/latest/shop_templates/index.html) - Entwickler Dokumentation Templates