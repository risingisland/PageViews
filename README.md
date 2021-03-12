# PageViews
### (Module/Plugin/Snippet)

[!Pageviews!]

[!PageViews? &unit=`View,Views,Views` &tpl=`@CODE:[+views+] [+unit+]`!]

[!pvController? &tpl=`@CODE:[+pagetitle+] [+views+]` &orderBy=`views DESC`!]

[!pvController? &prepare=`pageviewsDocLister::prepare` &tpl=`@CODE:[+pagetitle+] [+views+] [+unit+]` &orderBy=`views DESC` &unit=`View,Views,Views`!]
