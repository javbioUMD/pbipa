### Changes

* `v1.3.0`
  * purge_dups by default (unless "--no-purge-dups")
  * purge_dups on paf from pancake runs in parallel
  * Include "ipa_purge_dups"
  * "config_purge_map_opt"
* `v1.2.0`
  * Use htslib=1.10; stop pinning in Bioconda
  * Add "-e" to get_seqs in purge-dups
* `v1.1.2`
  * Retain elements with high copy numbers, and down-sample them.
  * Important bug-fix in nighthawk for some genomes (including HG).
  * Run purge_dups stage (no-op by default, hidden option).
  * Several other bug-fixes.
  * Known bug: If nighthawk hangs, simply kill the job and restart snakemake.
* `v1.0.5`
  * Use finer-grained sharding for phasing, polishing, and overlapping.
  * Other minor fixes.
* `v1.0.4`
  * Minor change to `ipa dist` defaults.
* `v1.0.3`
  * Minor fix
* `v0.0.2`
  * Bug fixes
* `v0.0.1`
  * Initial release
