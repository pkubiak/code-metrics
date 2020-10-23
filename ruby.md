# Ruby Code metrics #

## metric-fu ##
https://github.com/metricfu/metric_fu

Meta-plugin integrating results of many metrics tools into single report (https://github.com/metricfu/metric_fu/wiki/Code-Tools).
*Metrics:* 

### RuboCop ###
https://github.com/rubocop-hq/rubocop

RuboCop is a Ruby static code analyzer (a.k.a. linter) and code formatter. Out of the box it will enforce many of the guidelines outlined in
the community Ruby Style Guide. Apart from reporting the problems discovered in your code, RuboCop can also automatically fix many of them for you.
(buildin cops: https://docs.rubocop.org/rubocop/cops.html)

*Metrics:* ABCSize, CyclomaticComplexity, Block/Method Length, PerceivedComplexity, ... (https://docs.rubocop.org/rubocop/cops_metrics.html)

### flay ###
https://github.com/seattlerb/flay

Flay analyzes code for structural similarities. Differences in literal values, variable, class, method names, whitespace,
programming style, braces vs do/end, etc are all ignored.

*Metrics:* Code Duplication Score (smell)


### bundler-audit ###
https://github.com/rubysec/bundler-audit

Dependency verification tool for bundler gem manager.

*Metrics:* Number of outdated/vulnerable gems
