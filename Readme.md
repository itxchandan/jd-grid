## ⌘ Cmd

* npm init -y
* npm i bootstrap@4.5.0
* sass --watch scss:css --style=expanded --no-cache

<!-- Commented Files -->
* Never comment "function, variables, mixins & grid" files.

### add "jd-" in mentioned files
* node_modules\bootstrap\scss\mixins\_grid-framework.scss

## Replace class Name

|Bootstrap|JD Grid| Notes|
|-|-|- |
|``container``|``jd-container``| |
|``container-fluid``|``jd-container-fluid``| |
|``row``|``jd-row``| |
|``no-gutters``|``jd-no-gutters``| |
|``col``|``jd-col``| |
|``row-cols-2``|``jd-row-cols-2``| |
|``col-1``|``jd-col-1``| |
|Joomla|jd-Joomla| |

## Order's class
|Bootstrap|JD Grid| Notes|
|-|-|-|
|``order-first``|``jd-order-first``| To be display on First |
|``order-last``|``jd-order-last``| To be display on Last |
|``order-0``|``jd-order-0``| Total class: ``jd-order-0`` to ``jd-order-12`` |

## Offset's class

|Bootstrap|JD Grid| Notes|
|-|-|-|
|``offset-1``|``jd-offset-1``| Total Class: ``jd-offset-1`` to ``jd-offset-11`` |

## Responsive breakpoints

|Bootstrap|JD Grid| Notes|
|-|-|-|
| |``@media (min-width: 576px)``| Small devices (landscape phones, 576px and up)|
||``@media (min-width: 768px)``|Medium devices (tablets, 768px and up)|
||``@media (min-width: 992px)``|Large devices (desktops, 992px and up)|
||``@media (min-width: 1200px)``|Extra large devices (large desktops, 1200px and up)|
