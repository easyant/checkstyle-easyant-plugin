checkstyle-plugin
=================

Checkstyle EasyAnt plugin is used to check code quality.
By default this module generates XML report, but you can use a specific target (:report-html) to generate HTML report.
This module can breaks the build-process, if code is not conform to a Checkstyle rules.
You can easily change checkstyles rules by changing checkstyle.config.file property.
Checkstyles target can be skipped using skip.checkstyle property
