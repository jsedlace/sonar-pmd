# StdCyclomaticComplexity
**Category:** `pmd`<br/>
**Rule Key:** `pmd:StdCyclomaticComplexity`<br/>
> :warning: This rule is **deprecated** in favour of [MethodCyclomaticComplexity](https://rules.sonarsource.com/java/RSPEC-ethodCyclomaticComplexity).

-----

Complexity directly affects maintenance costs is determined by the number of decision points in a method plus one for the method entry. The decision points include 'if', 'while', 'for', and 'case labels' calls. Generally, numbers ranging from 1-4 denote low complexity, 5-7 denote moderate complexity, 8-10 denote high complexity, and 11+ is very high complexity.

<p>
  This rule is deprecated, use {rule:squid:MethodCyclomaticComplexity} or {rule:squid:ClassCyclomaticComplexity}
  instead.
</p>