# magento2-theme-simplicity-base2

use prefix for new variable, i'm using @theme_variable_name for now.

Magento_Theme\web\css\source\_extend.less
- top priority overrride
- only use _extend.less on child theme?, not sure.

web\css\source\_theme.less
- can override variables from _module.less and _variables.less

Magento_Theme\web\css\source\_module.less
- don't create new varialbe here.
- if you need to create new varialbe, put it in _variables.less

web\css\source\_variables.less
- contains theme specific variables
- you can declare new variables here and use it in _module.less and _theme.less
