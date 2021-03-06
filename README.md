# Zf2Datagrid

[![SensioLabsInsight](https://insight.sensiolabs.com/projects/f85e7364-7439-4787-ba54-16cfc536c416/mini.png)](https://insight.sensiolabs.com/projects/f85e7364-7439-4787-ba54-16cfc536c416) 
[![Latest Stable Version](https://poser.pugx.org/astek-go/zf2-datagrid/v/stable)](https://packagist.org/packages/astek-go/zf2-datagrid)
[![Total Downloads](https://poser.pugx.org/astek-go/zf2-datagrid/downloads)](https://packagist.org/packages/astek-go/zf2-datagrid)
[![Latest Unstable Version](https://poser.pugx.org/astek-go/zf2-datagrid/v/unstable)](https://packagist.org/packages/astek-go/zf2-datagrid)
[![License](https://poser.pugx.org/astek-go/zf2-datagrid/license)](https://packagist.org/packages/astek-go/zf2-datagrid)


Permet de créer des datagrid facilement avec Zf2 et Doctrine2.

# Fonctionnalités

* Datasources : Doctrine2 (QueryBuilder), PhpArray
* Renderer : TwitterBootstrap2, Excel, Csv
* Decorator > Renderer : Form
* Column : Select/Property/Index
* Decorator > Column : Checkbox/Closure/Date/Icon/Integer/Link/NoValue/Number/Percentage/Route/Tag/Text/Translate
* Pagination : pagination/order by

Bien sûr vous pouvez étendre vous même chacune des fonctionnalités.

# Dépendances

* Zend Framework 2 (Form)
* Doctrine 2 (Doctrine2Datasource)

## Optionnelles

* PHPOffice/PHPExcel pour l'export Excel

# Installation

## Via composer

Placez-vous à la racine de votre répertoire projet et utilisez la commande :

```
php composer.phar require astek-go/zf2-datagrid:dev-master
```

Vous-êtes maintenant ready to go.

# Documentation

Pour apprendre à utiliser cette librairie vous pouvez consulter la [documentation](/docs/01. Introduction.md) !

# TODO

* Documentation / Exemples WIP
* Gérer les attributs HTML pour les Column (th/td)
* D'autres renderer out of the box (TwitterBootstrap3, Foundation...)
* D'autres datasource out of the box (Zend\Db ? autres...)

---
Après ça : [Introduction](/docs/01. Introduction.md)
