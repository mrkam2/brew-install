Changelog
===========

**Also see [tools.deps changelog](https://github.com/clojure/tools.deps.alpha/blob/master/CHANGELOG.md)**

clj has both stable and prerelease versions. Current and former stable build are listed in **bold** and are (or were) available from the default [brew formula](https://github.com/clojure/brew-install/). Other versions can be obtained using versioned formulas only.

Prerelease versions:

* next
  * Update to tools.tools 0.3.3

**Current stable version:**

* **1.11.1.1435 on Dec 29, 2023**
  * **Update to tools.deps 1.18.1394**

Older versions (previous stable builds in bold):

* **1.11.1.1429 on Dec 4, 2023**
  * **Update to tools.deps 1.18.1374**
* **1.11.1.1420 on Dec 4, 2023**
  * **TDEPS-119 Unable to start CLI in write-protected project directory**
  * **Update to tools.deps 1.18.1370**
  * **Update to tools.tools 0.3.2**
* **1.11.1.1413 on Aug 26, 2023**
  * **No changes from prior**
* **1.11.1.1409 on Aug 25, 2023**
  * **No changes from prior**
* **1.11.1.1405 on Aug 22, 2023**
  * **GitHub releases now contain .sha256 files for binaries**
* **1.11.1.1386 on Aug 14, 2023**
  * **Release artifacts are now published to GitHub, and the download archive is used only as a mirror**
* **1.11.1.1369 on Aug 14, 2023**
  * **Download and mirroring wip**
* **1.11.1.1365 on Aug 13, 2023**
  * **Download and mirroring wip**
* **1.11.1.1347 on May 31, 2023**
  * **With -X or -T accept `-` as a trailing argument to read the remainder of args from stdin**
  * **On windows installer, hide progress bar on download**
  * **Update to tools.deps 0.18.1354**
  * **Update to tools.tools 0.3.1**
* **1.11.1.1273 on Apr 3, 2023**
  * **Change help text to point to -X:deps mvn-pom instead of -Spom**
  * **Switch to tools.deps 0.18.1335**
* **1.11.1.1267 on Mar 31, 2023**
  * **Switch to tools.deps 0.18.1331**
* **1.11.1.1262 on Mar 27, 2023**
  * **Switch to tools.deps 0.18.1317**
* **1.11.1.1257 on Mar 15, 2023**
  * **Switch to tools.deps 0.18.1308**
* **1.11.1.1252 on Mar 6, 2023**
  * **Switch to passing exec args via the basis :argmap**
  * **Function execution protocol support for -X/-T**
  * **Switch to tools.deps 0.17.1297**
* **1.11.1.1237 on Feb 27, 2023**
  * **Updates on -R and -C error messages**
* 1.11.1.1234 on Feb 27, 2023
  * Remove deprecated support for -R and -C
  * Clean up help text around repl supporting init-opts
  * Switch to tools.deps 0.16.1285
* **1.11.1.1224** on Feb 12, 2023**
  * **Switch to tools.deps 0.16.1281**
  * **TDEPS-236 Add rlwrap -m to clj for multiline editing**
* **1.11.1.1208 on Dec 11, 2022**
  * **Switch to tools.deps 0.16.1264**
  * **TDEPS-234 - Set -XX:-OmitStackTraceInFastThrow always**
* **1.11.1.1200 on Nov 14, 2022**
  * **Update to tools.deps.alpha 0.15.1254**
  * **Update to tools.tools v0.2.9**
* 1.11.1.1194 on Nov 14, 2022
  * Update to tools.deps.alpha 0.15.1250
* **1.11.1.1189 on Nov 2, 2022**
  * **TDEPS-233 bash script fixes from stale jar check changes**
  * **Add some missing items on help and man page**
* **1.11.1.1182 on Oct 24, 2022**
  * **Update to tools.deps.alpha 0.15.1244**
* 1.11.1.1177 on Oct 23, 2022
  * Fix bug in posix-install.sh
* 1.11.1.1174 on Oct 23, 2022
  * TDEPS-70 - Detect missing jar in classpath and recompute
  * TDEPS-200 - Clean up default user deps.edn
  * TDEPS-232 - Add more generic posix installer
  * Update to tools.deps.alpha 0.15.1237
* **1.11.1.1165 on Sep 18, 2022**
  * Extended the env var support to Windows
* 1.11.1.1161 on Sep 16, 2022
  * Use `$CLJ_JVM_OPTS` as jvm options on calls to internal tooling (making classpaths etc)
  * Use `$JAVA_OPTS` as jvm options on calls to user programs
* **1.11.1.1155 on Aug 5, 2022**
  * **Update to tools.deps.alpha 0.14.1222**
* **1.11.1.1149 on Jun 21, 2022**
  * **Update to tools.tools 0.2.8**
* 1.11.1.1145 on Jun 20, 2022
  * Update to tools.tools 0.2.7
  * Update to tools.deps.alpha 0.14.1212
* **1.11.1.1139 on Jun 16, 2022**
  * **Update to tools.tools 0.2.6**
  * **Update to tools.deps.alpha 0.14.1205**
* 1.11.1.1135 on Jun 16, 2022
  * Update to tools.deps.alpha 0.14.1200
* **1.11.1.1129 on Jun 12, 2022**
  * **Update to tools.deps.alpha 0.14.1194**
* **1.11.1.1124** on Jun 11, 2022
  * **Update to tools.deps.alpha 0.14.1189**
* **1.11.1.1119** on Jun 9, 2022
  * **Update to tools.deps.alpha 0.14.1185**
* **1.11.1.1113** on Apr 22, 2022
  * **Update to tools.deps.alpha 0.14.1178**
  * **Update to tools.build v0.8.1**
* **1.11.1.1105 on Apr 5, 2022**
  * **Update to clojure 1.11.1**
* **1.11.0.1100 on Mar 28, 2022**
  * **No changes from prior**
* 1.11.0.1097 on Mar 25, 2022
  * Update to clojure 1.11.0
* 1.10.3.1093 on Mar 21, 2022
  * Update to tools.deps.alpha 0.12.1162
* **1.10.3.1087 on Feb 28, 2022**
  * **Update to tools.deps.alpha 0.12.1158**
  * **Update to tools.build v0.8.0**
* 1.10.3.1082 on Feb 11, 2022
  * Update to tools.deps.alpha 0.12.1148
* **1.10.3.1075 on Feb 2, 2022**
  * **Update to tools.deps.alpha 0.12.1135**
* **1.10.3.1069 on Jan 26, 2022**
  * **Update to tools.deps.alpha 0.12.1120**
  * **Update to tools.tools v0.2.5**
  * **Add check to error on invocation of multiple exec functions**
* **1.10.3.1058 on Jan 4, 2022**
  * **Update to tools.deps.alpha 0.12.1109**
* 1.10.3.1053 on Dec 23, 2021
  * Update to tools.deps.alpha 0.12.1104
  * Update to tools.tools 0.2.3
  * Build with tools.build 0.7.3
* 1.10.3.1049 on Dec 22, 2021
  * Update to tools.deps.alpha 0.12.1098
* **1.10.3.1040 on Dec 1, 2021**
  * **Update to tools.deps.alpha 0.12.1084**
* 1.10.3.1036 on Nov 30, 2021
  * Update to tools.deps.alpha 0.12.1080
* **1.10.3.1029 on Nov 8, 2021**
  * **Update to tools.deps.alpha 0.12.1071**
  * **Update to tools.tools 0.2.2**
  * **Update to tools.build 0.6.3**
* **1.10.3.1020 on Nov 4, 2021**
  * **TDEPS-83 - invalidate cp cache when local manifest is missing**
  * **Update to tools.deps.alpha 0.12.1067**
* 1.10.3.1013 on Oct 30, 2021
  * Undo: -Stree no longer forces cache recompute
* 1.10.3.1007 on Oct 29, 2021
  * TDEPS-83 - invalidate cp cache when local lib manifests are stale
  * -Stree no longer forces cache recompute
  * Clean up exception handling for -X
  * Update to tools.deps.alpha 0.12.1063
* **1.10.3.998 on Oct 26, 2021**
  * **Remove `bottle :unneeded` from brew formulas**
  * **Update to tools.deps.alpha 0.12.1058**
  * **Update to tools.tools v0.2.1**
* **1.10.3.986 on Sept 22, 2021**
  * **Rebuild to actually include latest tools.deps.alpha**
  * **Update to tools.deps.alpha 0.12.1048**
* **1.10.3.981 on Sept 17, 2021**
  * **Update to tools.build v0.5.0**
* 1.10.3.976 on Sept 17, 2021
  * Update to tools.deps.alpha 0.12.1041
* **1.10.3.967 on Aug 31, 2021**
  * **Undo compilation of exec stub jar**
* 1.10.3.962 on Aug 30, 2021
  * Modify build to compile tools.deps entry points and exec stub jar
  * Update to tools.deps.alpha 0.12.1036
* 1.10.3.956 on Aug 27, 2021
  * Refine exec exceptions for missing namespace vs missing function in namespace
  * Update to tools.deps.alpha 0.12.1030
  * Build the Clojure CLI with tools.build, instead of Maven
* 1.10.3.949 on Aug 17, 2021
  * Update to tools.deps.alpha 0.12.1026
* **1.10.3.943 on Aug 10, 2021**
  * **Update to tools.deps.alpha 0.12.1019**
* 1.10.3.939 on Aug 9, 2021
  * Update to tools.deps.alpha 0.12.1013
* **1.10.3.933 on July 28, 2021**
  * **TDEPS-198 - on -X, don't use System/exit or shutdown-agents (but don't let agent threads block exit)**
* 1.10.3.929 on July 21, 2021
  * TDEPS-189 Port -T changes to Windows
  * Did some script cleanup in bash
* 1.10.3.920 on July 19, 2021
  * Fix regression in -X execution
* 1.10.3.916 on July 19, 2021
  * TDEPS-187 - redo how -X and -T get execute arg data
  * Update to tools.deps.alpha 0.12.1003
* 1.10.3.912 on July 15, 2021
  * On -X success, exit with (shutdown-agents) instead of System/exit
  * TDEPS-187 - pass -A aliases along with -Ttool
* 1.10.3.905 on July 9, 2021
  * Removing multi-function support from -X and -T for now
* 1.10.3.899 on July 9, 2021
  * New tools support
  * Added -T
  * Update to tools.deps.alpha 0.12.985
* 1.10.3.882 on June 15, 2021
  * On -X success, exit with System/exit to avoid hang from futures
  * Bind namespace resolution context around -X
* 1.10.3.875 on June 10, 2021
  * New: support for specifying multiple functions with -X with -> semantics
  * TDEPS-182 - Improve deprecation message to be more accurate
  * TDEPS-183 - Fix -Sdescribe output to be valid edn on Windows
  * Update to tools.deps.alpha 0.11.931
* **1.10.3.855 on May 25, 2021**
  * **Fix bug in applying :jvm-opts flags for -X on Windows**
* **1.10.3.849 on May 20, 2021**
  * **Add support for trailing map in -X calls**
  * **Update to tools.deps.alpha 0.11.922**
* **1.10.3.839 on May 12, 2021**
  * **Fix breakage in linux installer in 1.10.3.833**
* **1.10.3.833 on May 11, 2021**
  * **Clean up script variables**
* 1.10.3.829 on May 11, 2021
  * Update to tools.deps.alpha 0.11.918
* **1.10.3.822 on Apr 3, 2021**
  * **Update to tools.deps.alpha 0.11.910**
* **1.10.3.814 on Mar 11, 2021**
  * **Update to tools.deps.alpha 0.11.905**
* 1.10.3.810 on Mar 10, 2021
  * Use Clojure 1.10.3 by default
  * Update to tools.deps.alpha 0.11.901
* 1.10.2.805 on Mar 10, 2021
  * Update to tools.deps.alpha 0.10.895
* 1.10.2.801 on Mar 3, 2021
  * Update to tools.deps.alpha 0.10.889
* **1.10.2.796 on Feb 23, 2021**
  * **Update to tools.deps.alpha 0.9.884**
* **1.10.2.790 on Feb 19, 2021**
  * **Add -version and --version to print Clojure CLI version (to stderr and stdout respectively)**
* 1.10.2.786 on Feb 17, 2021
  * TDEPS-56 - fix main-opts and jvm-opts splitting on space
  * Update to tools.deps.alpha 0.9.876
* 1.10.2.781 on Feb 8, 2021
  * TDEPS-125 - use `JAVA_CMD` if set
  * Update to tools.deps.alpha 0.9.871
* **1.10.2.774 on Jan 26, 2021**
  * **Change default Clojure dep to 1.10.2**
  * **Update to tools.deps.alpha 0.9.863**
* 1.10.1.769 on Jan 26, 2021
  * Update to tools.deps.alpha 0.9.859
* **1.10.1.763 on Dec 10, 2020**
  * **Set exit code for -X ex-info error**
  * **Sync up cli syntax for aliases in help**
* **1.10.1.754 on Dec 7, 2020**
  * **Update to tools.deps.alpha 0.9.857**
  * **Update Windows scripts for new -Stree format**
* 1.10.1.749 on Dec 6, 2020
  * Update -Stree to use new tree printer
  * Update to tools.deps.alpha 0.9.853
* 1.10.1.745 on Dec 2, 2020
  * Update to tools.deps.alpha 0.9.847
* **1.10.1.739 on Nov 23, 2020**
  * **Update to tools.deps.alpha 0.9.840**
* 1.10.1.735 on Oct 30, 2020
  * Fix double throw in -X handling
  * Error if -A used without an alias
* **1.10.1.727 on Oct 21, 2020**
  * **Update to tools.deps.alpha 0.9.833**
* 1.10.1.723 on Oct 20, 2020
  * Fix `clj -X:deps tree` adding tools.deps.alpha to tree
  * Fix `clj -X:deps mvn-pom` adding tools.deps.alpha to pom deps
  * Fix `clj -X:deps git-resolve-tags` not working
  * Update to tools.deps.alpha 0.9.828
* **1.10.1.716 on Oct 10, 2020**
  * **Make edn reading tolerant of unknown tagged literals**
  * **Update to tools.deps.alpha 0.9.821**
* **1.10.1.708 on Oct 7, 2020**
  * **Update to tools.deps.alpha 0.9.816**
  * **TDEPS-168 - Fix error message handling for -X**
* **1.10.1.697 on Sep 25, 2020**
  * **Update to tools.deps.alpha 0.9.810**
* 1.10.1.693 on Sep 21, 2020
  * Update windows scripts for latest
  * Re-instate -Stree
  * Update to tools.deps.alpha 0.9.799
* 1.10.1.681 on Sep 11, 2020
  * Reinstate -R, -C, and -Spom as deprecated options
  * Update to tools.deps.alpha 0.9.795
* 1.10.1.672 on Sep 4, 2020
  * Add -P to prepare (download, cache classpath) without execution
  * Enhance -X and -M to support all argmaps
  * Enhance -X to support ad hoc function (-F removed)
  * Add new argmap keys for -X, :ns-default, :ns-aliases
  * Deprecate main args without -M
  * Remove -T, -R, -C, -O
  * In deps.edn, deprecate :deps/:paths in alias (change to :replace-deps/:replace-paths)
  * In deps.edn, change :fn/:args to :exec-fn/:exec-args
  * Move -Sdeps, -Spom, -Sresolve-tags into -X:deps invocations
  * Update to tools.deps.alpha 0.9.782
* 1.10.1.645 on Aug 9, 2020
  * Update to tools.deps.alpha 0.9.763
* 1.10.1.641 on Aug 8, 2020
  * Fix clj -X to make :args optional
* 1.10.1.636 on Aug 7, 2020
  * Fix clj -X arg handler in Windows
  * Update to tools.deps.alpha 0.9.759
* 1.10.1.619 on July 31, 2020
  * Error handling on -X :args
* 1.10.1.615 on July 30, 2020
  * Add -F function exec
  * Update to tools.deps.alpha 0.9.751
* 1.10.1.604 on July 28, 2020
  * Fix clj -X arg handler in Windows
* 1.10.1.600 on July 28, 2020
  * Fix clj -X handler in Windows
* 1.10.1.596 on July 28, 2020
  * Fix clj -X handler
* 1.10.1.590 on July 22, 2020
  * Added new execution mode to execute a function that takes an argmap via -X
  * Added support for using data stored in aliases as :paths
  * Added explicit "tool" step to cover :deps and :paths replacement, which can be passed via alias -T
  * Update to tools.deps.alpha 0.9.745
* **1.10.1.561 on July 17, 2020**
  * **Update to tools.deps.alpha 0.8.709**
* 1.10.1.554 on July 15, 2020
  * Update to tools.deps.alpha 0.8.702
* **1.10.1.547 on June 11, 2020**
  * **In Windows impl, use Write-Output when returning values like with -Spath**
  * **Update to tools.deps.alpha 0.8.695**
* 1.10.1.524-**1.10.1.536 on Feb 28, 2020**
  * Working on release automation, no changes
* **All releases older than this were stable releases**
* 1.10.1.510 on Feb 14, 2020
  * Update to tools.deps.alpha 0.8.677
* 1.10.1.507 on Jan 30, 2020
  * Update to tools.deps.alpha 0.8.661
  * Add -Sthreads option for concurrent downloads
  * Use -- to separate dep options and clojure.main options
* 1.10.1.502 on Jan 20, 2020
  * Report clj version in clj -h
  * Update to tools.deps.alpha 0.8.640
* 1.10.1.496 on Jan 16, 2020
  * Update to tools.deps.alpha 0.8.624
  * Remove -Xms on tool jvms
* 1.10.1.492 on Nov 25, 2019
  * Fix bad condition checking whether to write trace.edn
* 1.10.1.489 on Nov 20, 2019
  * Update to tools.deps.alpha 0.8.599
  * Join aliases in windows script without spaces
  * Added -Strace option
* 1.10.1.483 on Nov 4, 2019 
  * Update to tools.deps.alpha 0.8.584
  * Use homebrew ruby to minimize env conflicts
* 1.10.1.478 on Oct 18, 2019
  * Update to tools.deps.alpha 0.8.567
  * Report locations of user and project configs in -Sdescribe
* 1.10.1.472 on Oct 15, 2019
  * Update to tools.deps.alpha 0.8.559
* 1.10.1.469 on Aug 9, 2019 
  * Update to tools.deps.alpha 0.7.541
  * Add slf4j-nop which was removed from tools.deps.alpha
* 1.10.1.466 on July 17, 2019
  * Use min heap setting, not max, on internal tool calls
  * Update to tools.deps 0.7.527
* 1.10.1.462 on July 3, 2019
  * Rollback deps.edn install changes and install again
* 1.10.1.458 on June 29, 2019
  * Update to tools.deps 0.7.511
* 1.10.1.455 on June 28, 2019
  * Fix some manpage/help formatting
  * TDEPS-131 Fix bug tracker link in man page
  * Update to tools.deps 0.7.505
  * Stop installing deps.edn, now embedded in tools.deps
* 1.10.1.447 on June 6, 2019
  * Add new clj option to man page and clj help
* 1.10.1.445 on June 6, 2019
  * Change default Clojure to 1.10.1
* 1.10.0.442 on Mar 16, 2019
  * Update to tools.deps.alpha 0.6.496
  * Early release of Windows clj
* 1.10.0.414 on Feb 13, 2019
  * Update to tools.deps.alpha 0.6.488
* 1.10.0.411 on Jan 4, 2019
  * Update to tools.deps.alpha 0.6.480
* 1.10.0.408 on Jan 2, 2019 
  * Update to tools.deps.alpha 0.6.474
  * FIX TDEPS-82 - ensure -Sdescribe doesn't trigger resolution
* 1.10.0.403 on Dec 17, 2018
  * Changed default Clojure version to 1.10
* 1.9.0.397 on Oct 17, 2018
  * Update to tools.deps.alpha 0.5.460
* 1.9.0.394 on Sept 15, 2018
  * Update to tools.deps.alpha 0.5.452
* 1.9.0.391 on July 19, 2018
  * FIX TDEPS-77 - fix bad break character in rlwrap
  * FIX TDEPS-86 - use non-0 exit code in clj if rlwrap doesn't exist
  * FIX TDEPS-87 - change wording describing -Sdeps in help and man
* 1.9.0.381 on May 11, 2018
  * FIX TDEPS-76 - use exec for final Java invocation in script
  * NEW Convey lib map via Java system property
* 1.9.0.375 on Apr 14, 2018
  * FIX TDEPS-61 - switch to use Clojars CDN repo
  * FIX TDEPS-71 - better error if Java not installed
  * FIX TDEPS-65 - specify permissions on installed files
* 1.9.0.358 on Mar 2, 2018 
  * FIX linux-install - use mkdir -p to ensure parent dirs are created
  * FIX brew install - move man page installation from formula to install.sh
  * FIX TDEPS-45 - don't swipe -h flag if main aliases are in effect
  * FIX TDEPS-47 - use classpath cache with -Sdeps
* 1.9.0.348 on Feb 23, 2018
  * NEW Add --prefix to linux-install (INST-9)
  * NEW Add man page to installation (INST-18)
  * FIX Fix uberjar construction to avoid overlap of file and directory with same name
  * FIX Add missing license file
* 1.9.0.341 on Feb 21, 2018
  * CHANGE -Senv to -Sdescribe
* 1.9.0.338 on Feb 20, 2018
  * NEW -Senv - print edn for Clojure config, similar to -Sverbose info
  * NEW -Scp - provide a custom classpath and ignore classpath gen
* 1.9.0.326 on Feb 2, 2018
  * NEW -O - Java option aliases (append if multiple)
  * NEW -M - clojure.main option aliases (replace if multiple)
  * NEW -A - generic alias can combine any kind of alias and all are applied
  * FIX - if multiple alias switches supplied, they combine
  * FIX - whitespace in help fixed
* 1.9.0.315 on Jan 23, 2018
  * NEW -Stree to print dependency tree
  * NEW -Sdeps to supply a deps.edn on the command line as data
  * FIX bug with git deps using :deps/root writing File objects to libs files
* 1.9.0.309 on Jan 18, 2018
  * NEW -Spom emits dep exclusions and classifier
  * NEW pom file reader for local and git deps
  * FIX git deps now use :deps/root if specified
  * FIX major updates to improve transitive version selection
  * ENHANCE git version resolution uses stricter rules in comparison
  * ENHANCE dump stack on unexpected errors for debugging
* 1.9.0.302 on Jan 8, 2018
  * CHANGE git dep attributes (removed :rev, added :tag and :sha)
  * FIX Java 9 warning with -Spom
  * NEW -Sresolve-tags
* 1.9.0.297 on Jan 4, 2018
  * NEW git deps
  * NEW Updated -Spom to include repositories in the pom
* 1.9.0.273 on Dec 8, 2017
  * Initial release for 1.9
