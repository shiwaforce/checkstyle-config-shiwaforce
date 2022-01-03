# checkstyle-config-shiwaforce
Checkstyle (https://checkstyle.org/) Shiwaforce config

### Differences between the two checkstyle xml files:
- checkstyle.xml - for Checkstyle 8.23 and earlier IDE plugin
- checkstyle2.xml - for Checkstyle 8.24 and later IDE plugin

**What happend at 8.24:** LineLength moved outside of TreeWalker and placed it directly in Checker.

### Related site:
- https://github.com/checkstyle/checkstyle/issues/2116
