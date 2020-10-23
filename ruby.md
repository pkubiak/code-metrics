# Ruby Code metrics #

Sources:
- https://github.com/metricfu/metric_fu/wiki/Code-Tools
- https://www.ruby-toolbox.com/categories/code_metrics
- https://github.com/search?q=metrics&type=topics
- https://blog.usejournal.com/ruby-software-complexity-metrics-part-two-calculations-a00fbab610d2


## metric-fu ##
https://github.com/metricfu/metric_fu

Meta-tool integrating results of many metrics tools into single report.

- **Metrics:** Integrate reports from `churn`, `cane`, `flay`, `roodi`, `saikuro`, `flog`, `reek`, `hotspots`, `rails_best_practices` (https://github.com/metricfu/metric_fu/wiki/Code-Tools)
- **Sample report:** https://metricfu.github.io/metric_fu/old_index.html


### rubycritic ###
https://github.com/whitesmith/rubycritic

RubyCritic is a gem that wraps around static analysis gems such as Reek, Flay and Flog to provide a quality report of your Ruby code.

- **Metrics:**


### RuboCop ###
https://github.com/rubocop-hq/rubocop

RuboCop is a Ruby static code analyzer (a.k.a. linter) and code formatter. Out of the box it will enforce many of the guidelines outlined in
the community Ruby Style Guide. Apart from reporting the problems discovered in your code, RuboCop can also automatically fix many of them for you.
(buildin cops: https://docs.rubocop.org/rubocop/cops.html)

- **Metrics:** ABCSize, CyclomaticComplexity, Block/Method Length, PerceivedComplexity, ... (https://docs.rubocop.org/rubocop/cops_metrics.html)


---

### reek ###
https://github.com/troessner/reek

Reek is a tool that examines Ruby classes, modules and methods and reports any code smells it finds.

- **Metrics:** Code smells 


### flay ###
https://github.com/seattlerb/flay

Flay analyzes code for structural similarities. Differences in literal values, variable, class, method names, whitespace,
programming style, braces vs do/end, etc are all ignored.

- **Metrics:** Code Duplication Score (smell)


### bundler-audit ###
https://github.com/rubysec/bundler-audit

Dependency verification tool for bundler gem manager.

- **Metrics:** Number of outdated/vulnerable gems

### bugspots ###
https://github.com/igrigorik/bugspots

An implementation of the simple bug prediction heuristic based on project git log.

- **Metrics:** Number of hotspots
