## CHANGELOG

#### From version 5.8-lucjan-ll19 to version 5.13-lucjan-ll14-rc1 it is necessary to use the PDS CPU scheduler.
#### As of version 5.13-lucjan-ll15-rc1 it is again possible to choose between the BMQ CPU scheduler and the PDS CPU scheduler.
#### You must have GCC 11/Clang 12 to take advantages of the MZEN3/MSAPPHIRERAPIDS/MALDERLAKE/GENERIC_CPU2/GENERIC_CPU3/GENERIC_CPU4 optimizations. 
#### Otherwise the kernel will not compile properly.
#### The repository has been cleaned of old patch versions - patches for kernels 4.17-5.13 have been removed!

5.15-lucjan-ll96

- add ksmbd-Fix-buffer_check_err-kernel-doc-comment.patch
- add ksmbd-Fix-smb2_set_info_file-kernel-doc-comment.patch
- add ksmbd-Delete-an-invalid-argument-description-in-smb2.patch
- add ksmbd-Fix-smb2_get_name-kernel-doc-comment.patch
- add btrfs-fix-reserved-space-leak-on-log-tree-nodes-afte.patch
- add HID-holtek-fix-mouse-probing.patch

5.15-lucjan-ll95-rc1 --> 5.15-lucjan-ll95

5.15-lucjan-ll95-rc1

- sync with upstream (drop btrfs-Fix-memory-leak-in-__add_inode_ref.patch)
- sync with upstream (drop btrfs-fix-double-free-of-anon_dev-after-failure-to-c.patch)
- sync with upstream (drop btrfs-check-WRITE_ERR-when-trying-to-read-an-extent-.patch)

5.15-lucjan-ll94

- add AUFS 20211222

DROP 5.15-lucjan-ll94-rc1

5.15-lucjan-ll94-rc1

- sync with upstream (drop btrfs-Fix-memory-leak-in-__add_inode_ref.patch)
- sync with upstream (drop btrfs-fix-double-free-of-anon_dev-after-failure-to-c.patch)
- sync with upstream (drop btrfs-check-WRITE_ERR-when-trying-to-read-an-extent-.patch)

5.15-lucjan-ll93

- add Revert-block-bfq-update-pos_root-for-idle-bfq_queue-.patch
- add block-bfq-cleanup-bfq_bfqq_to_bfqg.patch
- add block-bfq-avoid-moving-bfqq-to-it-s-parent-bfqg.patch
- add block-bfq-don-t-move-oom_bfqq.patch
- add block-bfq-update-pos_root-for-idle-bfq_queue-in-bfq_.patch
- add block-bfq-Fix-bfq_group-error.patch
- add hwmon-nct6775-add-ROG-STRIX-B550-A-X570-I-GAMING.patch

DROP 5.15-lucjan-ll93-rc1

5.15-lucjan-ll93-rc1

- sync with upstream (drop btrfs-Fix-memory-leak-in-__add_inode_ref.patch)
- sync with upstream (drop btrfs-fix-double-free-of-anon_dev-after-failure-to-c.patch)
- sync with upstream (drop btrfs-check-WRITE_ERR-when-trying-to-read-an-extent-.patch)

5.15-lucjan-ll92

- add Revert-hwmon-nct6775-add-MAXIMUS-VII-HERO.patch
- add hwmon-nct6775-Additional-check-for-ChipID-before-ASU.patch
- add Add-module_version-macro.patch

5.15-lucjan-ll91

- drop drm-i915-Add-workaround-numbers-to-GEN7_COMMON_SLICE.patch
- drop x86-cpufeatures-add-AMD-Collaborative-Processor-Perf.patch
- drop x86-msr-add-AMD-CPPC-MSR-definitions.patch
- drop ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- drop ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- drop ACPI-CPPC-add-cppc-enable-register-function.patch
- drop cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- drop cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- drop cpufreq-amd-introduce-the-support-for-the-processors.patch
- drop cpufreq-amd-add-trace-for-amd-pstate-module.patch
- drop cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- drop cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- drop cpufreq-amd-add-amd-pstate-performance-attributes.patch
- drop cpupower-add-AMD-P-state-capability-flag.patch
- drop cpupower-add-the-function-to-check-amd-pstate-enable.patch
- drop cpupower-initial-AMD-P-state-capability.patch
- drop cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- drop cpupower-introduce-acpi-cppc-library.patch
- drop cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- drop cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- drop cpupower-move-print_speed-function-into-misc-helper.patch
- drop cpupower-print-amd-pstate-information-on-cpupower.patch
- drop Documentation-amd-pstate-add-amd-pstate-driver-intro.patch
- add x86-cpufeatures-add-AMD-Collaborative-Processor-Perf.patch
- add x86-msr-add-AMD-CPPC-MSR-definitions.patch
- add ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- add ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- add ACPI-CPPC-add-cppc-enable-register-function.patch
- add cpufreq-amd-pstate-introduce-a-new-AMD-P-State-drive.patch
- add cpufreq-amd-pstate-add-fast-switch-function-for-AMD-.patch
- add cpufreq-amd-pstate-introduce-the-support-for-the-pro.patch
- add cpufreq-amd-pstate-add-trace-for-AMD-P-State-module.patch
- add cpufreq-amd-pstate-add-boost-mode-support-for-AMD-P-.patch
- add cpufreq-amd-pstate-add-AMD-P-State-frequencies-attri.patch
- add cpufreq-amd-pstate-add-AMD-P-State-performance-attri.patch
- add Documentation-AMD-P-State-add-AMD-P-State-driver-int.patch
- add MAINTAINERS-add-AMD-P-State-driver-maintainer-entry.patch

5.15-lucjan-ll90

- add xfs-check-sb_meta_uuid-for-dabuf-buffer-recovery.patch

5.15-lucjan-ll89

- add btrfs-don-t-log-unnecessary-boundary-keys-when-loggi.patch
- add btrfs-put-initial-index-value-of-a-directory-in-a-co.patch
- add btrfs-stop-copying-old-dir-items-when-logging-a-dire.patch
- add btrfs-stop-trying-to-log-subdirectories-created-in-p.patch

5.15-lucjan-ll88

- add bfq-fix-use-after-free-in-bfq_dispatch_request.patch

5.15-lucjan-ll87

- add ksmbd-disable-SMB2_GLOBAL_CAP_ENCRYPTION-for-SMB-3.1.patch

5.15-lucjan-ll86

- add sched-alt-Optimize-loops-in-update_sched_rq_watermar.patch

5.15-lucjan-ll85

- add wait-Add-EXPORT_SYMBOL-for-__wake_up_pollfree.patch

5.15-lucjan-ll84

- add block-wbt-fix-negative-inflight-counter-when-remove-.patch
- add btrfs-Fix-memory-leak-in-__add_inode_ref.patch
- add btrfs-fix-double-free-of-anon_dev-after-failure-to-c.patch
- add btrfs-fix-invalid-delayed-ref-after-subvolume-creati.patch
- add btrfs-fix-warning-when-freeing-leaf-after-subvolume-.patch
- add btrfs-skip-transaction-commit-after-failure-to-creat.patch
- add btrfs-check-WRITE_ERR-when-trying-to-read-an-extent-.patch
- add btrfs-fix-missing-last-dir-item-offset-update-when-l.patch

5.15-lucjan-ll83-rc2 --> 5.15-lucjan-ll83

5.15-lucjan-ll83-rc2

- update mm-damon-simplify-stop-mechanism.patch

5.15-lucjan-ll83-rc1

- sync with upstream (drop mm-damon-core-Avoid-fake-load-reports-due-to-uninter.patch)
- sync with upstream (drop Revert-mm-damon-core-Avoid-fake-load-reports-due-to-.patch)
- sync with upstream (drop mm-damon-core-Fix-fake-load-reports-due-to-uninterru.patch)
- sync with upstream (drop timers-Implement-usleep_idle_range.patchd)
- sync with upstream (update mm-damon-simplify-stop-mechanism.patch)
- sync with upstream (update mm-damon-dbgfs-fix-missing-damon_dbgfs_lock.patch

5.15-lucjan-ll82

- add block-bfq-update-pos_root-for-idle-bfq_queue-in-bfq_.patch

5.15-lucjan-ll81

- add x86-sched-Decrease-further-the-priorities-of-SMT-sib.patch
- add sched-topology-Introduce-sched_group-flags.patch
- add sched-fair-Optimize-checking-for-group_asym_packing.patch
- add sched-fair-Provide-update_sg_lb_stats-with-sched-dom.patch
- add sched-fair-Carve-out-logic-to-mark-a-group-for-asymm.patch
- add sched-fair-Consider-SMT-in-ASYM_PACKING-load-balance.patch

5.15-lucjan-ll80

- add clearlinux-5.15-backport-patches-from-clearlinux-rep.patch

5.15-lucjan-ll79

- add Revert-netfilter-Add-full-cone-NAT-support.patch
- add Revert-drm-i915-Add-workaround-numbers-to-GEN7_COMMO.patch
- add amd-pmu-fix-s2idle-failures-on-certain-AMD-laptops.patch
- add netfilter-Add-full-cone-NAT-support.patch

5.15-lucjan-ll78-rc1 --> 5.15-lucjan-ll78

5.15-lucjan-ll78-rc1

- sync with upstream (drop Revert-drm-i915-Implement-Wa_1508744258.patch)

5.15-lucjan-ll77

- update futex-resync-from-gitlab.collabora.com.patch

DROP 5.15-lucjan-ll77-rc1

5.15-lucjan-ll77-rc1

- sync with upstream (drop Revert-drm-i915-Implement-Wa_1508744258.patch)

5.15-lucjan-ll76

- drop x86-MCE-AMD-EDAC-amd64-Move-address-translation-to-A.patch
- drop x86-amd_nb-EDAC-amd64-Move-DF-Indirect-Read-to-AMD64.patch
- drop EDAC-amd64-Don-t-use-naked-values-for-DF-registers.patch
- drop EDAC-amd64-Allow-for-DF-Indirect-Broadcast-reads.patch
- drop EDAC-amd64-Add-context-struct.patch
- drop EDAC-amd64-Define-Data-Fabric-operations.patch
- drop EDAC-amd64-Define-functions-for-DramOffset.patch
- drop EDAC-amd64-Define-function-to-read-DRAM-address-map-.patch
- drop EDAC-amd64-Define-function-to-find-interleaving-mode.patch
- drop EDAC-amd64-Define-function-to-denormalize-address.patch
- drop EDAC-amd64-Define-function-to-add-DRAM-base-and-hole.patch
- drop EDAC-amd64-Define-function-to-dehash-address.patch
- drop EDAC-amd64-Define-function-to-check-DRAM-limit-addre.patch
- drop EDAC-amd64-Remove-goto-statements.patch
- drop EDAC-amd64-Simplify-function-parameters.patch
- drop EDAC-amd64-Define-function-to-get-Interleave-Address.patch
- drop EDAC-amd64-Skip-denormalization-if-no-interleaving.patch
- drop EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- drop EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- drop EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- drop EDAC-amd64-Remove-unnecessary-assert.patch
- drop EDAC-amd64-Define-function-to-make-space-for-CS-ID.patch
- drop EDAC-amd64-Define-function-to-calculate-CS-ID.patch
- drop EDAC-amd64-Define-function-to-insert-CS-ID-into-addr.patch
- drop EDAC-amd64-Define-function-to-get-CS-Fabric-ID.patch
- drop EDAC-amd64-Define-function-to-find-shift-and-mask-va.patch
- drop EDAC-amd64-Update-CS-ID-calculation-to-match-referen.patch
- drop EDAC-amd64-Match-hash-function-to-reference-code.patch
- drop EDAC-amd64-Define-helper-function-to-get-interleave-.patch
- drop EDAC-amd64-Add-support-for-address-translation-on-DF.patch
- drop EDAC-amd64-Add-glossary-of-acronyms-for-address-tran.patch
- add x86-amd_nb-Add-support-for-northbridges-on-Aldebaran.patch
- add EDAC-mce_amd-Extract-node-id-from-MCA_IPID.patch
- add EDAC-amd64-Extend-family-ops-functions.patch
- add EDAC-amd64-Move-struct-fam_type-into-amd64_pvt-struc.patch
- add EDAC-amd64-Enumerate-memory-on-Aldebaran-GPU-nodes.patch
- add x86-MCE-AMD-EDAC-amd64-Move-address-translation-to-A.patch
- add x86-amd_nb-EDAC-amd64-Move-DF-Indirect-Read-to-AMD64.patch
- add EDAC-amd64-Allow-for-DF-Indirect-Broadcast-reads.patch
- add EDAC-amd64-Add-context-struct.patch
- add EDAC-amd64-Define-Data-Fabric-operations.patch
- add EDAC-amd64-Define-functions-for-DramOffset.patch
- add EDAC-amd64-Define-function-to-read-DRAM-address-map-.patch
- add EDAC-amd64-Define-function-to-find-interleaving-mode.patch
- add EDAC-amd64-Define-function-to-denormalize-address.patch
- add EDAC-amd64-Define-function-to-add-DRAM-base-and-hole.patch
- add EDAC-amd64-Define-function-to-dehash-address.patch
- add EDAC-amd64-Define-function-to-check-DRAM-limit-addre.patch
- add EDAC-amd64-Remove-goto-statements.patch
- add EDAC-amd64-Simplify-function-parameters.patch
- add EDAC-amd64-Define-function-to-get-Interleave-Address.patch
- add EDAC-amd64-Skip-denormalization-if-no-interleaving.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Remove-unnecessary-assert.patch
- add EDAC-amd64-Define-function-to-make-space-for-CS-ID.patch
- add EDAC-amd64-Define-function-to-calculate-CS-ID.patch
- add EDAC-amd64-Define-function-to-insert-CS-ID-into-addr.patch
- add EDAC-amd64-Define-function-to-get-CS-Fabric-ID.patch
- add EDAC-amd64-Define-function-to-find-shift-and-mask-va.patch
- add EDAC-amd64-Update-CS-ID-calculation-to-match-referen.patch
- add EDAC-amd64-Match-hash-function-to-reference-code.patch
- add EDAC-amd64-Define-function-to-get-interleave-address.patch
- add EDAC-amd64-Add-support-for-address-translation-on-DF.patch
- add EDAC-amd64-Add-glossary-of-acronyms-for-address-tran.patch
- add EDAC-amd64-Add-check-for-when-to-add-DRAM-base-and-h.patch
- add EDAC-amd64-Save-the-number-of-block-instances.patch
- add EDAC-amd64-Add-address-translation-support-for-DF3.5.patch

DROP 5.15-lucjan-ll76-rc1

5.15-lucjan-ll76-rc1

- sync with upstream (drop Revert-drm-i915-Implement-Wa_1508744258.patch)

5.15-lucjan-ll75

- update mm-5.15-protect-mappings-under-memory-pressure.patch

5.15-lucjan-ll74

- add lrng-5.15-update-to-the-latest-git-HEAD.patch

5.15-lucjan-ll73

- add x86-csum-Fix-initial-seed-for-odd-buffers.patch

5.15-lucjan-ll72

- drop x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- drop x86-msr-add-AMD-CPPC-MSR-definitions.patch
- drop ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- drop ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- drop ACPI-CPPC-add-cppc-enable-register-function.patch
- drop cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- drop cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- drop cpufreq-amd-introduce-the-support-for-the-processors.patch
- drop cpufreq-amd-add-trace-for-amd-pstate-module.patch
- drop cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- drop cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- drop cpufreq-amd-add-amd-pstate-performance-attributes.patch
- drop cpupower-add-AMD-P-state-capability-flag.patch
- drop cpupower-add-the-function-to-check-amd-pstate-enable.patch
- drop cpupower-initial-AMD-P-state-capability.patch
- drop cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- drop cpupower-introduce-acpi-cppc-library.patch
- drop cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- drop cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- drop cpupower-move-print_speed-function-into-misc-helper.patch
- drop cpupower-print-amd-pstate-information-on-cpupower.patch
- drop Documentation-amd-pstate-add-amd-pstate-driver-intro.patch
- add drm-i915-Add-workaround-numbers-to-GEN7_COMMON_SLICE.patch
- add x86-cpufeatures-add-AMD-Collaborative-Processor-Perf.patch
- add x86-msr-add-AMD-CPPC-MSR-definitions.patch
- add ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- add ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- add ACPI-CPPC-add-cppc-enable-register-function.patch
- add cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- add cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- add cpufreq-amd-introduce-the-support-for-the-processors.patch
- add cpufreq-amd-add-trace-for-amd-pstate-module.patch
- add cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- add cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- add cpufreq-amd-add-amd-pstate-performance-attributes.patch
- add cpupower-add-AMD-P-state-capability-flag.patch
- add cpupower-add-the-function-to-check-amd-pstate-enable.patch
- add cpupower-initial-AMD-P-state-capability.patch
- add cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- add cpupower-introduce-acpi-cppc-library.patch
- add cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- add cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- add cpupower-move-print_speed-function-into-misc-helper.patch
- add cpupower-print-amd-pstate-information-on-cpupower.patch
- add Documentation-amd-pstate-add-amd-pstate-driver-intro.patch

5.15-lucjan-ll71-rc1 --> 5.15-lucjan-ll71

5.15-lucjan-ll71-rc1

- add Revert-drm-i915-Implement-Wa_1508744258.patch

5.15-lucjan-ll70-rc1

- add ksmbd-fix-error-code-in-ndr_read_int32.patch
- add ksmbd-fix-uninitialized-symbol-pntsd_size.patch

5.15-lucjan-ll69-rc1

- add bfq-Fix-use-after-free-with-cgroups.patch

5.15-lucjan-ll68-rc1

- add hwmon-asus_wmi_ec_sensors-fix-array-overflow.patch
- add hwmon-asus_wmi_sensors-fix-an-array-overflow.patch

5.15-lucjan-ll67-rc1

- sync with upstream (drop staging-r8188eu-Fix-breakage-introduced-when-5G-code.patch)
- sync with upstream (drop igb-fix-netpoll-exit-with-traffic.patch)
- sync with upstream (drop ksmbd-downgrade-addition-info-error-msg-to-debug-in-.patch)
- sync with upstream (drop ksmbd-contain-default-data-stream-even-if-xattr-is-e.patch)
- sync with upstream (drop ksmbd-fix-memleak-in-get_file_stream_info.patch)
- sync with upstream (drop ksmbd-Fix-an-error-handling-path-in-smb2_sess_setup.patch)
- sync with upstream (drop scsi-sd-Fix-sd_do_mode_sense-buffer-length-handling.patch)
- sync with upstream (update ksmbd-remove-smb2_buf_length-in-smb2_hdr.patch)

5.15-lucjan-ll66-rc2

- add scsi-sd-Fix-sd_do_mode_sense-buffer-length-handling.patch

5.15-lucjan-ll66-rc1

- add spadfs-5.15-merge-v1.0.15.patch

5.15-lucjan-ll65-rc1

- sync with upstream (drop staging-r8188eu-Fix-breakage-introduced-when-5G-code.patch)
- sync with upstream (drop igb-fix-netpoll-exit-with-traffic.patch)
- sync with upstream (drop ksmbd-downgrade-addition-info-error-msg-to-debug-in-.patch)
- sync with upstream (drop ksmbd-contain-default-data-stream-even-if-xattr-is-e.patch)
- sync with upstream (drop ksmbd-fix-memleak-in-get_file_stream_info.patch)
- sync with upstream (drop ksmbd-Fix-an-error-handling-path-in-smb2_sess_setup.patch)
- sync with upstream (update ksmbd-remove-smb2_buf_length-in-smb2_hdr.patch)

5.15-lucjan-ll64-rc1

- add Revert-bfq-use-bfq_entity_to_bfqg-helper-method.patch
- add Revert-block-bfq-do-not-idle-if-only-one-cgroup-is-a.patch
- add Revert-block-bfq-counted-root-group-into-num_groups_.patch
- add block-bfq-add-new-apis-to-iterate-bfq-entities.patch
- add block-bfq-apply-news-apis-where-root-group-is-not-ex.patch
- add block-bfq-handle-the-case-when-for_each_entity-acces.patch
- add block-bfq-count-root-group-into-num_groups_with_pend.patch
- add block-bfq-do-not-idle-if-only-one-cgroup-is-activate.patch
- add block-bfq-only-count-group-that-the-bfq_queue-belong.patch
- add block-bfq-record-how-many-queues-have-pending-reques.patch
- add block-bfq-move-forward-__bfq_weights_tree_remove.patch
- add block-bfq-decrease-num_groups_with_pending_reqs-earl.patch

5.15-lucjan-ll63-rc2

- sync with upstream (drop ksmbd-Fix-an-error-handling-path-in-smb2_sess_setup.patch)
- sync with upstream (update ksmbd-remove-smb2_buf_length-in-smb2_hdr.patch)

5.15-lucjan-ll63-rc1

- sync with upstream (drop staging-r8188eu-Fix-breakage-introduced-when-5G-code.patch)
- sync with upstream (drop igb-fix-netpoll-exit-with-traffic.patch)
- sync with upstream (drop ksmbd-downgrade-addition-info-error-msg-to-debug-in-.patch)
- sync with upstream (drop ksmbd-contain-default-data-stream-even-if-xattr-is-e.patch)
- sync with upstream (drop ksmbd-fix-memleak-in-get_file_stream_info.patch)

5.15-lucjan-ll62-rc1

- add lg-laptop-Recognize-more-models.patch
- add bfq-Fix-spelling-mistake-tenative-tentative.patch
- add Revert-mm-damon-core-Avoid-fake-load-reports-due-to-.patch
- add timers-Implement-usleep_idle_range.patch
- add mm-damon-core-Fix-fake-load-reports-due-to-uninterru.patch

5.15-lucjan-ll61-rc1

- add x86-csum-Fix-compilation-error-for-UM.patch

5.15-lucjan-ll60-rc1

- add mm-damon-core-Avoid-fake-load-reports-due-to-uninter.patch
- add Revert-net-replace-WARN_ONCE-with-pr_warn_once.patch
- add sched-alt-Sync-42dc938a-sched-core-Mitigate-race-cpu.patch
- add sched-alt-Sync-b027789e-Prevent-dead-task-groups-fro.patch

5.15-lucjan-ll59-rc1

- sync with upstream (drop drm-amd-pm-avoid-duplicate-powergate-ungate-setting.patch)
- sync with upstream (drop mm-damon-dbgfs-use-__GFP_NOWARN-for-user-specified-s.patch)
- sync with upstream (drop mm-damon-dbgfs-fix-missed-use-of-damon_dbgfs_lock.patch)
- sync with upstream (update mm-damon-dbgfs-remove-unnecessary-variables.patch)
- sync with upstream (update mm-damon-dbgfs-add-adaptive_targets-list-check-befor.patch)
- sync with upstream (add mm-damon-dbgfs-fix-missing-damon_dbgfs_lock.patch)
- sync with upstream (add AUFS 20211124)

5.15-lucjan-ll58-rc1

- add hwmon-nct6775-Use-nct6775_-lock-function-pointers-in.patch
- add hwmon-nct6775-Implement-custom-lock-by-ACPI-mutex.patch
- add hwmon-nct6775-add-MAXIMUS-VII-HERO.patch
- add igb-fix-netpoll-exit-with-traffic.patch

5.15-lucjan-ll57-rc1

- sync with upstream (drop drm-amd-pm-avoid-duplicate-powergate-ungate-setting.patch)
- sync with upstream (drop mm-damon-dbgfs-use-__GFP_NOWARN-for-user-specified-s.patch)
- sync with upstream (drop mm-damon-dbgfs-fix-missed-use-of-damon_dbgfs_lock.patch)
- sync with upstream (update mm-damon-dbgfs-remove-unnecessary-variables.patch)
- sync with upstream (update mm-damon-dbgfs-add-adaptive_targets-list-check-befor.patch)
- sync with upstream (add mm-damon-dbgfs-fix-missing-damon_dbgfs_lock.patch)
- sync with upstream (add AUFS 20211124)

5.15-lucjan-ll56-rc1

- add fs-ntfs3-In-function-ntfs_set_acl_ex-do-not-change-i.patch
- add fs-ntfs3-Fix-fiemap-fix-shrink-file-size-to-remove-p.patch
- add fs-ntfs3-Check-new-size-for-limits.patch
- add fs-ntfs3-Update-valid-size-if-EIOCBQUEUED.patch

5.15-lucjan-ll55-rc1

- sync with upstream (drop drm-amd-pm-avoid-duplicate-powergate-ungate-setting.patch)
- sync with upstream (drop mm-damon-dbgfs-use-__GFP_NOWARN-for-user-specified-s.patch)
- sync with upstream (drop mm-damon-dbgfs-fix-missed-use-of-damon_dbgfs_lock.patch)
- sync with upstream (update mm-damon-dbgfs-remove-unnecessary-variables.patch)
- sync with upstream (update mm-damon-dbgfs-add-adaptive_targets-list-check-befor.patch)
- sync with upstream (add mm-damon-dbgfs-fix-missing-damon_dbgfs_lock.patch)
- sync with upstream (add AUFS 20211124)

5.15-lucjan-ll54-rc1

- add ksmbd-use-oid-registry-functions-to-decode-OIDs.patch
- add ksmbd-fix-memleak-in-get_file_stream_info.patch

5.15-lucjan-ll53-rc2

- sync with upstream (add AUFS 20211124)

5.15-lucjan-ll53-rc1

- sync with upstream (drop drm-amd-pm-avoid-duplicate-powergate-ungate-setting.patch)
- sync with upstream (drop mm-damon-dbgfs-use-__GFP_NOWARN-for-user-specified-s.patch)
- sync with upstream (drop mm-damon-dbgfs-fix-missed-use-of-damon_dbgfs_lock.patch)
- sync with upstream (update mm-damon-dbgfs-remove-unnecessary-variables.patch)
- sync with upstream (update mm-damon-dbgfs-add-adaptive_targets-list-check-befor.patch)
- sync with upstream (add mm-damon-dbgfs-fix-missing-damon_dbgfs_lock.patch)

5.15-lucjan-ll52-rc1

- add fs-ntfs3-Fix-some-memory-leaks-in-an-error-handling-.patch
- add fs-ntfs3-Keep-preallocated-only-if-option-prealloc-e.patch
- add fs-ntfs3-Restore-ntfs_xattr_get_acl-and-ntfs_xattr_s.patch
- add fs-ntfs3-Update-i_ctime-when-xattr-is-added.patch
- add fs-ntfs3-Optimize-locking-in-ntfs_save_wsl_perm.patch

5.15-lucjan-ll51-rc1

- sync with upstream (drop drm-amd-pm-avoid-duplicate-powergate-ungate-setting.patch)
- sync with upstream (drop mm-damon-dbgfs-use-__GFP_NOWARN-for-user-specified-s.patch)
- sync with upstream (drop mm-damon-dbgfs-fix-missed-use-of-damon_dbgfs_lock.patch)
- sync with upstream (update mm-damon-dbgfs-remove-unnecessary-variables.patch)
- sync with upstream (update mm-damon-dbgfs-add-adaptive_targets-list-check-befor.patch)
- sync with upstream (add mm-damon-dbgfs-fix-missing-damon_dbgfs_lock.patch)

5.15-lucjan-ll50-rc1

- drop x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- drop x86-msr-add-AMD-CPPC-MSR-definitions.patch
- drop ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- drop ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- drop ACPI-CPPC-add-cppc-enable-register-function.patch
- drop cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- drop cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- drop cpufreq-amd-add-acpi-cppc-function-as-the-backend-fo.patch
- drop cpufreq-amd-add-trace-for-amd-pstate-module.patch
- drop cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- drop cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- drop cpufreq-amd-add-amd-pstate-performance-attributes.patch
- drop cpupower-add-AMD-P-state-capability-flag.patch
- drop cpupower-add-the-function-to-check-amd-pstate-enable.patch
- drop cpupower-initial-AMD-P-state-capability.patch
- drop cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- drop cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- drop cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- drop cpupower-move-print_speed-function-into-misc-helper.patch
- drop cpupower-print-amd-pstate-information-on-cpupower.patch
- drop Documentation-amd-pstate-add-amd-pstate-driver-intro.patch
- add x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- add x86-msr-add-AMD-CPPC-MSR-definitions.patch
- add ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- add ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- add ACPI-CPPC-add-cppc-enable-register-function.patch
- add cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- add cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- add cpufreq-amd-introduce-the-support-for-the-processors.patch
- add cpufreq-amd-add-trace-for-amd-pstate-module.patch
- add cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- add cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- add cpufreq-amd-add-amd-pstate-performance-attributes.patch
- add cpupower-add-AMD-P-state-capability-flag.patch
- add cpupower-add-the-function-to-check-amd-pstate-enable.patch
- add cpupower-initial-AMD-P-state-capability.patch
- add cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- add cpupower-introduce-acpi-cppc-library.patch
- add cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- add cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- add cpupower-move-print_speed-function-into-misc-helper.patch
- add cpupower-print-amd-pstate-information-on-cpupower.patch
- add Documentation-amd-pstate-add-amd-pstate-driver-intro.patch

5.15-lucjan-ll49-rc1

- add ksmbd-downgrade-addition-info-error-msg-to-debug-in-.patch
- add ksmbd-contain-default-data-stream-even-if-xattr-is-e.patch
- add ksmbd-Fix-an-error-handling-path-in-smb2_sess_setup.patch
- add docs-filesystem-cifs-ksmbd-Fix-small-layout-issues.patch

5.15-lucjan-ll48-rc1

- add mm-damon-dbgfs-use-__GFP_NOWARN-for-user-specified-s.patch
- add mm-damon-dbgfs-fix-missed-use-of-damon_dbgfs_lock.patch

5.15-lucjan-ll47-rc1

- sync with upstream (drop PCI-MSI-Deal-with-devices-lying-about-their-MSI-mask.patch)
- sync with upstream (drop PCI-Add-MSI-masking-quirk-for-Nvidia-ION-AHCI.patch)

5.15-lucjan-ll46-rc1

- add Revert-btrfs-index-free-space-entries-on-size.patch
- add btrfs-index-free-space-entries-on-size.patch

5.15-lucjan-ll45-rc1

- sync with upstream (drop PCI-MSI-Deal-with-devices-lying-about-their-MSI-mask.patch)
- sync with upstream (drop PCI-Add-MSI-masking-quirk-for-Nvidia-ION-AHCI.patch)

5.15-lucjan-ll44-rc1

- add Bluetooth-btintel-Fix-bdaddress-comparison-with-garb.patch

5.15-lucjan-ll43-rc1

- add cpufreq-intel_pstate-ITMT-support-for-overclocked-sy.patch

5.15-lucjan-ll42-rc1

- add net-introduce-sk_forward_alloc_get.patch
- add tcp-move-inet-rx_dst_ifindex-to-sk-sk_rx_dst_ifindex.patch
- add ipv6-move-inet6_sk-sk-rx_dst_cookie-to-sk-sk_rx_dst_.patch
- add bpf-sockmap-Use-stricter-sk-state-checks-in-sk_looku.patch
- add tcp-minor-optimization-in-tcp_add_backlog.patch
- add tcp-remove-dead-code-in-__tcp_v6_send_check.patch
- add tcp-small-optimization-in-tcp_v6_send_check.patch
- add net-use-sk_is_tcp-in-more-places.patch
- add net-remove-sk_route_forced_caps.patch
- add net-remove-sk_route_nocaps.patch
- add ipv6-shrink-struct-ipcm6_cookie.patch
- add net-shrink-struct-sock-by-8-bytes.patch
- add net-forward_alloc_get-depends-on-CONFIG_MPTCP.patch
- add net-cache-align-tcp_memory_allocated-tcp_sockets_all.patch
- add tcp-small-optimization-in-tcp-recvmsg.patch
- add tcp-add-RETPOLINE-mitigation-to-sk_backlog_rcv.patch
- add tcp-annotate-data-races-on-tp-segs_in-and-tp-data_se.patch
- add tcp-annotate-races-around-tp-urg_data.patch
- add tcp-tp-urg_data-is-unlikely-to-be-set.patch
- add tcp-avoid-indirect-calls-to-sock_rfree.patch
- add tcp-defer-skb-freeing-after-socket-lock-is-released.patch
- add tcp-check-local-var-timeo-before-socket-fields-in-on.patch
- add tcp-do-not-call-tcp_cleanup_rbuf-if-we-have-a-backlo.patch
- add net-move-early-demux-fields-close-to-sk_refcnt.patch

5.15-lucjan-ll41-rc1

- drop prjc-5.15-sched-Fix-sched_fork-access-an-invalid-sch.patch
- add Project-C v5.15-r1
- add btrfs-only-use-max_extent_size-if-it-is-set-in-the-b.patch
- add Revert-btrfs-index-free-space-entries-on-size.patch
- add btrfs-index-free-space-entries-on-size.patch
- add x86-csum-rewrite-csum_partial.patch

5.15-lucjan-ll40-rc1

- add staging-r8188eu-Fix-breakage-introduced-when-5G-code.patch
- add PCI-MSI-Deal-with-devices-lying-about-their-MSI-mask.patch
- add PCI-Add-MSI-masking-quirk-for-Nvidia-ION-AHCI.patch
- add PCI-Add-more-NVIDIA-controllers-to-the-MSI-masking-q.patch
- add drm-amd-pm-avoid-duplicate-powergate-ungate-setting.patch
- add iommu-intel-do-deep-dma-unmapping-to-avoid-kernel-fl.patch

5.15-lucjan-ll39-rc1

- sync with upstream (update ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch)
- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)
- sync with upstream (drop ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch)
- sync with upstream (drop ksmbd-don-t-need-8byte-alignment-for-request-length-.patch)
- sync with upstream (drop ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch)
- add prjc-5.15-sched-Fix-sched_fork-access-an-invalid-sch.patch

5.15-lucjan-ll38-rc1

- add zstd-5.15-update-against-zstd-zstd-1.4.10.patch

5.15-lucjan-ll37-rc2

- drop prjc-5.15-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch
- add prjc-5.15-sched-Fix-sched_fork-access-an-invalid-sch.patch

5.15-lucjan-ll37-rc1

- sync with upstream (update ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch)
- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)
- sync with upstream (drop ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch)
- sync with upstream (drop ksmbd-don-t-need-8byte-alignment-for-request-length-.patch)
- sync with upstream (drop ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch)
- add prjc-5.15-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch

5.15-lucjan-ll36-rc1

- add lib-zstd-Remove-large-inline-functions-in-zstd_lazy..patch
- add lib-zstd-Remove-large-inline-functions-from-zstd_-do.patch

5.15-lucjan-ll35-rc1

- sync with upstream (update ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch)
- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)
- sync with upstream (drop ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch)
- sync with upstream (drop ksmbd-don-t-need-8byte-alignment-for-request-length-.patch)
- sync with upstream (drop ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch)
- add prjc-5.15-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch

5.15-lucjan-ll34-rc1

- add lib-zstd-Fix-unused-variable-warning.patch
- add lib-zstd-Don-t-inline-functions-in-zstd_opt.c.patch
- add lib-zstd-Don-t-add-O3-to-cflags.patch

5.15-lucjan-ll33-rc1

- sync with upstream (update ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch)
- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)
- sync with upstream (drop ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch)
- sync with upstream (drop ksmbd-don-t-need-8byte-alignment-for-request-length-.patch)
- sync with upstream (drop ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch)
- add prjc-5.15-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch

5.15-lucjan-ll32-rc1

- add hwmon-asus_wmi_sensors-create-separate-record.patch
- add Revert-hwmon-asus_wmi_sensors-support-ROG-STRIX-Z390.patch

5.15-lucjan-ll31-rc1

- sync with upstream (update ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch)
- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)
- sync with upstream (drop ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch)
- sync with upstream (drop ksmbd-don-t-need-8byte-alignment-for-request-length-.patch)
- sync with upstream (drop ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch)
- add prjc-5.15-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch

5.15-lucjan-ll30-rc1

- add hwmon-nct6775-mask-out-bank-number-in-nct6775_wmi_re.patch

5.15-lucjan-ll29-rc1

- sync with upstream (update ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch)
- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)
- sync with upstream (drop ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch)
- sync with upstream (drop ksmbd-don-t-need-8byte-alignment-for-request-length-.patch)
- sync with upstream (drop ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch)
- add prjc-5.15-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch

5.15-lucjan-ll28-rc1

- add hwmon-asus_wmi_sensors-support-ROG-STRIX-Z390-F-GAMI.patch

5.15-lucjan-ll27-rc2

- add prjc-5.15-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch

5.15-lucjan-ll27-rc1

- sync with upstream (update ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch)
- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)
- sync with upstream (drop ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch)
- sync with upstream (drop ksmbd-don-t-need-8byte-alignment-for-request-length-.patch)
- sync with upstream (drop ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch)

5.15-lucjan-ll26-rc1

- add AUFS 20211115
- update cpu-5.15-merge-graysky-s-patchset.patch

5.15-lucjan-ll25-rc2

- sync with upstream (update ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch)
- sync with upstream (drop ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch)
- sync with upstream (drop ksmbd-don-t-need-8byte-alignment-for-request-length-.patch)
- sync with upstream (drop ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch)

5.15-lucjan-ll25-rc1

- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)

5.15-lucjan-ll24-rc1

- add vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch

5.15-lucjan-ll23-rc1

- add mm-damon-grammar-s-works-work.patch
- add mm-damon-core-print-kdamond-start-log-in-debug-mode-.patch
- add mm-damon-remove-unnecessary-do_exit-from-kdamond.patch
- add mm-damon-needn-t-hold-kdamond_lock-to-print-pid-of-k.patch
- add mm-damon-core-nullify-pointer-ctx-kdamond-with-a-NUL.patch
- add mm-damon-core-account-age-of-target-regions.patch
- add mm-damon-core-implement-DAMON-based-Operation-Scheme.patch
- add mm-damon-vaddr-support-DAMON-based-Operation-Schemes.patch
- add mm-damon-dbgfs-support-DAMON-based-Operation-Schemes.patch
- add mm-damon-schemes-implement-statistics-feature.patch
- add mm-damon-dbgfs-allow-users-to-set-initial-monitoring.patch
- add mm-damon-dbgfs-test-add-a-unit-test-case-for-init_re.patch
- add mm-damon-vaddr-separate-commonly-usable-functions.patch
- add mm-damon-implement-primitives-for-physical-address-s.patch
- add mm-damon-dbgfs-support-physical-memory-monitoring.patch
- add mm-damon-vaddr-constify-static-mm_walk_ops.patch
- add mm-damon-dbgfs-remove-unnecessary-variables.patch
- add mm-damon-paddr-support-the-pageout-scheme.patch
- add mm-damon-schemes-implement-size-quota-for-schemes-ap.patch
- add mm-damon-schemes-skip-already-charged-targets-and-re.patch
- add mm-damon-schemes-implement-time-quota.patch
- add mm-damon-dbgfs-support-quotas-of-schemes.patch
- add mm-damon-schemes-prioritize-regions-within-the-quota.patch
- add mm-damon-vaddr-paddr-support-pageout-prioritization.patch
- add mm-damon-dbgfs-support-prioritization-weights.patch
- add mm-damon-schemes-activate-schemes-based-on-a-waterma.patch
- add mm-damon-dbgfs-support-watermarks.patch
- add mm-damon-introduce-DAMON-based-Reclamation-DAMON_REC.patch
- add mm-damon-remove-unnecessary-variable-initialization.patch
- add mm-damon-dbgfs-add-adaptive_targets-list-check-befor.patch
- add mm-damon-simplify-stop-mechanism.patch
- add mm-damon-fix-a-few-spelling-mistakes-in-comments-and.patch
- add mm-damon-remove-return-value-from-before_terminate-c.patch

5.15-lucjan-ll22-rc1

- drop scripts-package-builddeb-add-UPLOAD_DIR-and-NO_HEADE.patch
- drop build-fixes.patch
- drop enable-Werror-build.patch
- drop mm-export-dump_mm.patch
- drop mmap-locking-API-mmap_lock_is_contended-returns-a-bo.patch
- drop mmap-locking-API-name-the-return-values.patch
- drop do_anonymous_page-use-update_mmu_tlb.patch
- drop do_anonymous_page-reduce-code-duplication.patch
- drop mm-introduce-CONFIG_SPECULATIVE_PAGE_FAULT.patch
- drop x86-mm-define-ARCH_SUPPORTS_SPECULATIVE_PAGE_FAULT.patch
- drop mm-add-FAULT_FLAG_SPECULATIVE-flag.patch
- drop mm-add-do_handle_mm_fault.patch
- drop mm-add-per-mm-mmap-sequence-counter-for-speculative-.patch
- drop mm-rcu-safe-vma-freeing.patch
- drop mm-separate-mmap-locked-assertion-from-find_vma.patch
- drop x86-mm-attempt-speculative-mm-faults-first.patch
- drop mm-add-speculative_page_walk_begin-and-speculative_p.patch
- drop mm-refactor-__handle_mm_fault-handle_pte_fault.patch
- drop mm-implement-speculative-handling-in-__handle_mm_fau.patch
- drop mm-add-pte_map_lock-and-pte_spinlock.patch
- drop mm-implement-speculative-handling-in-do_anonymous_pa.patch
- drop mm-enable-speculative-fault-handling-through-do_anon.patch
- drop mm-implement-speculative-handling-in-do_numa_page.patch
- drop mm-enable-speculative-fault-handling-in-do_numa_page.patch
- drop mm-implement-speculative-handling-in-wp_page_copy.patch
- drop mm-implement-and-enable-speculative-fault-handling-i.patch
- drop mm-disable-speculative-faults-for-single-threaded-us.patch
- drop mm-disable-rcu-safe-vma-freeing-for-single-threaded-.patch
- drop mm-create-new-include-linux-vm_event.h-header-file.patch
- drop mm-anon-spf-statistics.patch
- drop arm64-mm-define-ARCH_SUPPORTS_SPECULATIVE_PAGE_FAULT.patch
- drop arm64-mm-attempt-speculative-mm-faults-first.patch
- drop powerpc-mm-define-ARCH_SUPPORTS_SPECULATIVE_PAGE_FAU.patch
- drop powerpc-mm-attempt-speculative-mm-faults-first.patch

5.15-lucjan-ll21-rc1

- sync with upstream (update android-export-symbold-and-enable-building-ashmem-an.patch)

5.15-lucjan-ll20-rc1

- update LL-Implement-ll-branding-v5.15.patch

5.15-lucjan-ll19-rc1

- sync with upstream (update android-export-symbold-and-enable-building-ashmem-an.patch)

5.15-lucjan-ll18-rc1

- drop mm-x86-arm64-add-arch_has_hw_pte_young.patch
- drop mm-x86-add-CONFIG_ARCH_HAS_NONLEAF_PMD_YOUNG.patch
- drop mm-vmscan.c-refactor-shrink_node.patch
- drop mm-multigenerational-lru-groundwork.patch
- drop mm-multigenerational-lru-protection.patch
- drop mm-multigenerational-lru-mm_struct-list.patch
- drop mm-multigenerational-lru-aging.patch
- drop mm-multigenerational-lru-eviction.patch
- drop mm-multigenerational-lru-user-interface.patch
- drop mm-multigenerational-lru-Kconfig.patch
- drop mm-multigenerational-lru-documentation.patch
- add mm-x86-arm64-add-arch_has_hw_pte_young.patch
- add mm-x86-add-CONFIG_ARCH_HAS_NONLEAF_PMD_YOUNG.patch
- add mm-vmscan.c-refactor-shrink_node.patch
- add mm-multigenerational-lru-groundwork.patch
- add mm-multigenerational-lru-mm_struct-list.patch
- add mm-multigenerational-lru-aging.patch
- add mm-multigenerational-lru-eviction.patch
- add mm-multigenerational-lru-user-interface.patch
- add mm-multigenerational-lru-Kconfig.patch
- add mm-multigenerational-lru-documentation.patch

5.15-lucjan-ll17-rc1

- sync with upstream (update android-export-symbold-and-enable-building-ashmem-an.patch)

5.15-lucjan-ll16-rc1

- update mm-multigenerational-lru-groundwork.patch
- update mm-multigenerational-lru-aging.patch
- update mm-multigenerational-lru-eviction.patch

5.15-lucjan-ll15-rc1

- drop Linux-Random-Number-Generator.patch
- drop LRNG-allocate-one-DRNG-instance-per-NUMA-node.patch
- drop LRNG-sysctls-and-proc-interface.patch
- drop LRNG-add-switchable-DRNG-support.patch
- drop LRNG-add-common-generic-hash-support.patch
- drop crypto-DRBG-externalize-DRBG-functions-for-LRNG.patch
- drop LRNG-add-SP800-90A-DRBG-extension.patch
- drop LRNG-add-kernel-crypto-API-PRNG-extension.patch
- drop crypto-move-Jitter-RNG-header-include-dir.patch
- drop LRNG-add-Jitter-RNG-fast-noise-source.patch
- drop LRNG-add-SP800-90B-compliant-health-tests.patch
- drop LRNG-add-interface-for-gathering-of-raw-entropy.patch
- drop LRNG-add-power-on-and-runtime-self-tests.patch
- drop lrng-5.15-update-to-the-latest-git-HEAD.patch
- add Linux-Random-Number-Generator.patch
- add LRNG-IRQ-entropy-source.patch
- add LRNG-sysctls-and-proc-interface.patch
- add LRNG-allocate-one-DRNG-instance-per-NUMA-node.patch
- add LRNG-CPU-entropy-source.patch
- add LRNG-add-switchable-DRNG-support.patch
- add LRNG-add-common-generic-hash-support.patch
- add crypto-DRBG-externalize-DRBG-functions-for-LRNG.patch
- add LRNG-add-SP800-90A-DRBG-extension.patch
- add LRNG-add-kernel-crypto-API-PRNG-extension.patch
- add crypto-move-Jitter-RNG-header-include-dir.patch
- add LRNG-add-Jitter-RNG-fast-noise-source.patch
- add LRNG-add-SP800-90B-compliant-health-tests.patch
- add LRNG-add-interface-for-gathering-of-raw-entropy.patch
- add LRNG-add-power-on-and-runtime-self-tests.patch

5.15-lucjan-ll14-rc1

- add ksmbd-switch-to-use-shared-definitions-where-availab.patch
- add ksmbd-use-the-common-definitions-for-NEGOTIATE_PROTO.patch
- add ksmbd-Move-more-definitions-into-the-shared-area.patch
- add ksmbd-Use-the-SMB3_Create-definitions-from-the-share.patch
- add cifs-Create-a-new-shared-file-holding-smb2-pdu-defin.patch
- add cifs-move-NEGOTIATE_PROTOCOL-definitions-out-into-th.patch
- add cifs-Move-more-definitions-into-the-shared-area.patch
- add cifs-Move-SMB2_Create-definitions-to-the-shared-area.patch

5.15-lucjan-ll13-rc1

- add scripts-package-builddeb-add-UPLOAD_DIR-and-NO_HEADE.patch
- add build-fixes.patch
- add enable-Werror-build.patch
- add mm-export-dump_mm.patch
- add mmap-locking-API-mmap_lock_is_contended-returns-a-bo.patch
- add mmap-locking-API-name-the-return-values.patch
- add do_anonymous_page-use-update_mmu_tlb.patch
- add do_anonymous_page-reduce-code-duplication.patch
- add mm-introduce-CONFIG_SPECULATIVE_PAGE_FAULT.patch
- add x86-mm-define-ARCH_SUPPORTS_SPECULATIVE_PAGE_FAULT.patch
- add mm-add-FAULT_FLAG_SPECULATIVE-flag.patch
- add mm-add-do_handle_mm_fault.patch
- add mm-add-per-mm-mmap-sequence-counter-for-speculative-.patch
- add mm-rcu-safe-vma-freeing.patch
- add mm-separate-mmap-locked-assertion-from-find_vma.patch
- add x86-mm-attempt-speculative-mm-faults-first.patch
- add mm-add-speculative_page_walk_begin-and-speculative_p.patch
- add mm-refactor-__handle_mm_fault-handle_pte_fault.patch
- add mm-implement-speculative-handling-in-__handle_mm_fau.patch
- add mm-add-pte_map_lock-and-pte_spinlock.patch
- add mm-implement-speculative-handling-in-do_anonymous_pa.patch
- add mm-enable-speculative-fault-handling-through-do_anon.patch
- add mm-implement-speculative-handling-in-do_numa_page.patch
- add mm-enable-speculative-fault-handling-in-do_numa_page.patch
- add mm-implement-speculative-handling-in-wp_page_copy.patch
- add mm-implement-and-enable-speculative-fault-handling-i.patch
- add mm-disable-speculative-faults-for-single-threaded-us.patch
- add mm-disable-rcu-safe-vma-freeing-for-single-threaded-.patch
- add mm-create-new-include-linux-vm_event.h-header-file.patch
- add mm-anon-spf-statistics.patch
- add arm64-mm-define-ARCH_SUPPORTS_SPECULATIVE_PAGE_FAULT.patch
- add arm64-mm-attempt-speculative-mm-faults-first.patch
- add powerpc-mm-define-ARCH_SUPPORTS_SPECULATIVE_PAGE_FAU.patch
- add powerpc-mm-attempt-speculative-mm-faults-first.patch

5.15-lucjan-ll12-rc1

- drop btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- drop btrfs-index-free-space-entries-on-size.patch
- drop btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- drop btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch
- drop btrfs-fix-lost-error-handling-when-replaying-directo.patch
- add btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- add btrfs-check-if-a-log-tree-exists-at-inode_logged.patch
- add btrfs-remove-no-longer-needed-checks-for-NULL-log-co.patch
- add btrfs-do-not-log-new-dentries-when-logging-that-a-ne.patch
- add btrfs-always-update-the-logged-transaction-when-logg.patch
- add btrfs-avoid-expensive-search-when-dropping-inode-ite.patch
- add btrfs-add-helper-to-truncate-inode-items-when-loggin.patch
- add btrfs-avoid-expensive-search-when-truncating-inode-i.patch
- add btrfs-avoid-attempt-to-drop-extents-when-logging-ino.patch
- add btrfs-avoid-search-for-logged-i_size-when-logging-in.patch
- add btrfs-do-not-commit-delayed-inode-when-logging-a-fil.patch
- add btrfs-remove-root-argument-from-btrfs_log_inode-and-.patch
- add btrfs-remove-redundant-log-root-assignment-from-log_.patch
- add btrfs-factor-out-the-copying-loop-of-dir-items-from-.patch
- add btrfs-insert-items-in-batches-when-logging-a-directo.patch
- add btrfs-keep-track-of-the-last-logged-keys-when-loggin.patch
- add btrfs-loop-only-once-over-data-sizes-array-when-inse.patch
- add btrfs-unexport-setup_items_for_insert.patch
- add btrfs-use-single-bulk-copy-operations-when-logging-d.patch
- add btrfs-index-free-space-entries-on-size.patch
- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch
- add btrfs-fix-lost-error-handling-when-replaying-directo.patch
- add btrfs-remove-root-argument-from-drop_one_dir_item.patch
- add btrfs-remove-root-argument-from-btrfs_unlink_inode.patch
- add btrfs-remove-root-argument-from-add_link.patch
- add btrfs-remove-root-argument-from-check_item_in_log.patch
- add btrfs-only-copy-dir-index-keys-when-logging-a-direct.patch
- add btrfs-remove-no-longer-needed-logic-for-replaying-di.patch

5.15-lucjan-ll11-rc1

- add ksmbd-set-unique-value-to-volume-serial-field-in-FS_.patch
- add ksmbd-remove-md4-leftovers.patch
- add ksmbd-remove-smb2_buf_length-in-smb2_hdr.patch
- add ksmbd-remove-smb2_buf_length-in-smb2_transform_hdr.patch
- add ksmbd-change-LeaseKey-data-type-to-u8-array.patch

5.15-lucjan-ll10-rc1

- update lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch

5.15-lucjan-ll9-rc1

- add blk-mq-sched-Don-t-reference-queue-tagset-in-blk_mq_.patch

5.15-lucjan-ll8-rc1

- add Disable-stack-conservation-for-GCC.patch

5.15-lucjan-ll7-rc1

- drop x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- drop x86-msr-add-AMD-CPPC-MSR-definitions.patch
- drop ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- drop ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- drop ACPI-CPPC-add-cppc-enable-register-function.patch
- drop cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- drop cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- drop cpufreq-amd-add-acpi-cppc-function-as-the-backend-fo.patch
- drop cpufreq-amd-add-trace-for-amd-pstate-module.patch
- drop cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- drop cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- drop cpufreq-amd-add-amd-pstate-performance-attributes.patch
- drop cpupower-add-AMD-P-state-capability-flag.patch
- drop cpupower-add-the-function-to-check-amd-pstate-enable.patch
- drop cpupower-initial-AMD-P-state-capability.patch
- drop cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- drop cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- drop cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- drop cpupower-move-print_speed-function-into-misc-helper.patch
- drop cpupower-print-amd-pstate-information-on-cpupower.patch
- drop Documentation-amd-pstate-add-amd-pstate-driver-intro.patch
- add x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- add x86-msr-add-AMD-CPPC-MSR-definitions.patch
- add ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- add ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- add ACPI-CPPC-add-cppc-enable-register-function.patch
- add cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- add cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- add cpufreq-amd-add-acpi-cppc-function-as-the-backend-fo.patch
- add cpufreq-amd-add-trace-for-amd-pstate-module.patch
- add cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- add cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- add cpufreq-amd-add-amd-pstate-performance-attributes.patch
- add cpupower-add-AMD-P-state-capability-flag.patch
- add cpupower-add-the-function-to-check-amd-pstate-enable.patch
- add cpupower-initial-AMD-P-state-capability.patch
- add cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- add cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- add cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- add cpupower-move-print_speed-function-into-misc-helper.patch
- add cpupower-print-amd-pstate-information-on-cpupower.patch
- add Documentation-amd-pstate-add-amd-pstate-driver-intro.patch

5.15-lucjan-ll6-rc1

- drop block-remove-plug-based-merging.patch
- update blk-mq-Use-shared-tags-for-shared-sbitmap-support.patch
- add blk-mq-Change-shared-sbitmap-naming-to-shared-tags.patch
- add blk-mq-Fix-blk_mq_tagset_busy_iter-for-shared-tags.patch

5.15-lucjan-ll5-rc1

- add blk-mq-Change-rqs-check-in-blk_mq_free_rqs.patch
- add block-Rename-BLKDEV_MAX_RQ-BLKDEV_DEFAULT_RQ.patch
- add blk-mq-Relocate-shared-sbitmap-resize-in-blk_mq_upda.patch
- add blk-mq-Invert-check-in-blk_mq_update_nr_requests.patch
- add blk-mq-sched-Rename-blk_mq_sched_alloc_-tags-map_and.patch
- add blk-mq-sched-Rename-blk_mq_sched_free_-requests-rqs.patch
- add blk-mq-Pass-driver-tags-to-blk_mq_clear_rq_mapping.patch
- add blk-mq-Don-t-clear-driver-tags-own-mapping.patch
- add blk-mq-Add-blk_mq_tag_update_sched_shared_sbitmap.patch
- add blk-mq-Add-blk_mq_alloc_map_and_rqs.patch
- add blk-mq-Refactor-and-rename-blk_mq_free_map_and_-requ.patch
- add blk-mq-Use-shared-tags-for-shared-sbitmap-support.patch
- add blk-mq-Stop-using-pointers-for-blk_mq_tags-bitmap-ta.patch

5.15-lucjan-ll4-rc1

- add mm-Disable-watermark-boosting-by-default.patch

5.15-lucjan-ll3-rc1

- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch

5.15-lucjan-ll2-rc1

- add bcachefs-5.15-introduce-bcachefs-patchset.patch

5.15-lucjan-ll1-rc1

- add x86-MCE-AMD-EDAC-amd64-Move-address-translation-to-A.patch
- add x86-amd_nb-EDAC-amd64-Move-DF-Indirect-Read-to-AMD64.patch
- add EDAC-amd64-Don-t-use-naked-values-for-DF-registers.patch
- add EDAC-amd64-Allow-for-DF-Indirect-Broadcast-reads.patch
- add EDAC-amd64-Add-context-struct.patch
- add EDAC-amd64-Define-Data-Fabric-operations.patch
- add EDAC-amd64-Define-functions-for-DramOffset.patch
- add EDAC-amd64-Define-function-to-read-DRAM-address-map-.patch
- add EDAC-amd64-Define-function-to-find-interleaving-mode.patch
- add EDAC-amd64-Define-function-to-denormalize-address.patch
- add EDAC-amd64-Define-function-to-add-DRAM-base-and-hole.patch
- add EDAC-amd64-Define-function-to-dehash-address.patch
- add EDAC-amd64-Define-function-to-check-DRAM-limit-addre.patch
- add EDAC-amd64-Remove-goto-statements.patch
- add EDAC-amd64-Simplify-function-parameters.patch
- add EDAC-amd64-Define-function-to-get-Interleave-Address.patch
- add EDAC-amd64-Skip-denormalization-if-no-interleaving.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Remove-unnecessary-assert.patch
- add EDAC-amd64-Define-function-to-make-space-for-CS-ID.patch
- add EDAC-amd64-Define-function-to-calculate-CS-ID.patch
- add EDAC-amd64-Define-function-to-insert-CS-ID-into-addr.patch
- add EDAC-amd64-Define-function-to-get-CS-Fabric-ID.patch
- add EDAC-amd64-Define-function-to-find-shift-and-mask-va.patch
- add EDAC-amd64-Update-CS-ID-calculation-to-match-referen.patch
- add EDAC-amd64-Match-hash-function-to-reference-code.patch
- add EDAC-amd64-Define-helper-function-to-get-interleave-.patch
- add EDAC-amd64-Add-support-for-address-translation-on-DF.patch
- add EDAC-amd64-Add-glossary-of-acronyms-for-address-tran.patch
- add android-export-symbold-and-enable-building-ashmem-an.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add bbr2-5.15-introduce-BBRv2.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O.patch
- add block-remove-plug-based-merging.patch
- add btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- add btrfs-index-free-space-entries-on-size.patch
- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch
- add btrfs-fix-lost-error-handling-when-replaying-directo.patch
- add CacULE-5.15.patch
- add ZEN-Disable-CacULE-by-default.patch
- add LL-Disable-RDB-by-default.patch
- add cacule-5.15-define-yield_mark-and-yield_unmark.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add port-print-fsync-count-for-bootchart.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add port-initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add init-wait-for-partition-and-retry-scan.patch
- add add-boot-option-to-allow-unsigned-modules.patch
- add enable-stateless-firmware-loading.patch
- add migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add Port-microcode-patches.patch
- add cpu-5.15-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add init-Kconfig-add-O1-flag.patch
- add Makefile-Turn-off-loop-vectorization-for-GCC-O3-opti.patch
- add x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- add x86-msr-add-AMD-CPPC-MSR-definitions.patch
- add ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- add ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- add ACPI-CPPC-add-cppc-enable-register-function.patch
- add cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- add cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- add cpufreq-amd-add-acpi-cppc-function-as-the-backend-fo.patch
- add cpufreq-amd-add-trace-for-amd-pstate-module.patch
- add cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- add cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- add cpufreq-amd-add-amd-pstate-performance-attributes.patch
- add cpupower-add-AMD-P-state-capability-flag.patch
- add cpupower-add-the-function-to-check-amd-pstate-enable.patch
- add cpupower-initial-AMD-P-state-capability.patch
- add cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- add cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- add cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- add cpupower-move-print_speed-function-into-misc-helper.patch
- add cpupower-print-amd-pstate-information-on-cpupower.patch
- add Documentation-amd-pstate-add-amd-pstate-driver-intro.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add scsi-sd-Optimal-I-O-size-should-be-a-multiple-of-rep.patch
- add iomap-avoid-deadlock-if-memory-reclaim-is-triggered-.patch
- add tty-Allow-setting-the-number-of-available-virtual-TT.patch
- add i2c-busses-Add-SMBus-capability-to-work-with-OpenRGB.patch
- add nvme-don-t-memset-the-normal-read-write-command.patch
- add futex-resync-from-gitlab.collabora.com.patch
- add hwmon-nct6775-Use-superio_-function-pointers-in-sio_.patch
- add hwmon-nct6775-Use-nct6775_-function-pointers-in-nct6.patch
- add hwmon-nct6775-Support-access-via-Asus-WMI.patch
- add hwmon-nct6775-Add-additional-ASUS-motherboards.patch
- add hwmon-nct6775-add-Pro-WS-X570-ACE.patch
- add hwmon-nct6775-Add-ProArt-X570-CREATOR-WIFI-support.patch
- add hwmon-asus_wmi_ec_sensors-Support-B550-Asus-WMI.patch
- add hwmon-asus_wmi_sensors-Support-X370-Asus-WMI.patch
- add ksmbd-use-ksmbd_req_buf_next-in-ksmbd_verify_smb_mes.patch
- add ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch
- add ksmdb-use-cmd-helper-variable-in-smb2_get_ksmbd_tcon.patch
- add ksmbd-Remove-redundant-flush_workqueue-calls.patch
- add ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch
- add ksmbd-don-t-need-8byte-alignment-for-request-length-.patch
- add zen-Allow-MSR-writes-by-default.patch
- add PCI-Add-Intel-remapped-NVMe-device-support.patch
- add Linux-Random-Number-Generator.patch
- add LRNG-allocate-one-DRNG-instance-per-NUMA-node.patch
- add LRNG-sysctls-and-proc-interface.patch
- add LRNG-add-switchable-DRNG-support.patch
- add LRNG-add-common-generic-hash-support.patch
- add crypto-DRBG-externalize-DRBG-functions-for-LRNG.patch
- add LRNG-add-SP800-90A-DRBG-extension.patch
- add LRNG-add-kernel-crypto-API-PRNG-extension.patch
- add crypto-move-Jitter-RNG-header-include-dir.patch
- add LRNG-add-Jitter-RNG-fast-noise-source.patch
- add LRNG-add-SP800-90B-compliant-health-tests.patch
- add LRNG-add-interface-for-gathering-of-raw-entropy.patch
- add LRNG-add-power-on-and-runtime-self-tests.patch
- add lrng-5.15-update-to-the-latest-git-HEAD.patch
- add mm-x86-arm64-add-arch_has_hw_pte_young.patch
- add mm-x86-add-CONFIG_ARCH_HAS_NONLEAF_PMD_YOUNG.patch
- add mm-vmscan.c-refactor-shrink_node.patch
- add mm-multigenerational-lru-groundwork.patch
- add mm-multigenerational-lru-protection.patch
- add mm-multigenerational-lru-mm_struct-list.patch
- add mm-multigenerational-lru-aging.patch
- add mm-multigenerational-lru-eviction.patch
- add mm-multigenerational-lru-user-interface.patch
- add mm-multigenerational-lru-Kconfig.patch
- add mm-multigenerational-lru-documentation.patch
- add mm-5.15-protect-mappings-under-memory-pressure.patch
- add genirq-i2c-Provide-and-use-generic_dispatch_irq.patch
- add x86-ACPI-cstate-Optimize-C3-entry-on-AMD-CPUs.patch
- add net-replace-WARN_ONCE-with-pr_warn_once.patch
- add mac80211-minstrel_ht-force-ampdu_len-to-be-0.patch
- add mac80211-rate-replace-WARN_ON-with-pr_warn.patch
- add mac80211-airtime-replace-WARN_ON_ONCE-with-pr_warn_o.patch
- add mac80211-rate-replace-WARN_ON_ONCE-with-pr_warn_once.patch
- add mac80211-rate-replace-WARN_ON-with-pr_warn.patch
- add security-Add-LSM-hook-at-the-point-where-a-task-gets.patch
- add security-brute-Define-a-LSM-and-add-sysctl-attribute.patch
- add security-brute-Detect-a-brute-force-attack.patch
- add security-brute-Mitigate-a-brute-force-attack.patch
- add security-brute-Notify-to-userspace-task-killed.patch
- add selftests-brute-Add-tests-for-the-Brute-LSM.patch
- add Documentation-Add-documentation-for-the-Brute-LSM.patch
- add MAINTAINERS-Add-a-new-entry-for-the-Brute-LSM.patch
- add x86-change-default-to-spec_store_bypass_disable-prct.patch
- add x86-deduplicate-the-spectre_v2_user-documentation.patch
- add v4l2loopback-5.15-merge-v0.12.5.patch
- add sched-autogroup-Add-kernel-parameter-and-config-opti.patch
- add netfilter-Add-full-cone-NAT-support.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add ZEN-Update-VHBA-driver.patch
- add lib-zstd-Add-kernel-specific-API.patch
- add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- add MAINTAINERS-Add-maintainer-entry-for-zstd.patch
- add kbuild-Add-make-tarzst-pkg-build-option.patch
- add lib-zstd-Add-cast-to-silence-clang-s-Wbitwise-instea.patch
- add kbuild-allow-setting-zstd-compression-level-for-modu.patch
- add kbuild-allow-setting-zstd-compression-level-for-kern.patch
- add kbuild-optimize-zstd-compression-settings.patch
- add kbuild-allow-setting-ultra-zstd-compression-level-fo.patch
- add kbuild-add-menu-for-ZSTD-module-compression-options.patch
- add block-elevator-remove-un-used-input-parameter-reques.patch
- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch
- add bfq-reset-entity-prio_changed-in-bfq_init_entity.patch
- add bfq-remove-unnecessary-BFQ_DEFAULT_GRP_IOPRIO.patch
- add block-bfq-the-delta_from_first-should-be-ns-rather-t.patch
- add block-bfq-fix-the-timeout-calculation-in-bfq_bfqq_ch.patch
- add block-bfq-counted-root-group-into-num_groups_with_pe.patch
- add block-bfq-do-not-idle-if-only-one-cgroup-is-activate.patch
- add bfq-use-bfq_entity_to_bfqg-helper-method.patch
- add block-Provide-icq-in-request-allocation-data.patch
- add bfq-Track-number-of-allocated-requests-in-bfq_entity.patch
- add bfq-Store-full-bitmap-depth-in-bfq_data.patch
- add bfq-Limit-number-of-requests-consumed-by-each-cgroup.patch
- add bfq-Limit-waker-detection-in-time.patch
- add bfq-Provide-helper-to-generate-bfqq-name.patch
- add bfq-Log-waker-detections.patch
- add bfq-Do-not-let-waker-requests-skip-proper-accounting.patch
- add block-bfq-Accept-symmetric-weight-adjustments.patch
- add block-bfq-honor-already-setup-queue-merges.patch
- add block-bfq-fix-UAF-problem-in-bfqg_stats_init.patch
- add elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add block-bfq-set-bfq-lucjan-branding.patch
- add Project-C v5.15-r0
- add sched-alt-Export-can_nice-symbol-for-Android-Binder-.patch
- add sched-alt-Add-MG-LRU-changes-through-ifdef-macro.patch
- add init-Kconfig-set-default-value-of-SCHED_PDS.patch
- add init-Kconfig-Restore-original-PDS-description.patch
- add LL-Add-.ll-version.patch
- add LL-Implement-ll-branding-v5.15.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add Disable-CPU_FREQ_GOV_SCHEDUTIL.patch
- add spadfs-5.15-merge-v1.0.14.patch
- add UKSM-for-5.15.patch
- add AUFS 20211018

5.14-lucjan-ll122

- drop prjc-5.14-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch
- add prjc-5.14-sched-Fix-sched_fork-access-an-invalid-sch.patch

5.14-lucjan-ll121-rc2 --> 5.14-lucjan-ll121

5.14-lucjan-ll121-rc2

- add prjc-5.14-sched-Add-wrapper-for-get_wchan-to-keep-ta.patch

5.14-lucjan-ll121-rc1

- sync with upstream (drop btrfs-fix-lost-error-handling-when-replaying-directo.patch)

5.14-lucjan-ll120-rc1 --> 5.14-lucjan-ll120

5.14-lucjan-ll120-rc1

- sync with upstream (drop ALSA-pcm-Check-mmap-capability-of-runtime-dma-buffer.patch)
- sync with upstream (drop ALSA-pci-cs46xx-Fix-set-up-buffer-type-properly.patch)
- sync with upstream (update android-export-symbold-and-enable-building-ashmem-an.patch)

5.14-lucjan-ll119

- drop x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- drop x86-msr-add-AMD-CPPC-MSR-definitions.patch
- drop ACPI-CPPC-Check-online-CPUs-for-determining-_CPC-is-.patch
- drop ACPI-CPPC-add-cppc-enable-register-function.patch
- drop cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- drop cpufreq-amd-add-fast-switch-function-for-amd-pstate-.patch
- drop cpufreq-amd-add-acpi-cppc-function-as-the-backend-fo.patch
- drop cpufreq-amd-add-trace-for-amd-pstate-module.patch
- drop cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- drop cpufreq-amd-add-amd-pstate-checking-support-check-at.patch
- drop cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- drop cpufreq-amd-add-amd-pstate-performance-attributes.patch
- drop cpupower-add-AMD-P-state-capability-flag.patch
- drop cpupower-add-the-function-to-check-amd-pstate-enable.patch
- drop cpupower-initial-AMD-P-state-capability.patch
- drop cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- drop cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- drop cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- drop cpupower-move-print_speed-function-into-misc-helper.patch
- drop cpupower-print-amd-pstate-information-on-cpupower.patch
- drop Documentation-amd-pstate-add-amd-pstate-driver-intro.patch
- add x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- add x86-msr-add-AMD-CPPC-MSR-definitions.patch
- add ACPI-CPPC-implement-support-for-SystemIO-registers.patch
- add ACPI-CPPC-Check-present-CPUs-for-determining-_CPC-is.patch
- add ACPI-CPPC-add-cppc-enable-register-function.patch
- add cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- add cpufreq-amd-add-fast-switch-function-for-amd-pstate.patch
- add cpufreq-amd-add-acpi-cppc-function-as-the-backend-fo.patch
- add cpufreq-amd-add-trace-for-amd-pstate-module.patch
- add cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- add cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- add cpufreq-amd-add-amd-pstate-performance-attributes.patch
- add cpupower-add-AMD-P-state-capability-flag.patch
- add cpupower-add-the-function-to-check-amd-pstate-enable.patch
- add cpupower-initial-AMD-P-state-capability.patch
- add cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- add cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- add cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- add cpupower-move-print_speed-function-into-misc-helper.patch
- add cpupower-print-amd-pstate-information-on-cpupower.patch
- add Documentation-amd-pstate-add-amd-pstate-driver-intro.patch

5.14-lucjan-ll118

- add Project-C v5.14-r4

5.14-lucjan-ll117

- add x86-change-default-to-spec_store_bypass_disable-prct.patch
- add x86-deduplicate-the-spectre_v2_user-documentation.patch

5.14-lucjan-ll116

- add ksmbd-use-ksmbd_req_buf_next-in-ksmbd_verify_smb_mes.patch
- add ksmbd-use-ksmbd_req_buf_next-in-ksmbd_smb2_check_mes.patch
- add ksmdb-use-cmd-helper-variable-in-smb2_get_ksmbd_tcon.patch
- add ksmbd-Remove-redundant-flush_workqueue-calls.patch
- add ksmbd-Fix-buffer-length-check-in-fsctl_validate_nego.patch
- add ksmbd-don-t-need-8byte-alignment-for-request-length-.patch

5.14-lucjan-ll115

- add nct6775-5.14-update-to-v9-ASUS-WMI-submission.patch

5.14-lucjan-ll114-rc1 --> 5.14-lucjan-ll114

5.14-lucjan-ll114-rc1

- sync with upstream (drop mm-secretmem-Fix-NULL-page-mapping-dereference-in-pa.patch)

5.14-lucjan-ll113

- add lib-zstd-Add-cast-to-silence-clang-s-Wbitwise-instea.patch

DROP 5.14-lucjan-ll113-rc1

5.14-lucjan-ll113-rc1

- sync with upstream (drop mm-secretmem-Fix-NULL-page-mapping-dereference-in-pa.patch)

5.14-lucjan-ll112

- add ZEN-Update-VHBA-driver.patch

DROP 5.14-lucjan-ll112-rc1

5.14-lucjan-ll112-rc1

- sync with upstream (drop mm-secretmem-Fix-NULL-page-mapping-dereference-in-pa.patch)

5.14-lucjan-ll111

- add x86-MCE-AMD-EDAC-amd64-Move-address-translation-to-A.patch
- add x86-amd_nb-EDAC-amd64-Move-DF-Indirect-Read-to-AMD64.patch
- add EDAC-amd64-Don-t-use-naked-values-for-DF-registers.patch
- add EDAC-amd64-Allow-for-DF-Indirect-Broadcast-reads.patch
- add EDAC-amd64-Add-context-struct.patch
- add EDAC-amd64-Define-Data-Fabric-operations.patch
- add EDAC-amd64-Define-functions-for-DramOffset.patch
- add EDAC-amd64-Define-function-to-read-DRAM-address-map-.patch
- add EDAC-amd64-Define-function-to-find-interleaving-mode.patch
- add EDAC-amd64-Define-function-to-denormalize-address.patch
- add EDAC-amd64-Define-function-to-add-DRAM-base-and-hole.patch
- add EDAC-amd64-Define-function-to-dehash-address.patch
- add EDAC-amd64-Define-function-to-check-DRAM-limit-addre.patch
- add EDAC-amd64-Remove-goto-statements.patch
- add EDAC-amd64-Simplify-function-parameters.patch
- add EDAC-amd64-Define-function-to-get-Interleave-Address.patch
- add EDAC-amd64-Skip-denormalization-if-no-interleaving.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Define-function-to-get-number-of-interlea.patch
- add EDAC-amd64-Remove-unnecessary-assert.patch
- add EDAC-amd64-Define-function-to-make-space-for-CS-ID.patch
- add EDAC-amd64-Define-function-to-calculate-CS-ID.patch
- add EDAC-amd64-Define-function-to-insert-CS-ID-into-addr.patch
- add EDAC-amd64-Define-function-to-get-CS-Fabric-ID.patch
- add EDAC-amd64-Define-function-to-find-shift-and-mask-va.patch
- add EDAC-amd64-Update-CS-ID-calculation-to-match-referen.patch
- add EDAC-amd64-Match-hash-function-to-reference-code.patch
- add EDAC-amd64-Define-helper-function-to-get-interleave-.patch
- add EDAC-amd64-Add-support-for-address-translation-on-DF.patch
- add EDAC-amd64-Add-glossary-of-acronyms-for-address-tran.patch
- add dmaengine-ptdma-Initial-driver-for-the-AMD-PTDMA.patch
- add dmaengine-ptdma-register-PTDMA-controller-as-a-DMA-r.patch
- add dmaengine-ptdma-Add-debugfs-entries-for-PTDMA.patch
- add iommu-amd-Selective-flush-on-unmap.patch
- add iommu-amd-Do-not-use-flush-queue-when-NpCache-is-on.patch
- add iommu-Improve-iommu_iotlb_gather-helpers.patch
- add iommu-Factor-iommu_iotlb_gather_is_disjoint-out.patch
- add iommu-amd-Tailored-gather-logic-for-AMD.patch
- add iommu-amd-Sync-once-for-scatter-gather-operations.patch
- add iommu-amd-Use-only-natural-aligned-flushes-in-a-VM.patch

DROP 5.14-lucjan-ll111-rc1

5.14-lucjan-ll111-rc1

- sync with upstream (drop mm-secretmem-Fix-NULL-page-mapping-dereference-in-pa.patch)

5.14-lucjan-ll110

- add cacule-5.14-define-yield_mark-and-yield_unmark.patch

5.14-lucjan-ll109

- add nct6775-5.14-update-to-v8-ASUS-WMI-submission.patch

5.14-lucjan-ll108

- add lrng-5.14-update-to-the-latest-git-HEAD.patch

5.14-lucjan-ll107

- add ksmbd-5.14-update-to-next-20211021.patch

5.14-lucjan-ll106

- add btrfs-fix-lost-error-handling-when-replaying-directo.patch

5.14-lucjan-ll105-rc1 --> 5.14-lucjan-ll105

5.14-lucjan-ll105-rc1

- sync with upstream (drop btrfs-unlock-the-newly-allocated-extent-buffer-in-bt.patch)
- add Revert-btrfs-update-comments-for-chunk-allocation-EN.patch
- add Revert-btrfs-fix-deadlock-between-chunk-allocation-a.patch
- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch

5.14-lucjan-ll104

- add LL-Disable-RDB-by-default.patch

DROP 5.14-lucjan-ll104-rc1

5.14-lucjan-ll104-rc1

- sync with upstream (drop btrfs-unlock-the-newly-allocated-extent-buffer-in-bt.patch)
- add Revert-btrfs-update-comments-for-chunk-allocation-EN.patch
- add Revert-btrfs-fix-deadlock-between-chunk-allocation-a.patch
- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch

5.14-lucjan-ll103

- add ksmbd-5.14-update-to-next-20211018.patch

DROP 5.14-lucjan-ll103-rc1

5.14-lucjan-ll103-rc1

- sync with upstream (drop btrfs-unlock-the-newly-allocated-extent-buffer-in-bt.patch)
- add Revert-btrfs-update-comments-for-chunk-allocation-EN.patch
- add Revert-btrfs-fix-deadlock-between-chunk-allocation-a.patch
- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch

5.14-lucjan-ll102

- add nvme-don-t-memset-the-normal-read-write-command.patch
- add mm-secretmem-Fix-NULL-page-mapping-dereference-in-pa.patch
- add block-remove-plug-based-merging.patch

DROP 5.14-lucjan-ll102-rc1

5.14-lucjan-ll102-rc1

- sync with upstream (drop btrfs-unlock-the-newly-allocated-extent-buffer-in-bt.patch)
- add Revert-btrfs-update-comments-for-chunk-allocation-EN.patch
- add Revert-btrfs-fix-deadlock-between-chunk-allocation-a.patch
- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch

5.14-lucjan-ll101

- add x86-cpufreatures-add-AMD-Collaborative-Processor-Per.patch
- add x86-msr-add-AMD-CPPC-MSR-definitions.patch
- add ACPI-CPPC-Check-online-CPUs-for-determining-_CPC-is-.patch
- add ACPI-CPPC-add-cppc-enable-register-function.patch
- add cpufreq-amd-introduce-a-new-amd-pstate-driver-to-sup.patch
- add cpufreq-amd-add-fast-switch-function-for-amd-pstate-.patch
- add cpufreq-amd-add-acpi-cppc-function-as-the-backend-fo.patch
- add cpufreq-amd-add-trace-for-amd-pstate-module.patch
- add cpufreq-amd-add-boost-mode-support-for-amd-pstate.patch
- add cpufreq-amd-add-amd-pstate-checking-support-check-at.patch
- add cpufreq-amd-add-amd-pstate-frequencies-attributes.patch
- add cpufreq-amd-add-amd-pstate-performance-attributes.patch
- add cpupower-add-AMD-P-state-capability-flag.patch
- add cpupower-add-the-function-to-check-amd-pstate-enable.patch
- add cpupower-initial-AMD-P-state-capability.patch
- add cpupower-add-the-function-to-get-the-sysfs-value-fro.patch
- add cpupower-add-amd-pstate-sysfs-definition-and-access-.patch
- add cpupower-enable-boost-state-support-for-amd-pstate-m.patch
- add cpupower-move-print_speed-function-into-misc-helper.patch
- add cpupower-print-amd-pstate-information-on-cpupower.patch
- add Documentation-amd-pstate-add-amd-pstate-driver-intro.patch

DROP 5.14-lucjan-ll101-rc1

5.14-lucjan-ll101-rc1

- sync with upstream (drop btrfs-unlock-the-newly-allocated-extent-buffer-in-bt.patch)
- add Revert-btrfs-update-comments-for-chunk-allocation-EN.patch
- add Revert-btrfs-fix-deadlock-between-chunk-allocation-a.patch
- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch

5.14-lucjan-ll100

- add AUFS 20211018

DROP 5.14-lucjan-ll100-rc1

5.14-lucjan-ll100-rc1

- sync with upstream (drop btrfs-unlock-the-newly-allocated-extent-buffer-in-bt.patch)
- add Revert-btrfs-update-comments-for-chunk-allocation-EN.patch
- add Revert-btrfs-fix-deadlock-between-chunk-allocation-a.patch
- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch

5.14-lucjan-ll99

- add Revert-block-bfq-Accept-symmetric-weight-adjustments.patch
- add block-bfq-Accept-symmetric-weight-adjustments.patch
- add block-bfq-honor-already-setup-queue-merges.patch
- add block-bfq-reset-last_bfqq_created-on-group-change.patch

5.14-lucjan-ll98

- add nct6775-5.14-update-to-v7-ASUS-WMI-submission.patch

5.14-lucjan-ll97

- add ksmbd-5.14-update-to-next-20211015.patch

5.14-lucjan-ll96

- add kbuild-Add-make-tarzst-pkg-build-option.patch

5.14-lucjan-ll95

- add nct6775-5.14-update-to-v6-ASUS-WMI-submission.patch

5.14-lucjan-ll94

- add Revert-bfq-use-bfq_entity_to_bfqg-helper-method.patch
- add Revert-block-bfq-do-not-idle-if-only-one-cgroup-is-a.patch
- add Revert-block-bfq-counted-root-group-into-num_groups_.patch
- add block-bfq-counted-root-group-into-num_groups_with_pe.patch
- add block-bfq-do-not-idle-if-only-one-cgroup-is-activate.patch
- add bfq-use-bfq_entity_to_bfqg-helper-method.patch

5.14-lucjan-ll93

- add Revert-bfq-use-bfq_entity_to_bfqg-helper-method.patch
- add Revert-block-bfq-consider-request-size-in-bfq_asymme.patch
- add Revert-block-bfq-add-support-to-record-request-size-.patch
- add Revert-block-bfq-do-not-idle-if-only-one-cgroup-is-a.patch
- add Revert-block-bfq-add-support-to-track-if-root_group-.patch
- add block-bfq-counted-root-group-into-num_groups_with_pe.patch
- add block-bfq-do-not-idle-if-only-one-cgroup-is-activate.patch
- add bfq-use-bfq_entity_to_bfqg-helper-method.patch

5.14-lucjan-ll92

- add units-Add-SI-metric-prefix-definitions.patch

5.14-lucjan-ll91

- add zstd-5.14-update-to-next-20211012.patch

5.14-lucjan-ll90

- add Revert-hwmon-nct6775-Use-custom-scale-for-ASUS-mothe.patch
- add Revert-hwmon-asus_wmi_sensors-remove-T_Sensor-for-Pr.patch
- add Revert-hwmon-asus_wmi_sensors-add-Pro-WS-X570-ACE.patch
- add Revert-hwmon-asus_wmi_sensors-Support-access-via-Asu.patch
- add hwmon-asus_wmi_ec_sensors-Support-B550-Asus-WMI.patch
- add hwmon-asus_wmi_sensors-Support-X370-Asus-WMI.patch

5.14-lucjan-ll89

- add block-bfq-fix-UAF-problem-in-bfqg_stats_init.patch

5.14-lucjan-ll88

- add fs-ntfs3-Keep-prealloc-for-all-types-of-files.patch
- add fs-ntfs3-Fix-memory-leak-if-fill_super-failed.patch
- add fs-ntfs3-Rework-ntfs_utf16_to_nls.patch
- add fs-ntfs3-Refactor-ntfs_readlink_hlp.patch
- add fs-ntfs3-Refactor-ntfs_create_inode.patch
- add fs-ntfs3-Refactor-ni_parse_reparse.patch
- add fs-ntfs3-Refactor-ntfs_read_mft.patch

5.14-lucjan-ll87

- add ksmbd-5.14-update-to-next-20211011.patch

5.14-lucjan-ll86

- update mm-x86-arm64-add-arch_has_hw_pte_young.patch
- update mm-x86-add-CONFIG_ARCH_HAS_NONLEAF_PMD_YOUNG.patch
- update mm-vmscan.c-refactor-shrink_node.patch
- update mm-multigenerational-lru-groundwork.patch
- update mm-multigenerational-lru-protection.patch
- update mm-multigenerational-lru-mm_struct-list.patch
- update mm-multigenerational-lru-aging.patch
- update mm-multigenerational-lru-eviction.patch
- update mm-multigenerational-lru-user-interface.patch
- update mm-multigenerational-lru-Kconfig.patch
- update mm-multigenerational-lru-documentation.patch
- update LL-Implement-ll-branding-v5.14.patch

5.14-lucjan-ll85

- add btrfs-fix-deadlock-between-chunk-allocation-and-chun.patch
- add btrfs-update-comments-for-chunk-allocation-ENOSPC-ca.patch

5.14-lucjan-ll84-rc1 --> 5.14-lucjan-ll84

5.14-lucjan-ll84-rc1

- sync with upstream (drop btrfs-fix-mount-failure-due-to-past-and-transient-de.patch)

5.14-lucjan-ll83

- add sched-alt-Fix-fails-on-x86-UP-5.14.9-build.patch

5.14-lucjan-ll82

- add ksmbd-5.14-update-to-next-20211008.patch

5.14-lucjan-ll81

- add Revert-ZEN-Add-OpenRGB-patches.patch
- add i2c-busses-Add-SMBus-capability-to-work-with-OpenRGB.patch
- add ksmbd-5.14-update-to-next-20211007.patch
- add mac80211-rate-replace-WARN_ON-with-pr_warn.patch
- update lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch

5.14-lucjan-ll80

- add Revert-block-Provide-icq-in-request-allocation-data.patch
- add Revert-bfq-Limit-number-of-requests-consumed-by-each.patch
- add Revert-bfq-Track-number-of-allocated-requests-in-bfq.patch
- add block-Provide-icq-in-request-allocation-data.patch
- add bfq-Track-number-of-allocated-requests-in-bfq_entity.patch
- add bfq-Store-full-bitmap-depth-in-bfq_data.patch
- add bfq-Limit-number-of-requests-consumed-by-each-cgroup.patch
- add bfq-Limit-waker-detection-in-time.patch
- add bfq-Provide-helper-to-generate-bfqq-name.patch
- add bfq-Log-waker-detections.patch
- add bfq-Do-not-let-waker-requests-skip-proper-accounting.patch

5.14-lucjan-ll79-rc1 --> 5.14-lucjan-ll79

5.14-lucjan-ll79-rc1

- sync with upstream (drop Revert-block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll78

- add fs-ntfs3-Use-available-posix_acl_release-instead-of-.patch
- add fs-ntfs3-Remove-locked-argument-in-ntfs_set_ea.patch
- add fs-ntfs3-Refactoring-of-ntfs_set_ea.patch
- add fs-ntfs3-Forbid-FALLOC_FL_PUNCH_HOLE-for-normal-file.patch
- add fs-ntfs3-Remove-unnecessary-functions.patch
- add ksmbd-missing-check-for-NULL-in-convert_to_nt_pathna.patch

DROP 5.14-lucjan-ll78-rc1

5.14-lucjan-ll78-rc1

- sync with upstream (drop Revert-block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll77

- update lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- drop zstd-fix-fall-through-warnings.patch

DROP 5.14-lucjan-ll77-rc1

5.14-lucjan-ll77-rc1

- sync with upstream (drop Revert-block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll76

- add mac80211-rate-replace-WARN_ON_ONCE-with-pr_warn_once.patch

5.14-lucjan-ll75

- add hwmon-nct6775-Use-superio_-function-pointers-in-sio_.patch
- add hwmon-nct6775-Use-nct6775_-function-pointers-in-nct6.patch
- add hwmon-nct6775-Support-access-via-Asus-WMI.patch
- add hwmon-nct6775-Add-additional-ASUS-motherboards.patch
- add hwmon-nct6775-Use-custom-scale-for-ASUS-motherboards.patch
- add hwmon-asus_wmi_sensors-Support-access-via-Asus-WMI.patch
- add hwmon-nct6775-add-Pro-WS-X570-ACE.patch
- add hwmon-asus_wmi_sensors-add-Pro-WS-X570-ACE.patch
- add hwmon-asus_wmi_sensors-remove-T_Sensor-for-Pro-WS-X5.patch

5.14-lucjan-ll74

- update LL-Implement-ll-branding-v5.14.patch

5.14-lucjan-ll73

- add mac80211-airtime-replace-WARN_ON_ONCE-with-pr_warn_o.patch

5.14-lucjan-ll72

- add Revert-block-bfq-honor-already-setup-queue-merges.patch

5.14-lucjan-ll71

- add ksmbd-5.14-update-to-next-20211001.patch

5.14-lucjan-ll70

- add fs-ntfs3-Reject-mount-if-boot-s-cluster-size-media-s.patch
- add fs-ntfs3-Refactoring-of-ntfs_init_from_boot.patch
- add fs-ntfs3-Check-for-NULL-if-ATTR_EA_INFO-is-incorrect.patch

5.14-lucjan-ll69

- add btrfs-index-free-space-entries-on-size.patch

5.14-lucjan-ll68

- add ksmbd-5.14-update-to-next-20210930.patch

5.14-lucjan-ll67-rc1 --> 5.14-lucjan-ll67

5.14-lucjan-ll67-rc1

- sync with upstream (drop atlantic-Fix-issue-in-the-pm-resume-flow.patch)
- sync with upstream (drop blk-cgroup-fix-UAF-by-grabbing-blkcg-lock-before-des.patch)
- sync with upstream (resync ZEN-intel-pstate-Implement-enable-parameter.patch)

5.14-lucjan-ll66

- add Project-C v5.14-r3

5.14-lucjan-ll65

- add ksmbd-5.14-update-to-next-20210927.patch

5.14-lucjan-ll64-rc1 --> 5.14-lucjan-ll64

5.14-lucjan-ll64-rc1

- add atlantic-Fix-issue-in-the-pm-resume-flow.patch
- add SUNRPC-Simplify-socket-shutdown-when-not-reusing-TCP.patch
- add SUNRPC-Tweak-TCP-socket-shutdown-in-the-RPC-client.patch

DROP 5.14-lucjan-ll63-rc1

5.14-lucjan-ll63-rc1

- sync with upstream (drop SUNRPC-don-t-pause-on-incomplete-allocation.patch)

5.14-lucjan-ll62

- add mac80211-rate-replace-WARN_ON-with-pr_warn.patch

DROP 5.14-lucjan-ll62-rc1

5.14-lucjan-ll62-rc1

- sync with upstream (drop SUNRPC-don-t-pause-on-incomplete-allocation.patch)

5.14-lucjan-ll61

- add fs-ntfs3-Fix-logical-error-in-ntfs_create_inode.patch
- add fs-ntfs3-Move-ni_lock_dir-and-ni_unlock-into-ntfs_cr.patch
- add fs-ntfs3-Refactor-ntfs_get_acl_ex-for-better-readabi.patch
- add fs-ntfs3-Pass-flags-to-ntfs_set_ea-in-ntfs_set_acl_e.patch
- add fs-ntfs3-Change-posix_acl_equiv_mode-to-posix_acl_up.patch
- add fs-ntfs3-Refactoring-lock-in-ntfs_init_acl.patch

DROP 5.14-lucjan-ll61-rc1

5.14-lucjan-ll61-rc1

- sync with upstream (drop SUNRPC-don-t-pause-on-incomplete-allocation.patch)

5.14-lucjan-ll60

- add ksmbd-5.14-update-to-next-20210924.patch

5.14-lucjan-ll59

- add ksmbd-5.14-update-to-the-latest-git-HEAD.patch

5.14-lucjan-ll58

- add fs-ntfs3-Remove-a-useless-test-in-indx_find.patch
- add fs-ntfs3-Remove-a-useless-shadowing-variable.patch
- add fs-ntfs3-Remove-deprecated-mount-options-nls.patch

5.14-lucjan-ll57

- add ksmbd-5.14-update-to-the-latest-git-HEAD.patch

5.14-lucjan-ll56

- add Bluetooth-btusb-Add-support-for-IMC-Networks-Mediate.patch
- add Bluetooth-btusb-Add-support-for-Foxconn-Mediatek-Chi.patch
- add ALSA-pcm-Check-mmap-capability-of-runtime-dma-buffer.patch
- add ALSA-pci-rme-Set-up-buffer-type-properly.patch
- add ALSA-pci-cs46xx-Fix-set-up-buffer-type-properly.patch

5.14-lucjan-ll55

- add sched-alt-add-missing-sanity-check-in-migrate_pendin.patch

5.14-lucjan-ll54

- add ksmbd-5.14-update-to-the-latest-git-HEAD.patch

5.14-lucjan-ll53-rc1 --> 5.14-lucjan-ll53

5.14-lucjan-ll53-rc1

- sync with upstream (drop block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll52

- add ksmbd-5.14-update-to-the-latest-git-HEAD.patch

DROP 5.14-lucjan-ll52-rc1

5.14-lucjan-ll52-rc1

- sync with upstream (drop block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll51

- add fs-ntfs3-Fix-insertion-of-attr-in-ni_ins_attr_ext.patch
- add fs-ntfs3-Change-max-hardlinks-limit-to-4000.patch
- add fs-ntfs3-Add-sync-flag-to-ntfs_sb_write_run-and-al_u.patch

DROP 5.14-lucjan-ll51-rc1

5.14-lucjan-ll51-rc1

- sync with upstream (drop block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll50

- add sched-alt-Fix-cgroup-time-accounting.patch

DROP 5.14-lucjan-ll50-rc1

5.14-lucjan-ll50-rc1

- sync with upstream (drop block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll49

- add ksmbd-log-that-server-is-experimental-at-module-load.patch
- add Revert-ksmbd-use-LOOKUP_NO_SYMLINKS-flags-for-defaul.patch
- add ksmbd-remove-follow-symlinks-support.patch
- add Revert-ksmbd-add-request-buffer-validation-in-smb2_s.patch
- add ksmbd-add-request-buffer-validation-in-smb2_set_info.patch

DROP 5.14-lucjan-ll49-rc1

5.14-lucjan-ll49-rc1

- sync with upstream (drop block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll48

- add fs-ntfs3-Fix-wrong-error-message-Logfile-UpCase.patch
- add fs-ntfs3-Change-EINVAL-to-ENOMEM-when-d_make_root-fa.patch
- add fs-ntfs3-Remove-impossible-fault-condition-in-fill_s.patch
- add fs-ntfs3-Return-straight-without-goto-in-fill_super.patch
- add fs-ntfs3-Remove-unnecessary-variable-loading-in-fill.patch
- add fs-ntfs3-Use-sb-instead-of-sbi-sb-in-fill_super.patch
- add fs-ntfs3-Remove-tmp-var-is_ro-in-ntfs_fill_super.patch
- add fs-ntfs3-Remove-tmp-pointer-bd_inode-in-fill_super.patch
- add fs-ntfs3-Remove-tmp-pointer-upcase-in-fill_super.patch
- add fs-ntfs3-Initialize-pointer-before-use-place-in-fill.patch
- add fs-ntfs3-Initiliaze-sb-blocksize-only-in-one-place-r.patch
- add Doc-fs-ntfs3-Fix-rst-format-and-make-it-cleaner.patch
- add fs-ntfs3-Fix-a-memory-leak-on-object-opts.patch

DROP 5.14-lucjan-ll48-rc1

5.14-lucjan-ll48-rc1

- sync with upstream (drop block-bfq-honor-already-setup-queue-merges.patch)

5.14-lucjan-ll47

- add Project-C v5.14-r2

5.14-lucjan-ll46

- add lrng-5.14-update-to-v42.patch

5.14-lucjan-ll45

- add ksmbd-add-validation-for-FILE_FULL_EA_INFORMATION-of.patch
- add ksmbd-add-request-buffer-validation-in-smb2_set_info.patch
- add ksmbd-add-validation-in-smb2_ioctl.patch
- add ksmbd-add-buffer-validation-for-SMB2_CREATE_CONTEXT.patch
- add ksmbd-use-LOOKUP_NO_SYMLINKS-flags-for-default-looku.patch
- add ksmbd-add-default-data-stream-name-in-FILE_STREAM_IN.patch

5.14-lucjan-ll44

- add SUNRPC-don-t-pause-on-incomplete-allocation.patch

5.14-lucjan-ll43-rc1 --> 5.14-lucjan-ll43

5.14-lucjan-ll43-rc1

- sync with upstream (drop block-bfq-fix-bfq_set_next_ioprio_data.patch)
- sync with upstream (drop btrfs-wait-on-async-extents-when-flushing-delalloc.patch)
- sync with upstream (drop btrfs-use-delalloc_bytes-to-determine-flush-amount-f.patch)
- sync with upstream (drop btrfs-wake-up-async_delalloc_pages-waiters-after-sub.patch)
- sync with upstream (drop btrfs-do-not-pin-logs-too-early-during-renames.patch)
- sync with upstream (drop btrfs-reduce-the-preemptive-flushing-threshold-to-90.patch)
- sync with upstream (drop watchdog-iTCO_wdt-Fix-detection-of-SMI-off-case.patch)
- add btrfs-unlock-the-newly-allocated-extent-buffer-in-bt.patch

5.14-lucjan-ll42

- update LL-Implement-ll-branding-v5.14.patch

DROP 5.14-lucjan-ll42-rc1

5.14-lucjan-ll42-rc1

- add btrfs-unlock-the-newly-allocated-extent-buffer-in-bt.patch

5.14-lucjan-ll42-rc1

- sync with upstream (drop block-bfq-fix-bfq_set_next_ioprio_data.patch)
- sync with upstream (drop btrfs-wait-on-async-extents-when-flushing-delalloc.patch)
- sync with upstream (drop btrfs-use-delalloc_bytes-to-determine-flush-amount-f.patch)
- sync with upstream (drop btrfs-wake-up-async_delalloc_pages-waiters-after-sub.patch)
- sync with upstream (drop btrfs-do-not-pin-logs-too-early-during-renames.patch)
- sync with upstream (drop btrfs-reduce-the-preemptive-flushing-threshold-to-90.patch)
- sync with upstream (drop watchdog-iTCO_wdt-Fix-detection-of-SMI-off-case.patch)

5.14-lucjan-ll41

- add ksmbd-transport_rdma-Don-t-include-rwlock.h-directly.patch
- add ksmbd-prevent-out-of-share-access.patch

DROP 5.14-lucjan-ll41-rc1

5.14-lucjan-ll41-rc1

- sync with upstream (drop block-bfq-fix-bfq_set_next_ioprio_data.patch)
- sync with upstream (drop btrfs-wait-on-async-extents-when-flushing-delalloc.patch)
- sync with upstream (drop btrfs-use-delalloc_bytes-to-determine-flush-amount-f.patch)
- sync with upstream (drop btrfs-wake-up-async_delalloc_pages-waiters-after-sub.patch)
- sync with upstream (drop btrfs-do-not-pin-logs-too-early-during-renames.patch)
- sync with upstream (drop btrfs-reduce-the-preemptive-flushing-threshold-to-90.patch)
- sync with upstream (drop watchdog-iTCO_wdt-Fix-detection-of-SMI-off-case.patch)

5.14-lucjan-ll40

- add fs-ntfs3-Remove-before-constant-in-ni_insert_residen.patch
- add fs-ntfs3-Place-Comparisons-constant-right-side-of-th.patch
- add fs-ntfs3-Remove-braces-from-single-statment-block.patch
- add fs-ntfs3-Remove-tabs-before-spaces-from-comment.patch
- add fs-ntfs3-Fix-ntfs_look_for_free_space-does-only-repo.patch
- add fs-ntfs3-Remove-always-false-condition-check.patch
- add fs-ntfs3-Use-clamp-max-macros-instead-of-comparisons.patch
- add fs-ntfs3-Use-min-max-macros-instated-of-ternary-oper.patch

DROP 5.14-lucjan-ll40-rc1

5.14-lucjan-ll40-rc1

- sync with upstream (drop block-bfq-fix-bfq_set_next_ioprio_data.patch)
- sync with upstream (drop btrfs-wait-on-async-extents-when-flushing-delalloc.patch)
- sync with upstream (drop btrfs-use-delalloc_bytes-to-determine-flush-amount-f.patch)
- sync with upstream (drop btrfs-wake-up-async_delalloc_pages-waiters-after-sub.patch)
- sync with upstream (drop btrfs-do-not-pin-logs-too-early-during-renames.patch)
- sync with upstream (drop btrfs-reduce-the-preemptive-flushing-threshold-to-90.patch)
- sync with upstream (drop watchdog-iTCO_wdt-Fix-detection-of-SMI-off-case.patch)

5.14-lucjan-ll39-rc1 --> 5.14-lucjan-ll39

5.14-lucjan-ll39-rc1

- sync with upstream (drop block-return-ELEVATOR_DISCARD_MERGE-if-possible.patch)
- sync with upstream (drop Bluetooth-Move-shutdown-callback-before-flushing-tx-.patch)
- add Revert-block-bfq-fix-UAF-in-bfq_io_set_weight_legacy.patch
- add blk-cgroup-fix-UAF-by-grabbing-blkcg-lock-before-des.patch

5.14-lucjan-ll38

- add CacULE-5.14.patch
- add ZEN-Disable-CacULE-by-default.patch

DROP 5.14-lucjan-ll38-rc2

5.14-lucjan-ll38-rc2

- add Revert-block-bfq-fix-UAF-in-bfq_io_set_weight_legacy.patch
- add blk-cgroup-fix-UAF-by-grabbing-blkcg-lock-before-des.patch

5.14-lucjan-ll38-rc1

- sync with upstream (drop block-return-ELEVATOR_DISCARD_MERGE-if-possible.patch)
- sync with upstream (drop Bluetooth-Move-shutdown-callback-before-flushing-tx-.patch)

5.14-lucjan-ll37

- add fs-ntfs3-Remove-redundant-initialization-of-variable.patch
- add fs-ntfs3.-Add-forward-declarations-for-structs-to-de.patch
- add fs-ntfs3-Add-missing-header-files-to-ntfs.h.patch
- add fs-ntfs3-Add-missing-headers-and-forward-declaration.patch
- add fs-ntfs3-Add-missing-header-and-guards-to-lib-header.patch
- add fs-ntfs3-Change-right-headers-to-bitfunc.c.patch
- add fs-ntfs3-Change-right-headers-to-upcase.c.patch
- add fs-ntfs3-Change-right-headers-to-lznt.c.patch
- add fs-ntfs3-Remove-unneeded-header-files-from-c-files.patch
- add fs-ntfs3-Limit-binary-search-table-size.patch
- add fs-ntfs3-Make-binary-search-to-search-smaller-chunks.patch
- add fs-ntfs3-Always-use-binary-search-with-entry-search.patch

DROP 5.14-lucjan-ll37-rc1

5.14-lucjan-ll37-rc1

- sync with upstream (drop block-return-ELEVATOR_DISCARD_MERGE-if-possible.patch)
- sync with upstream (drop Bluetooth-Move-shutdown-callback-before-flushing-tx-.patch)

5.14-lucjan-ll36-rc1 --> 5.14-lucjan-ll36

5.14-lucjan-ll36-rc1

- add namei-add-mapping-aware-lookup-helper.patch

5.14-lucjan-ll35-rc1

- add zstd-fix-fall-through-warnings.patch

5.14-lucjan-ll34-rc1

- add fs-ntfs3-Remove-unnecesarry-mount-option-noatime.patch
- add fs-ntfs3-Remove-unnecesarry-remount-flag-handling.patch
- add fs-ntfs3-Convert-mount-options-to-pointer-in-sbi.patch
- add fs-ntfs3-Use-new-api-for-mounting.patch
- add fs-ntfs3-Init-spi-more-in-init_fs_context-than-fill_.patch
- add fs-ntfs3-Make-mount-option-nohidden-more-universal.patch
- add fs-ntfs3-Add-iocharset-mount-option-as-alias-for-nls.patch
- add fs-ntfs3-Rename-mount-option-no_acs_rules-no-acsrule.patch
- add fs-ntfs3-Show-uid-gid-always-in-show_options.patch

5.14-lucjan-ll33-rc1

- add ksmbd-fix-lookup-on-idmapped-mounts.patch
- add ksmbd-fix-translation-in-smb2_populate_readdir_entry.patch
- add ksmbd-fix-translation-in-create_posix_rsp_buf.patch
- add ksmbd-fix-translation-in-ksmbd_acls_fattr.patch
- add ksmbd-fix-translation-in-acl-entries.patch
- add ksmbd-fix-subauth-0-handling-in-sid_to_id.patch
- add ksmbd-fix-translation-in-sid_to_id.patch
- add ndr-fix-translation-in-ndr_encode_posix_acl.patch
- add ksmbd-ensure-error-is-surfaced-in-set_file_basic_inf.patch
- add ksmbd-remove-setattr-preparations-in-set_file_basic_.patch
- add ksmbd-defer-notify_change-call.patch
- add ksmbd-Reduce-error-log-speed-is-unknown-to-debug.patch
- add ksmbd-smbd-fix-dma-mapping-error-in-smb_direct_post_.patch
- add ksmbd-remove-unused-ksmbd_file_table_flush-function.patch
- add ksmbd-add-validation-for-ndr-read-write-functions.patch
- add ksmbd-add-missing-assignments-to-ret-on-ndr_read_int.patch
- add ksmbd-fix-read-of-uninitialized-variable-ret-in-set_.patch
- add ksmbd-fix-control-flow-issues-in-sid_to_id.patch

5.14-lucjan-ll32-rc1

- add block-bfq-fix-UAF-in-bfq_io_set_weight_legacy.patch

5.14-lucjan-ll31-rc1

- add Bluetooth-Move-shutdown-callback-before-flushing-tx-.patch
- add watchdog-iTCO_wdt-Fix-detection-of-SMI-off-case.patch

5.14-lucjan-ll30-rc1

- add Revert-btrfs-remove-the-failing-device-argument-from.patch
- add Revert-btrfs-fix-mount-failure-due-to-past-and-trans.patch
- add btrfs-fix-mount-failure-due-to-past-and-transient-de.patch

5.14-lucjan-ll29-rc1

- add NFS-Always-provide-aligned-buffers-to-the-RPC-read-l.patch

5.14-lucjan-ll28-rc1

- add fs-add-a-filemap_fdatawrite_wbc-helper.patch

5.14-lucjan-ll27-rc1

- add btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- add btrfs-wait-on-async-extents-when-flushing-delalloc.patch
- add btrfs-use-the-filemap_fdatawrite_wbc-helper-for-dela.patch
- add btrfs-enable-a-tracepoint-when-we-fail-tickets.patch
- add btrfs-include-delalloc-related-info-in-dump-space-in.patch
- add btrfs-use-delalloc_bytes-to-determine-flush-amount-f.patch
- add btrfs-wake-up-async_delalloc_pages-waiters-after-sub.patch
- add btrfs-avoid-unnecessary-lock-and-leaf-splits-when-up.patch
- add btrfs-avoid-unnecessary-log-mutex-contention-when-sy.patch
- add btrfs-continue-readahead-of-siblings-even-if-target-.patch
- add btrfs-improve-the-batch-insertion-of-delayed-items.patch
- add btrfs-remove-unnecessary-list-head-initialization-wh.patch
- add btrfs-stop-doing-GFP_KERNEL-memory-allocations-in-th.patch
- add btrfs-make-btrfs_next_leaf-static-inline.patch
- add btrfs-allocate-backref_ctx-on-stack-in-find_extent_c.patch
- add btrfs-allocate-btrfs_ioctl_defrag_range_args-on-stac.patch
- add btrfs-allocate-btrfs_ioctl_quota_rescan_args-on-stac.patch
- add btrfs-allocate-file_ra_state-on-stack-in-readahead_c.patch
- add btrfs-do-not-pin-logs-too-early-during-renames.patch
- add btrfs-eliminate-some-false-positives-when-checking-i.patch
- add btrfs-avoid-unnecessarily-logging-directories-that-h.patch
- add btrfs-do-not-do-preemptive-flushing-if-the-majority-.patch
- add btrfs-reduce-the-preemptive-flushing-threshold-to-90.patch
- add btrfs-fix-mount-failure-due-to-past-and-transient-de.patch
- add btrfs-remove-the-failing-device-argument-from-btrfs_.patch

5.14-lucjan-ll26-rc1

- sync with upstream (drop HID-usbhid-fix-control-queue-full-flood.patch)
- sync with upstream (drop HID-usbhid-fix-control-queue-full-flood-take-two.patch)

5.14-lucjan-ll25-rc1

- add AUFS 20210906

5.14-lucjan-ll24-rc1

- sync with upstream (drop HID-usbhid-fix-control-queue-full-flood.patch)
- sync with upstream (drop HID-usbhid-fix-control-queue-full-flood-take-two.patch)

5.14-lucjan-ll23-rc1

- add Revert-mm-fix-priority-queue-in-multigenerational-lr.patch

5.14-lucjan-ll22-rc1

- sync with upstream (drop HID-usbhid-fix-control-queue-full-flood.patch)
- sync with upstream (drop HID-usbhid-fix-control-queue-full-flood-take-two.patch)

5.14-lucjan-ll21-rc1

- add Project-C v5.14-r1

5.14-lucjan-ll20-rc1

- sync with upstream (drop HID-usbhid-fix-control-queue-full-flood.patch)
- sync with upstream (drop HID-usbhid-fix-control-queue-full-flood-take-two.patch)

5.14-lucjan-ll19-rc1

- update futex2-resync-from-gitlab.collabora.com.patch
- drop stale-futex-resync-from-gitlab.collabora.com.patch
- add futex-resync-from-gitlab.collabora.com.patch

5.14-lucjan-ll18-rc1

- add bfq-use-bfq_entity_to_bfqg-helper-method.patch

5.14-lucjan-ll17-rc1

- add mm-fix-priority-queue-in-multigenerational-lru.patch
- update LL-Implement-ll-branding-v5.14.patch

5.14-lucjan-ll16-rc1

- sync with upstream (drop Bluetooth-btusb-check-conditions-before-enabling-USB.patch)

5.14-lucjan-ll15-rc1

- add fs-ntfs3-Fix-integer-overflow-in-ni_fiemap-with-fiem.patch
- add fs-ntfs3-Remove-unnecessary-condition-checking-from-.patch
- add fs-ntfs3-Remove-GPL-boilerplates-from-decompress-lib.patch
- add fs-ntfs3-Change-how-module-init-info-messages-are-di.patch

5.14-lucjan-ll14-rc1

- sync with upstream (drop Bluetooth-btusb-check-conditions-before-enabling-USB.patch)

5.14-lucjan-ll13-rc1

- add sched-alt-disable-sched_core-when-sched_alt-is-enabl.patch

5.14-lucjan-ll12-rc1

- sync with upstream (drop Bluetooth-btusb-check-conditions-before-enabling-USB.patch)

5.14-lucjan-ll11-rc1

- add sched-alt-Fix-fails-on-x86-UP-build-second-attempt.patch

5.14-lucjan-ll10-rc1

- sync with upstream (drop Bluetooth-btusb-check-conditions-before-enabling-USB.patch)

5.14-lucjan-ll9-rc1

- update UKSM-for-5.14.patch

5.14-lucjan-ll8-rc1

- sync with upstream (drop Bluetooth-btusb-check-conditions-before-enabling-USB.patch)

5.14-lucjan-ll7-rc1

- drop sched-alt-Fix-fails-on-x86-UP-build.patch

5.14-lucjan-ll6-rc1

- sync with upstream (drop Bluetooth-btusb-check-conditions-before-enabling-USB.patch)

5.14-lucjan-ll5-rc1

- add sched-alt-Fix-fails-on-x86-UP-build.patch

5.14-lucjan-ll4-rc1

- update lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch

5.14-lucjan-ll3-rc1

- update futex2-resync-from-gitlab.collabora.com.patch
- add stale-futex-resync-from-gitlab.collabora.com.patch

5.14-lucjan-ll2-rc1

- add fs-ntfs3-Remove-fat-ioctl-s-from-ntfs3-driver-for-no.patch
- add fs-ntfs3-Rework-file-operations.patch
- add fs-ntfs3-Restyle-comments-to-better-align-with-kerne.patch
- add Revert-block-Provide-icq-in-request-allocation-data.patch
- add block-Provide-icq-in-request-allocation-data.patch

5.14-lucjan-ll1-rc1

- add android-export-symbold-and-enable-building-ashmem-an.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add Bluetooth-btusb-check-conditions-before-enabling-USB.patch
- add AUFS 20210809
- add bbr2-5.14-introduce-BBRv2.patch
- add bcachefs-5.14-introduce-bcachefs-patchset.patch
- add block-elevator-remove-un-used-input-parameter-reques.patch
- add ioprio-move-user-space-relevant-ioprio-bits-to-UAPI-.patch
- add block-bfq-fix-bfq_set_next_ioprio_data.patch
- add block-improve-ioprio-class-description-comment.patch
- add block-change-ioprio_valid-to-an-inline-function.patch
- add block-fix-IOPRIO_PRIO_CLASS-and-IOPRIO_PRIO_VALUE-ma.patch
- add block-Introduce-IOPRIO_NR_LEVELS.patch
- add block-fix-default-IO-priority-handling.patch
- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch
- add bfq-reset-entity-prio_changed-in-bfq_init_entity.patch
- add bfq-remove-unnecessary-BFQ_DEFAULT_GRP_IOPRIO.patch
- add block-bfq-remove-the-repeated-declaration.patch
- add block-bfq-move-bfq_entity_to_bfqg-under-bfq_entity_t.patch
- add block-bfq-add-support-to-track-if-root_group-have-an.patch
- add block-bfq-do-not-idle-if-only-one-cgroup-is-activate.patch
- add block-bfq-add-support-to-record-request-size-informa.patch
- add block-bfq-consider-request-size-in-bfq_asymmetric_sc.patch
- add block-return-ELEVATOR_DISCARD_MERGE-if-possible.patch
- add block-bfq-Accept-symmetric-weight-adjustments.patch
- add block-bfq-honor-already-setup-queue-merges.patch
- add block-bfq-the-delta_from_first-should-be-ns-rather-t.patch
- add block-bfq-fix-the-timeout-calculation-in-bfq_bfqq_ch.patch
- add elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add block-bfq-set-bfq-lucjan-branding.patch
- add block-Provide-icq-in-request-allocation-data.patch
- add bfq-Track-number-of-allocated-requests-in-bfq_entity.patch
- add bfq-Limit-number-of-requests-consumed-by-each-cgroup.patch
- add Revert-bfq-Limit-number-of-requests-consumed-by-each.patch
- add Revert-bfq-Track-number-of-allocated-requests-in-bfq.patch
- add bfq-Track-number-of-allocated-requests-in-bfq_entity.patch
- add bfq-Limit-number-of-requests-consumed-by-each-cgroup.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O.patch
- add block-fix-trivial-typos-in-comments.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add port-print-fsync-count-for-bootchart.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add init-wait-for-partition-and-retry-scan.patch
- add add-boot-option-to-allow-unsigned-modules.patch
- add enable-stateless-firmware-loading.patch
- add migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add Port-microcode-patches.patch
- add cpu-5.14-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add init-Kconfig-add-O1-flag.patch
- add Makefile-Turn-off-loop-vectorization-for-GCC-O3-opti.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch
- add kbuild-Disable-stack-conservation-for-GCC.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add ZEN-Add-OpenRGB-patches.patch
- add scsi-sd-Optimal-I-O-size-should-be-a-multiple-of-rep.patch
- add iomap-avoid-deadlock-if-memory-reclaim-is-triggered-.patch
- add tty-Allow-setting-the-number-of-available-virtual-TT.patch
- add futex2-resync-from-gitlab.collabora.com.patch
- add ksmbd-add-document.patch
- add ksmbd-add-server-handler.patch
- add ksmbd-add-tcp-transport-layer.patch
- add ksmbd-add-ipc-transport-layer.patch
- add ksmbd-add-rdma-transport-layer.patch
- add ksmbd-add-a-utility-code-that-tracks-and-caches-sess.patch
- add ksmbd-add-authentication.patch
- add ksmbd-add-smb3-engine-part-1.patch
- add ksmbd-add-smb3-engine-part-2.patch
- add ksmbd-add-oplock-lease-cache-mechanism.patch
- add ksmbd-add-file-operations.patch
- add ksmbd-add-Kconfig-and-Makefile.patch
- add MAINTAINERS-add-ksmbd-kernel-server.patch
- add ksmbd-fix-__write_overflow-warning-in-ndr_read_strin.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add Disable-CPU_FREQ_GOV_SCHEDUTIL.patch
- add zen-Allow-MSR-writes-by-default.patch
- add PCI-Add-Intel-remapped-NVMe-device-support.patch
- add Linux-Random-Number-Generator.patch
- add LRNG-allocate-one-DRNG-instance-per-NUMA-node.patch
- add LRNG-sysctls-and-proc-interface.patch
- add LRNG-add-switchable-DRNG-support.patch
- add LRNG-add-common-generic-hash-support.patch
- add crypto-DRBG-externalize-DRBG-functions-for-LRNG.patch
- add LRNG-add-SP800-90A-DRBG-extension.patch
- add LRNG-add-kernel-crypto-API-PRNG-extension.patch
- add crypto-provide-access-to-a-static-Jitter-RNG-state.patch
- add LRNG-add-Jitter-RNG-fast-noise-source.patch
- add LRNG-add-SP800-90B-compliant-health-tests.patch
- add LRNG-add-interface-for-gathering-of-raw-entropy.patch
- add LRNG-add-power-on-and-runtime-self-tests.patch
- add mm-x86-arm64-add-arch_has_hw_pte_young.patch
- add mm-x86-add-CONFIG_ARCH_HAS_NONLEAF_PMD_YOUNG.patch
- add mm-vmscan.c-refactor-shrink_node.patch
- add mm-multigenerational-lru-groundwork.patch
- add mm-multigenerational-lru-protection.patch
- add mm-multigenerational-lru-mm_struct-list.patch
- add mm-multigenerational-lru-aging.patch
- add mm-multigenerational-lru-eviction.patch
- add mm-multigenerational-lru-user-interface.patch
- add mm-multigenerational-lru-Kconfig.patch
- add mm-multigenerational-lru-documentation.patch
- add mm-5.14-protect-mappings-under-memory-pressure.patch
- add fs-ntfs3-Add-headers-and-misc-files.patch
- add fs-ntfs3-Add-initialization-of-super-block.patch
- add fs-ntfs3-Add-bitmap.patch
- add fs-ntfs3-Add-file-operations-and-implementation.patch
- add fs-ntfs3-Add-attrib-operations.patch
- add fs-ntfs3-Add-compression.patch
- add fs-ntfs3-Add-NTFS-journal.patch
- add fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- add fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- add fs-ntfs3-Add-MAINTAINERS.patch
- add fs-ntfs3-Fix-various-spelling-mistakes.patch
- add fs-ntfs3-Use-linux-log2-is_power_of_2-function.patch
- add fs-ntfs3-Add-ifndef-define-to-all-header-files.patch
- add fs-ntfs3-Fix-integer-overflow-in-multiplication.patch
- add fs-ntfs3-Remove-unused-variable-cnt-in-ntfs_security.patch
- add fs-ntfs3-Fix-one-none-utf8-char-in-source-file.patch
- add fs-ntfs3-Fix-fall-through-warnings-for-Clang.patch
- add fs-ntfs3-Remove-unused-including-linux-version.h.patch
- add fs-ntfs3-Restyle-comment-block-in-ni_parse_reparse.patch
- add fs-ntfs3-Use-kernel-ALIGN-macros-over-driver-specifi.patch
- add fs-ntfs3-Do-not-use-driver-own-alloc-wrappers.patch
- add fs-ntfs3-Use-kcalloc-kmalloc_array-over-kzalloc-kmal.patch
- add fs-ntfs3-add-checks-for-allocation-failure.patch
- add fs-ntfs3-fix-an-error-code-in-ntfs_get_acl_ex.patch
- add fs-ntfs3-Fix-error-code-in-indx_add_allocate.patch
- add fs-ntfs3-Potential-NULL-dereference-in-hdr_find_spli.patch
- add fs-ntfs3-Fix-error-handling-in-indx_insert_into_root.patch
- add fs-ntfs3-Restyle-comments-to-better-align-with-kerne.patch
- add mm-compaction-optimize-proactive-compaction-deferral.patch
- add mm-compaction-support-triggering-of-proactive-compac.patch
- add genirq-i2c-Provide-and-use-generic_dispatch_irq.patch
- add mac80211-minstrel_ht-force-ampdu_len-to-be-0.patch
- add net-replace-WARN_ONCE-with-pr_warn_once.patch
- add x86-ACPI-State-Optimize-C3-entry-on-AMD-CPUs.patch
- add HID-usbhid-fix-control-queue-full-flood.patch
- add HID-usbhid-fix-control-queue-full-flood-take-two.patch
- add Project-C v5.14-r0
- add sched-alt-Export-can_nice-symbol-for-Android-Binder-.patch
- add sched-alt-Resync-with-lru-multigenerational.patch
- add sched-alt-Add-MG-LRU-changes-through-ifdef-macro.patch
- add init-Kconfig-set-default-value-of-SCHED_PDS.patch
- add init-Kconfig-Restore-original-PDS-description.patch
- add security-Add-LSM-hook-at-the-point-where-a-task-gets.patch
- add security-brute-Define-a-LSM-and-add-sysctl-attribute.patch
- add security-brute-Detect-a-brute-force-attack.patch
- add security-brute-Mitigate-a-brute-force-attack.patch
- add security-brute-Notify-to-userspace-task-killed.patch
- add selftests-brute-Add-tests-for-the-Brute-LSM.patch
- add Documentation-Add-documentation-for-the-Brute-LSM.patch
- add AINTAINERS-Add-a-new-entry-for-the-Brute-LSM.patch
- add spadfs-5.13-merge-v1.0.14.patch
- add UKSM-for-5.14.patch
- add v4l2loopback-5.14-merge-v0.12.5.patch
- add writeback-Track-number-of-inodes-under-writeback.patch
- add writeback-Reliably-update-bandwidth-estimation.patch
- add writeback-Fix-bandwidth-estimate-for-spiky-workload.patch
- add writeback-Rename-domain_update_bandwidth.patch
- add writeback-Use-READ_ONCE-for-unlocked-reads-of-writeb.patch
- add sched-autogroup-Add-kernel-parameter-and-config-opti.patch
- add netfilter-Add-full-cone-NAT-support.patch
- add netfilter-New-full-cone-SNAT-upstream.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add ZEN-vhba-Update-to-20210418.patch
- add lib-zstd-Add-kernel-specific-API.patch
- add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- add MAINTAINERS-Add-maintainer-entry-for-zstd.patch
- add kbuild-allow-setting-zstd-compression-level-for-modu.patch
- add kbuild-allow-setting-zstd-compression-level-for-kern.patch
- add kbuild-optimize-zstd-compression-settings.patch
- add kbuild-allow-setting-ultra-zstd-compression-level-fo.patch
- add kbuild-add-proper-bool-for-MODULE_COMPRESS_ZSTD_ULTR.patch
- add kbuild-add-proper-help-for-MODULE_COMPRESS_ZSTD_LEVE.patch
- add kbuild-add-menu-for-ZSTD-module-compression-options.patch
- add LL-Implement-ll-branding-v5.14.patch

5.13-lucjan-ll82-rc1 --> 5.13-lucjan-ll82

5.13-lucjan-ll82-rc1

- sync with upstream (drop Bluetooth-btusb-check-conditions-before-enabling-USB.patch)
- sync with upstream (drop pipe-avoid-unnecessary-EPOLLET-wakeups-under-normal-.patch)
- sync with upstream (drop pipe-do-FASYNC-notifications-for-every-pipe-IO-not-j.patch)
- sync with upstream (update block-fix-trivial-typos-in-comments.patch)

5.13-lucjan-ll81

- add ksmbd-fix-__write_overflow-warning-in-ndr_read_strin.patch

5.13-lucjan-ll80

- add update-to-git-tree-state.patch
- ad fs-ntfs3-Fix-various-spelling-mistakes.patch
- add fs-ntfs3-Use-linux-log2-is_power_of_2-function.patch
- add fs-ntfs3-Add-ifndef-define-to-all-header-files.patch
- add fs-ntfs3-Fix-integer-overflow-in-multiplication.patch
- add fs-ntfs3-Remove-unused-variable-cnt-in-ntfs_security.patch
- add fs-ntfs3-Fix-one-none-utf8-char-in-source-file.patch
- add fs-ntfs3-Fix-fall-through-warnings-for-Clang.patch
- add fs-ntfs3-Remove-unused-including-linux-version.h.patch
- add fs-ntfs3-Restyle-comment-block-in-ni_parse_reparse.patch
- add fs-ntfs3-Use-kernel-ALIGN-macros-over-driver-specifi.patch
- add fs-ntfs3-Do-not-use-driver-own-alloc-wrappers.patch
- add fs-ntfs3-Use-kcalloc-kmalloc_array-over-kzalloc-kmal.patch
- add fs-ntfs3-add-checks-for-allocation-failure.patch
- add fs-ntfs3-fix-an-error-code-in-ntfs_get_acl_ex.patch
- add fs-ntfs3-Fix-error-code-in-indx_add_allocate.patch
- add fs-ntfs3-Potential-NULL-dereference-in-hdr_find_spli.patch
- add fs-ntfs3-Fix-error-handling-in-indx_insert_into_root.patch
- add ntfs3-5.13-revert-back-to-iov_iter_copy_from_user_at.patch
- add ntfs3-5.13-fix-arguments-order-in-iov_iter_copy_from.patch

5.13-lucjan-ll79

- add Revert-block-mq-deadline-Speed-up-the-dispatch-of-lo.patch
- add block-mq-deadline-Fix-request-accounting.patch
- add block-mq-deadline-Remove-a-ktime_get_ns-call.patch
- add block-mq-deadline-Restore-performance.patch

5.13-lucjan-ll78

- add Revert-mq-deadline-Fix-request-accounting.patch
- add block-mq-deadline-Speed-up-the-dispatch-of-low-prior.patch

5.13-lucjan-ll77

- add docs-cgroup-v1-blkio-stop-abusing-itemized-list.patch
- add docs-cgroup-v1-blkio-update-for-5.x-kernels.patch
- add docs-block-bfq-describe-per-device-weight.patch
- add block-bfq-Accept-symmetric-weight-adjustments.patch

5.13-lucjan-ll76

- add pipe-avoid-unnecessary-EPOLLET-wakeups-under-normal-.patch
- add pipe-do-FASYNC-notifications-for-every-pipe-IO-not-j.patch

5.13-lucjan-ll75

- add mq-deadline-Fix-request-accounting.patch

5.13-lucjan-ll74

- add ksmbd-5.13-update-to-v8.patch

5.13-lucjan-ll73

- add Project-C v5.13-r3
- add Revert-mm-5.13-protect-anonymous-mappings-under-memo.patch
- add Revert-mm-5.13-protect-file-mappings-under-memory-pr.patch
- add mm-5.13-protect-mappings-under-memory-pressure.patch

5.13-lucjan-ll72

- add x86-ACPI-State-Optimize-C3-entry-on-AMD-CPUs.patch

5.13-lucjan-ll71-rc1 --> 5.13-lucjan-ll71

5.13-lucjan-ll71-rc1

- sync with upstream (drop drm-amdgpu-handle-VCN-instances-when-harvesting.patch)

5.13-lucjan-ll70

- update cpu-5.13-merge-graysky-s-patchset.patch

DROP 5.13-lucjan-ll70-rc1

5.13-lucjan-ll70-rc1

- sync with upstream (drop drm-amdgpu-handle-VCN-instances-when-harvesting.patch)

5.13-lucjan-ll69

- add sched-alt-Add-MG-LRU-changes-through-ifdef-macro.patch

5.13-lucjan-ll68

- add drm-amdgpu-handle-VCN-instances-when-harvesting.patch

5.13-lucjan-ll67

- add netfilter-New-full-cone-SNAT-upstream.patch

5.13-lucjan-ll66

- add Revert-Revert-block-increase-BLKCG_MAX_POLS.patch

5.13-lucjan-ll65

- update LL-Implement-ll-branding-v5.13.patch

5.13-lucjan-ll64

- add Revert-block-return-ELEVATOR_DISCARD_MERGE-if-possib.patch
- add Revert-block-mq-deadline-remove-redundant-assignment.patch
- add Revert-block-elevator-remove-un-used-input-parameter.patch
- add Revert-block-mq-deadline-Add-cgroup-support.patch
- add Revert-block-increase-BLKCG_MAX_POLS.patch
- add block-elevator-remove-un-used-input-parameter-reques.patch
- add block-return-ELEVATOR_DISCARD_MERGE-if-possible.patch
- update block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch

5.13-lucjan-ll63

- add Revert-block-return-ELEVATOR_DISCARD_MERGE-if-possib.patch
- add block-return-ELEVATOR_DISCARD_MERGE-if-possible.patch
- add Revert-bfq-optimize-the-calculation-of-bfq_weight_to.patch
- add Revert-block-fix-default-IO-priority-handling.patch
- add Revert-block-rename-IOPRIO_BE_NR.patch
- add Revert-block-fix-ioprio-interface.patch
- add Revert-block-bfq-fix-bfq_set_next_ioprio_data.patch
- add block-bfq-fix-bfq_set_next_ioprio_data.patch
- add block-improve-ioprio-class-description-comment.patch
- add block-change-ioprio_valid-to-an-inline-function.patch
- add block-fix-IOPRIO_PRIO_CLASS-and-IOPRIO_PRIO_VALUE-ma.patch
- add block-Introduce-IOPRIO_NR_LEVELS.patch
- add block-fix-default-IO-priority-handling.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch

5.13-lucjan-ll62

- add AUFS 20210809

5.13-lucjan-ll61

- add mm-multigenerational-lru-add-sys-kernel-mm-lru_gen-m.patch

5.13-lucjan-ll60

- add Revert-bfq-optimize-the-calculation-of-bfq_weight_to.patch
- add Revert-block-rename-IOPRIO_BE_NR.patch
- add Revert-block-fix-ioprio-interface.patch
- add Revert-block-bfq-fix-bfq_set_next_ioprio_data.patch
- add Revert-block-bfq-consider-request-size-in-bfq_asymme.patch
- add Revert-block-bfq-add-support-to-record-request-size-.patch
- add Revert-block-bfq-do-not-idle-if-only-one-cgroup-is-a.patch
- add block-bfq-add-support-to-track-if-root_group-have-an.patch
- add block-bfq-do-not-idle-if-only-one-cgroup-is-activate.patch
- add block-bfq-add-support-to-record-request-size-informa.patch
- add block-bfq-consider-request-size-in-bfq_asymmetric_sc.patch
- add block-bfq-fix-bfq_set_next_ioprio_data.patch
- add block-fix-ioprio-interface.patch
- add block-rename-IOPRIO_BE_NR.patch
- add block-fix-default-IO-priority-handling.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch
- add bfq-use-bfq_entity_to_bfqg-helper-method.patch

5.13-lucjan-ll59

- add ksmbd-add-document.patch
- add ksmbd-add-server-handler.patch
- add ksmbd-add-tcp-transport-layer.patch
- add ksmbd-add-ipc-transport-layer.patch
- add ksmbd-add-rdma-transport-layer.patch
- add ksmbd-add-a-utility-code-that-tracks-and-caches-sess.patch
- add ksmbd-add-authentication.patch
- add ksmbd-add-smb3-engine-part-1.patch
- add ksmbd-add-smb3-engine-part-2.patch
- add ksmbd-add-oplock-lease-cache-mechanism.patch
- add ksmbd-add-file-operations.patch
- add ksmbd-add-Kconfig-and-Makefile.patch
- add MAINTAINERS-add-ksmbd-kernel-server.patch

5.13-lucjan-ll58

- add Bluetooth-btusb-check-conditions-before-enabling-USB.patch

5.13-lucjan-ll57

- add netfilter-Add-full-cone-NAT-support.patch

5.13-lucjan-ll56-rc1 --> 5.13-lucjan-ll56

5.13-lucjan-ll56-rc1

- sync with upstream (drop pipe-make-pipe-writes-always-wake-up-readers.patch)
- sync with upstream (resync AUFS 20210705)

5.13-lucjan-ll55

- add v4l2loopback-5.13-update-to-the-latest-git-HEAD.patch

DROP 5.13-lucjan-ll55-rc1

5.13-lucjan-ll55-rc1

- sync with upstream (drop pipe-make-pipe-writes-always-wake-up-readers.patch)
- sync with upstream (resync AUFS 20210705)

5.13-lucjan-ll54

- add mm-multigenerational-lru-balance-memory-pressure-bet.patch

DROP 5.13-lucjan-ll54-rc1

5.13-lucjan-ll54-rc1

- sync with upstream (drop pipe-make-pipe-writes-always-wake-up-readers.patch)
- sync with upstream (resync AUFS 20210705)

5.13-lucjan-ll53

- add block-bfq-honor-already-setup-queue-merges.patch

DROP 5.13-lucjan-ll53-rc1

5.13-lucjan-ll53-rc1

- sync with upstream (drop pipe-make-pipe-writes-always-wake-up-readers.patch)
- sync with upstream (resync AUFS 20210705)

5.13-lucjan-ll52

- add Revert-bfq-optimize-the-calculation-of-bfq_weight_to.patch
- add ioprio-move-user-space-relevant-ioprio-bits-to-UAPI-.patch
- add block-bfq-fix-bfq_set_next_ioprio_data.patch
- add block-fix-ioprio-interface.patch
- add block-rename-IOPRIO_BE_NR.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch

DROP 5.13-lucjan-ll52-rc2

5.13-lucjan-ll52-rc2

- sync with upstream (resync AUFS 20210705)

5.13-lucjan-ll52-rc1

- sync with upstream (drop pipe-make-pipe-writes-always-wake-up-readers.patch)

5.13-lucjan-ll51

- add Project-C v5.13-r2

DROP 5.13-lucjan-ll51-rc1

5.13-lucjan-ll51-rc1

- sync with upstream (drop pipe-make-pipe-writes-always-wake-up-readers.patch)

5.13-lucjan-ll50

- add mm-compaction-support-triggering-of-proactive-compac.patch
- add pipe-make-pipe-writes-always-wake-up-readers.patch

5.13-lucjan-ll49

- add Update-intel-nvme-remap.c.patch

5.13-lucjan-ll48

- add Revert-block-another-attempt-to-fix-discard-merging.patch
- add block-return-ELEVATOR_DISCARD_MERGE-if-possible.patch
- add Revert-fs-ntfs3-Fix-unsupported-flags-by-clang.patch
- add ntfs3-5.13-update-to-v27.patch

5.13-lucjan-ll47

- add kbuild-add-menu-for-ZSTD-module-compression-options.patch

5.13-lucjan-ll46

- update futex2-resync-from-gitlab.collabora.com.patch

5.13-lucjan-ll45-rc1 --> 5.13-lucjan-ll45

5.13-lucjan-ll45-rc1

- add mm-compaction-optimize-proactive-compaction-deferral.patch

5.13-lucjan-ll44-rc1

- add Revert-Revert-mm-shmem-fix-shmem_swapin-race-with-sw.patch
- add Revert-Revert-swap-fix-do_swap_page-race-with-swapof.patch

5.13-lucjan-ll43-rc1

- add Revert-mm-fix-priority-queue-in-multigenerational-lru.patch
- add Revert-mm-fix-priority-queue-in-multigenerational-lru-v2.patch
- add mm-fix-priority-queue-in-multigenerational-lru.patch
- add PCI-Add-Intel-remapped-NVMe-device-support.patch

5.13-lucjan-ll42-rc1

- add mm-fix-priority-queue-in-multigenerational-lru-v2.patch

5.13-lucjan-ll41-rc1

- add mm-fix-priority-queue-in-multigenerational-lru.patch

5.13-lucjan-ll40-rc1

- add block-bfq-the-delta_from_first-should-be-ns-rather-t.patch

5.13-lucjan-ll39-rc1

- add mm-swapfile-use-percpu_ref-to-serialize-against-conc.patch
- add mm-swap-remove-confusing-checking-for-non_swap_entry.patch

5.13-lucjan-ll38-rc1

- sync with upstream (resync do-accept-in-LIFO-order-for-cache-efficiency.patch)

5.13-lucjan-ll37-rc1

- add block-mq-deadline-remove-redundant-assignment-of-var.patch

5.13-lucjan-ll36-rc1

- sync with upstream (resync do-accept-in-LIFO-order-for-cache-efficiency.patch)

5.13-lucjan-ll35-rc1

- add block-increase-BLKCG_MAX_POLS.patch

5.13-lucjan-ll34-rc1

- sync with upstream (resync do-accept-in-LIFO-order-for-cache-efficiency.patch)

5.13-lucjan-ll33-rc1

- add block-another-attempt-to-fix-discard-merging.patch

5.13-lucjan-ll32-rc1

- sync with upstream (resync do-accept-in-LIFO-order-for-cache-efficiency.patch)

5.13-lucjan-ll31-rc1

- add Revert-bfq-Limit-number-of-requests-consumed-by-each.patch
- add Revert-bfq-Track-number-of-allocated-requests-in-bfq.patch
- add Revert-block-Provide-icq-in-request-allocation-data.patch
- add block-Provide-icq-in-request-allocation-data.patch
- add bfq-Track-number-of-allocated-requests-in-bfq_entity.patch
- add bfq-Limit-number-of-requests-consumed-by-each-cgroup.patch

5.13-lucjan-ll30-rc1

- add block-bfq-fix-the-timeout-calculation-in-bfq_bfqq_ch.patch

5.13-lucjan-ll29-rc1

- add writeback-Track-number-of-inodes-under-writeback.patch
- add writeback-Reliably-update-bandwidth-estimation.patch
- add writeback-Fix-bandwidth-estimate-for-spiky-workload.patch
- add writeback-Rename-domain_update_bandwidth.patch
- add writeback-Use-READ_ONCE-for-unlocked-reads-of-writeb.patch

5.13-lucjan-ll28-rc1

- add block-Provide-icq-in-request-allocation-data.patch
- add bfq-Track-number-of-allocated-requests-in-bfq_entity.patch
- add bfq-Limit-number-of-requests-consumed-by-each-cgroup.patch
- add block-bfq-do-not-idle-if-only-one-cgroup-is-activate.patch
- add block-bfq-add-support-to-record-request-size-informa.patch
- add block-bfq-consider-request-size-in-bfq_asymmetric_sc.patch

5.13-lucjan-ll27-rc1

- add (again) bfq-Remove-merged-request-already-in-bfq_requests_me.patch

5.13-lucjan-ll26-rc1

- sync with upstream (drop btrfs-send-fix-invalid-path-for-unlink-operations-af.patch)
- sync with upstream (drop blk-mq-update-hctx-dispatch_busy-in-case-of-real-sch.patch)
- sync with upstream (drop block-bfq-fix-delayed-stable-merge-check.patch)
- sync with upstream (drop block-bfq-avoid-delayed-merge-of-async-queues.patch)
- sync with upstream (drop block-bfq-reset-waker-pointer-with-shared-queues.patch)
- sync with upstream (drop bfq-Remove-merged-request-already-in-bfq_requests_me.patch)
- sync with upstream (drop ALSA-intel8x0-Fix-breakage-at-ac97-clock-measurement.patch)

5.13-lucjan-ll25-rc1

- add Linux-Random-Number-Generator.patch
- add LRNG-allocate-one-DRNG-instance-per-NUMA-node.patch
- add LRNG-sysctls-and-proc-interface.patch
- add LRNG-add-switchable-DRNG-support.patch
- add LRNG-add-common-generic-hash-support.patch
- add crypto-DRBG-externalize-DRBG-functions-for-LRNG.patch
- add LRNG-add-SP800-90A-DRBG-extension.patch
- add LRNG-add-kernel-crypto-API-PRNG-extension.patch
- add crypto-provide-access-to-a-static-Jitter-RNG-state.patch
- add LRNG-add-Jitter-RNG-fast-noise-source.patch
- add LRNG-add-SP800-90B-compliant-health-tests.patch
- add LRNG-add-interface-for-gathering-of-raw-entropy.patch
- add LRNG-add-power-on-and-runtime-self-tests.patch

5.13-lucjan-ll24-rc1

- sync with upstream (drop btrfs-send-fix-invalid-path-for-unlink-operations-af.patch)
- sync with upstream (drop blk-mq-update-hctx-dispatch_busy-in-case-of-real-sch.patch)
- sync with upstream (drop block-bfq-fix-delayed-stable-merge-check.patch)
- sync with upstream (drop block-bfq-avoid-delayed-merge-of-async-queues.patch)
- sync with upstream (drop block-bfq-reset-waker-pointer-with-shared-queues.patch)
- sync with upstream (drop bfq-Remove-merged-request-already-in-bfq_requests_me.patch)
- sync with upstream (drop ALSA-intel8x0-Fix-breakage-at-ac97-clock-measurement.patch)

5.13-lucjan-ll23-rc1

- add mac80211-minstrel_ht-force-ampdu_len-to-be-0.patch
- add net-replace-WARN_ONCE-with-pr_warn_once.patch

5.13-lucjan-ll22-rc1

- sync with upstream (drop btrfs-send-fix-invalid-path-for-unlink-operations-af.patch)
- sync with upstream (drop blk-mq-update-hctx-dispatch_busy-in-case-of-real-sch.patch)
- sync with upstream (drop block-bfq-fix-delayed-stable-merge-check.patch)
- sync with upstream (drop block-bfq-avoid-delayed-merge-of-async-queues.patch)
- sync with upstream (drop block-bfq-reset-waker-pointer-with-shared-queues.patch)
- sync with upstream (drop bfq-Remove-merged-request-already-in-bfq_requests_me.patch)
- sync with upstream (drop ALSA-intel8x0-Fix-breakage-at-ac97-clock-measurement.patch)

5.13-lucjan-ll21-rc1

- add ALSA-usb-audio-Make-snd_usb_pcm_delay-static.patch
- add ALSA-usb-audio-Pre-calculate-buffer-byte-size.patch
- add ALSA-usb-audio-Refactoring-delay-account-code.patch
- add ALSA-usb-audio-Factor-out-DSD-bitrev-copy-function.patch
- add ALSA-usb-audio-Reduce-latency-at-playback-start.patch
- add Revert-ALSA-usb-audio-Reduce-latency-at-playback-sta.patch
- add ALSA-usb-audio-Reduce-latency-at-playback-start-take.patch
- add ALSA-intel8x0-Fix-breakage-at-ac97-clock-measurement.patch

5.13-lucjan-ll20-rc1

- sync with upstream (drop btrfs-send-fix-invalid-path-for-unlink-operations-af.patch)
- sync with upstream (drop blk-mq-update-hctx-dispatch_busy-in-case-of-real-sch.patch)
- sync with upstream (drop block-bfq-fix-delayed-stable-merge-check.patch)
- sync with upstream (drop block-bfq-avoid-delayed-merge-of-async-queues.patch)
- sync with upstream (drop block-bfq-reset-waker-pointer-with-shared-queues.patch)
- sync with upstream (drop bfq-Remove-merged-request-already-in-bfq_requests_me.patch)

5.13-lucjan-ll19-rc1

- add mm-5.13-protect-anonymous-mappings-under-memory-pres.patch

5.13-lucjan-ll18-rc1

- drop igb-fix-netpoll-exit-with-traffic.patch

5.13-lucjan-ll17-rc1

- add net-tcp_bbr-v2-Fix-missing-ECT-markings-on-retransmi.patch

5.13-lucjan-ll16-rc1

- sync with upstream (drop mm-page_alloc-Correct-return-value-of-populated-elem.patch)

5.13-lucjan-ll15-rc1

- add Project-C v5.13-r1
- drop sched-pds-1.1-Implement-bitmap-allocator.patch
- drop sched-pds-Set-pds-dev-instead-of-pds.patch

5.13-lucjan-ll14-rc1

- sync with upstream (drop mm-page_alloc-Correct-return-value-of-populated-elem.patch)

5.13-lucjan-ll13-rc1

- add AUFS 20210705

5.13-lucjan-ll12-rc1

- update futex2-resync-from-gitlab.collabora.com.patch

5.13-lucjan-ll11-rc1

- add kbuild-add-proper-help-for-MODULE_COMPRESS_ZSTD_LEVE.patch

5.13-lucjan-ll10-rc1

- add kbuild-add-proper-bool-for-MODULE_COMPRESS_ZSTD_ULTR.patch

5.13-lucjan-ll9-rc1

- fix kbuild-optimize-zstd-compression-settings.patch

5.13-lucjan-ll8-rc1

- add kbuild-allow-setting-ultra-zstd-compression-level-fo.patch

5.13-lucjan-ll7-rc1

- add futex-resync-from-gitlab.collabora.com.patch

5.13-lucjan-ll6-rc1

- update futex2-resync-from-gitlab.collabora.com.patch

5.13-lucjan-ll5-rc1

- add mm-page_alloc-Correct-return-value-of-populated-elem.patch

5.13-lucjan-ll4-rc1

- add security-Add-LSM-hook-at-the-point-where-a-task-gets.patch
- add security-brute-Define-a-LSM-and-add-sysctl-attribute.patch
- add security-brute-Detect-a-brute-force-attack.patch
- add security-brute-Mitigate-a-brute-force-attack.patch
- add security-brute-Notify-to-userspace-task-killed.patch
- add selftests-brute-Add-tests-for-the-Brute-LSM.patch
- add Documentation-Add-documentation-for-the-Brute-LSM.patch
- add MAINTAINERS-Add-a-new-entry-for-the-Brute-LSM.patch

5.13-lucjan-ll3-rc1

- add include-linux-memcontrol.h-do-not-warn-in-page_memcg.patch
- add include-linux-nodemask.h-define-next_memory_node-if-.patch
- add include-linux-cgroup.h-export-cgroup_mutex.patch
- add mm-x86-support-the-access-bit-on-non-leaf-PMD-entrie.patch
- add mm-vmscan.c-refactor-shrink_node.patch
- add mm-workingset.c-refactor-pack_shadow-and-unpack_shad.patch
- add mm-multigenerational-lru-groundwork.patch
- add mm-multigenerational-lru-activation.patch
- add mm-multigenerational-lru-mm_struct-list.patch
- add mm-multigenerational-lru-aging.patch
- add mm-multigenerational-lru-eviction.patch
- add mm-multigenerational-lru-user-interface.patch
- add mm-multigenerational-lru-Kconfig.patch
- add mm-multigenerational-lru-documentation.patch

5.13-lucjan-ll2-rc1

- add block-mq-deadline-Remove-a-WARN_ON_ONCE-call.patch

5.13-lucjan-ll1-rc1

- add android-export-symbold-and-enable-building-ashmem-an.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add bbr2-5.13-introduce-BBRv2.patch
- add bcachefs-5.13-introduce-bcachefs-patchset.patch
- add block-bfq-let-also-stably-merged-queues-enjoy-weight.patch
- add block-bfq-fix-delayed-stable-merge-check.patch
- add block-bfq-consider-also-creation-time-in-delayed-sta.patch
- add block-bfq-boost-throughput-by-extending-queue-mergin.patch
- add block-bfq-avoid-delayed-merge-of-async-queues.patch
- add block-bfq-check-waker-only-for-queues-with-no-in-fli.patch
- add block-bfq-reset-waker-pointer-with-shared-queues.patch
- add block-Do-not-pull-requests-from-the-scheduler-when-w.patch
- add block-Remove-unnecessary-elevator-operation-checks.patch
- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch
- add bfq-reset-entity-prio_changed-in-bfq_init_entity.patch
- add bfq-remove-unnecessary-BFQ_DEFAULT_GRP_IOPRIO.patch
- add block-bfq-remove-the-repeated-declaration.patch
- add block-bfq-move-bfq_entity_to_bfqg-under-bfq_entity_t.patch
- add elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add block-bfq-set-bfq-lucjan-branding.patch
- add block-Kconfig-Make-the-BLK_WBT-and-BLK_WBT_MQ-entrie.patch
- add block-blk-cgroup-Swap-the-blk_throtl_init-and-blk_io.patch
- add block-blk-rq-qos-Move-a-function-from-a-header-file-.patch
- add block-Introduce-the-ioprio-rq-qos-policy.patch
- add block-mq-deadline-Add-several-comments.patch
- add block-mq-deadline-Add-two-lockdep_assert_held-statem.patch
- add block-mq-deadline-Remove-two-local-variables.patch
- add block-mq-deadline-Rename-dd_init_queue-and-dd_exit_q.patch
- add block-mq-deadline-Improve-compile-time-argument-chec.patch
- add block-mq-deadline-Improve-the-sysfs-show-and-store-m.patch
- add block-mq-deadline-Reserve-25-of-scheduler-tags-for-s.patch
- add block-mq-deadline-Micro-optimize-the-batching-algori.patch
- add block-mq-deadline-Add-I-O-priority-support.patch
- add block-mq-deadline-Track-I-O-statistics.patch
- add block-mq-deadline-Add-cgroup-support.patch
- add block-mq-deadline-Prioritize-high-priority-requests.patch
- add bfq-Remove-merged-request-already-in-bfq_requests_me.patch
- add blk-Fix-lock-inversion-between-ioc-lock-and-bfqd-loc.patch
- add block-elevator-remove-un-used-input-parameter-reques.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O.patch
- add block-fix-trivial-typos-in-comments.patch
- add blk-mq-update-hctx-dispatch_busy-in-case-of-real-sch.patch
- add btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- add btrfs-do-not-evaluate-the-expression-with-CONFIG_BTR.patch
- add btrfs-restart-snapshot-delete-if-we-have-to-end-the-.patch
- add btrfs-add-btree-read-ahead-for-full-send-operations.patch
- add btrfs-check-worker-before-need_preemptive_reclaim.patch
- add btrfs-only-clamp-the-first-time-we-have-to-start-flu.patch
- add btrfs-don-t-include-the-global-rsv-size-in-the-preem.patch
- add btrfs-take-into-account-global-rsv-in-need_preemptiv.patch
- add btrfs-use-the-global-rsv-size-in-the-preemptive-thre.patch
- add btrfs-only-ignore-delalloc-if-delalloc-is-much-small.patch
- add btrfs-handle-preemptive-delalloc-flushing-slightly-d.patch
- add btrfs-scrub-per-device-bandwidth-control.patch
- add btrfs-abort-the-transaction-if-we-fail-to-replay-log.patch
- add btrfs-do-not-infinite-loop-in-data-reclaim-if-we-abo.patch
- add btrfs-change-handle_fs_error-in-recover_log_trees-to.patch
- add btrfs-avoid-unnecessary-logging-of-xattrs-during-fas.patch
- add btrfs-handle-shrink_delalloc-pages-calculation-diffe.patch
- add btrfs-send-fix-invalid-path-for-unlink-operations-af.patch
- add btrfs-sysfs-export-dev-stats-in-devinfo-directory.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add-boot-option-to-allow-unsigned-modules.patch
- add enable-stateless-firmware-loading.patch
- add migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add Port-microcode-patches.patch
- add cpu-5.13-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add init-Kconfig-add-O1-flag.patch
- add Makefile-Turn-off-loop-vectorization-for-GCC-O3-opti.patch
- add futex2-resync-from-gitlab.collabora.com.patch
- add zen-Allow-MSR-writes-by-default.patch
- add mm-5.13-protect-file-mappings-under-memory-pressure.patch
- add fs-ntfs3-Add-headers-and-misc-files.patch
- add fs-ntfs3-Add-initialization-of-super-block.patch
- add fs-ntfs3-Add-bitmap.patch
- add fs-ntfs3-Add-file-operations-and-implementation.patch
- add fs-ntfs3-Add-attrib-operations.patch
- add fs-ntfs3-Add-compression.patch
- add fs-ntfs3-Add-NTFS-journal.patch
- add fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- add fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- add fs-ntfs3-Add-MAINTAINERS.patch
- add fs-ntfs3-Fix-unsupported-flags-by-clang.patch
- add Project-C v5.13-r0
- add sched-alt-Export-can_nice-symbol-for-Android-Binder-.patch
- add sched-alt-Resync-with-lru-multigenerational.patch
- add init-Kconfig-set-default-value-of-SCHED_PDS.patch
- add init-Kconfig-Restore-original-PDS-description.patch
- add sched-pds-1.1-Implement-bitmap-allocator.patch
- add sched-pds-Set-pds-dev-instead-of-pds.patch
- add spadfs-5.13-merge-v1.0.14.patch
- add sched-autogroup-Add-kernel-parameter-and-config-opti.patch
- add lib-zstd-Add-kernel-specific-API.patch
- add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- add MAINTAINERS-Add-maintainer-entry-for-zstd.patch
- add kbuild-allow-setting-zstd-compression-level-for-modu.patch
- add kbuild-allow-setting-zstd-compression-level-for-kern.patch
- add kbuild-optimize-zstd-compression-settings.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add ZEN-vhba-Update-to-20210418.patch
- add v4l2loopback-5.13-merge-v0.12.5.patch
- add v4l2loopback-5.13-confine-v4l2loopback_cleanup_modul.patch
- add UKSM for 5.13
- add AUFS 20210517
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add Disable-CPU_FREQ_GOV_SCHEDUTIL.patch
- add LL-Add-.ll-version.patch
- add LL-Implement-ll-branding-v5.13.patch

5.12-lucjan-ll80-rc1 --> 5.12-lucjan-ll80

5.12-lucjan-ll80-rc1

- sync with upstream (resync do-accept-in-LIFO-order-for-cache-efficiency.patch)

5.12-lucjan-ll79

- add (again) bfq-Remove-merged-request-already-in-bfq_requests_me.patch

5.12-lucjan-ll78-rc1

- sync with upstream  (drop btrfs-send-fix-invalid-path-for-unlink-operations-af.patch)
- sync with upstream  (drop blk-mq-update-hctx-dispatch_busy-in-case-of-real-sch.patch)
- sync with upstream  (drop bfq-Remove-merged-request-already-in-bfq_requests_me.patch)

5.12-lucjan-ll77

- drop igb-fix-netpoll-exit-with-traffic.patch

5.12-lucjan-ll76

- add net-tcp_bbr-v2-Fix-missing-ECT-markings-on-retransmi.patch

5.12-lucjan-ll75

- add soundwire-add-override-addr-ops.patch
- add soundwire-Intel-introduce-DMI-quirks-for-HP-Spectre-.patch
- add soundwire-Intel-add-DMI-quirk-for-Dell-SKU-0A3E.patch

5.12-lucjan-ll74

- add kbuild-allow-setting-ultra-zstd-compression-level-fo.patch
- add kbuild-add-proper-bool-for-MODULE_COMPRESS_ZSTD_ULTR.patch
- add kbuild-add-proper-help-for-MODULE_COMPRESS_ZSTD_LEVE.patch

5.12-lucjan-ll73

- update futex2-resync-from-gitlab.collabora.com.patch

5.12-lucjan-ll72-rc1 --> 5.12-lucjan-ll72

5.12-lucjan-ll72-rc1

- sync with upstream (drop psi-Fix-psi-state-corruption-when-schedule-races-wit.patch)

5.12-lucjan-ll71

- add block-mq-deadline-Remove-a-WARN_ON_ONCE-call.patch

DROP 5.12-lucjan-ll71-rc1

5.12-lucjan-ll71-rc1

- sync with upstream (drop psi-Fix-psi-state-corruption-when-schedule-races-wit.patch)

5.12-lucjan-ll70

- update block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch

5.12-lucjan-ll69

- add psi-Fix-psi-state-corruption-when-schedule-races-wit.patch

5.12-lucjan-ll68

- drop block-Add-CONFIG-to-rename-the-mq-deadline-scheduler.patch
- drop ZEN-Fix-mq-deadline-scheduler-renaming.patch
- drop ZEN-Increase-max-elevator-name-size.patch
- update block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- update LL-Implement-ll-branding-v5.12.patch
- add elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add Revert-block-elevator-remove-un-used-input-parameter.patch
- add Revert-blk-Fix-lock-inversion-between-ioc-lock-and-b.patch
- add Revert-bfq-Remove-merged-request-already-in-bfq_requ.patch
- add block-Kconfig-Make-the-BLK_WBT-and-BLK_WBT_MQ-entrie.patch
- add block-blk-cgroup-Swap-the-blk_throtl_init-and-blk_io.patch
- add block-blk-rq-qos-Move-a-function-from-a-header-file-.patch
- add block-Introduce-the-ioprio-rq-qos-policy.patch
- add block-mq-deadline-Add-several-comments.patch
- add block-mq-deadline-Add-two-lockdep_assert_held-statem.patch
- add block-mq-deadline-Remove-two-local-variables.patch
- add block-mq-deadline-Rename-dd_init_queue-and-dd_exit_q.patch
- add block-mq-deadline-Improve-compile-time-argument-chec.patch
- add block-mq-deadline-Improve-the-sysfs-show-and-store-m.patch
- add block-mq-deadline-Reserve-25-of-scheduler-tags-for-s.patch
- add block-mq-deadline-Micro-optimize-the-batching-algori.patch
- add block-mq-deadline-Add-I-O-priority-support.patch
- add block-mq-deadline-Track-I-O-statistics.patch
- add block-mq-deadline-Add-cgroup-support.patch
- add block-mq-deadline-Prioritize-high-priority-requests.patch
- add block-elevator-remove-un-used-input-parameter-reques.patch
- add bfq-Remove-merged-request-already-in-bfq_requests_me.patch
- add blk-Fix-lock-inversion-between-ioc-lock-and-bfqd-loc.patch

5.12-lucjan-ll67

- add mm-compaction-optimize-proactive-compaction-deferral.patch
- add mm-compaction-support-triggering-of-proactive-compac.patch
- add mm-compaction-fix-wakeup-logic-of-proactive-compacti.patch

5.12-lucjan-ll66

- add Revert-block-bfq-avoid-delayed-merge-of-async-queues.patch
- add Revert-block-bfq-fix-delayed-stable-merge-check.patch
- add block-bfq-let-also-stably-merged-queues-enjoy-weight.patch
- add block-bfq-fix-delayed-stable-merge-check.patch
- add block-bfq-consider-also-creation-time-in-delayed-sta.patch
- add block-bfq-boost-throughput-by-extending-queue-mergin.patch
- add block-bfq-avoid-delayed-merge-of-async-queues.patch
- add block-bfq-check-waker-only-for-queues-with-no-in-fli.patch
- add block-bfq-reset-waker-pointer-with-shared-queues.patch

5.12-lucjan-ll65

- add Revert-Makefile-Turn-off-loop-vectorization-for-GCC-.patch
- add Makefile-Turn-off-loop-vectorization-for-GCC-O3-opti.patch

5.12-lucjan-ll64

- add block-Remove-unnecessary-elevator-operation-checks.patch

5.12-lucjan-ll63

- add bcachefs-5.12-introduce-bcachefs-patchset.patch

5.11-lucjan-ll62

- update cpu-5.12-merge-graysky-s-patchset.patch

5.12-lucjan-ll61-rc1 --> 5.12-lucjan-ll61

5.12-lucjan-ll61-rc1

- sync with upstream (drop btrfs-Fix-return-value-of-btrfs_mark_extent_written-.patch)
- sync with upstream (drop btrfs-Promote-debugging-asserts-to-full-flegded-chec.patch)
- add prjc-5.12-fix-compilation-error-if-sched_feat-UTIL_E.patch

5.12-lucjan-ll60

- update futex2-resync-from-gitlab.collabora.com.patch

DROP 5.12-lucjan-ll60-rc2

5.12-lucjan-ll60-rc2

- add prjc-5.12-fix-compilation-error-if-sched_feat-UTIL_E.patch

5.12-lucjan-ll60-rc1

- sync with upstream (drop btrfs-Fix-return-value-of-btrfs_mark_extent_written-.patch)
- sync with upstream (drop btrfs-Promote-debugging-asserts-to-full-flegded-chec.patch)

5.12-lucjan-ll59

- add x86-setup-Consolidate-early-memory-reservations.patch
- add x86-setup-Merge-several-reservations-of-start-of-mem.patch
- add x86-setup-Move-trim_snb_memory-later-in-setup_arch-t.patch
- add x86-setup-always-reserve-the-first-1M-of-RAM.patch
- add x86-setup-remove-CONFIG_X86_RESERVE_LOW-and-reservel.patch
- add x86-crash-remove-crash_reserve_low_1M.patch

5.12-lucjan-ll58

- add btrfs-handle-shrink_delalloc-pages-calculation-diffe.patch
- add btrfs-send-fix-invalid-path-for-unlink-operations-af.patch
- add btrfs-sysfs-export-dev-stats-in-devinfo-directory.patch

5.12-lucjan-ll57

- add Makefile-Turn-off-loop-vectorization-for-GCC-O3-opti.patch

5.12-lucjan-ll56-rc1 --> 5.12-lucjan-ll56

5.12-lucjan-ll56-rc1

- sync with upstream (drop btrfs-check-error-value-from-btrfs_update_inode-in-t.patch)
- sync with upstream (drop btrfs-fix-error-handling-in-btrfs_del_csums.patch)
- sync with upstream (drop btrfs-mark-ordered-extent-and-inode-with-error-if-we.patch)
- sync with upstream (drop btrfs-return-errors-from-btrfs_del_csums-in-cleanup_.patch)
- sync with upstream (drop btrfs-fix-deadlock-when-cloning-inline-extents-and-l.patch)

5.12-lucjan-ll55

- add mac80211-minstrel_ht-force-ampdu_len-to-be-0.patch

5.11-lucjan-ll54

- update cpu-5.12-merge-graysky-s-patchset.patch

5.12-lucjan-ll53

- add blk-mq-update-hctx-dispatch_busy-in-case-of-real-sch.patch

5.12-lucjan-ll52

- add btrfs-fix-deadlock-when-cloning-inline-extents-and-l.patch
- add btrfs-avoid-unnecessary-logging-of-xattrs-during-fas.patch
- add btrfs-Fix-return-value-of-btrfs_mark_extent_written-.patch
- add btrfs-Promote-debugging-asserts-to-full-flegded-chec.patch

5.12-lucjan-ll51-rc1 --> 5.12-lucjan-ll51

5.12-lucjan-ll51-rc1

- sync with upstream (drop btrfs-return-whole-extents-in-fiemap.patch)

5.12-lucjan-ll50

- update futex2-resync-from-gitlab.collabora.com.patch

DROP 5.12-lucjan-ll50-rc1

5.12-lucjan-ll50-rc1

- sync with upstream (drop btrfs-return-whole-extents-in-fiemap.patch)

5.12-lucjan-ll49

- update futex2-resync-from-gitlab.collabora.com.patch

DROP 5.12-lucjan-ll49-rc1

5.12-lucjan-ll49-rc1

- sync with upstream (drop btrfs-return-whole-extents-in-fiemap.patch)

5.12-lucjan-ll48

- add block-bfq-move-bfq_entity_to_bfqg-under-bfq_entity_t.patch

5.12-lucjan-ll47

- add block-bfq-remove-the-repeated-declaration.patch

5.12-lucjan-ll46-rc1 --> 5.12-lucjan-ll46

5.12-lucjan-ll46-rc1

- sync with upstream (drop drm-i915-gt-Disable-HiZ-Raw-Stall-Optimization-on-br.patch)
- sync with upstream (drop btrfs-avoid-RCU-stalls-while-running-delayed-iputs.patch)
- sync with upstream (drop btrfs-fix-removed-dentries-still-existing-after-log-.patch)

5.12-lucjan-ll45

- add Revert-bfq-silence-lockdep-for-bfqd-ioc-lock-inversi.patch

DROP 5.12-lucjan-ll45-rc1

5.12-lucjan-ll45-rc1

- sync with upstream (drop drm-i915-gt-Disable-HiZ-Raw-Stall-Optimization-on-br.patch)
- sync with upstream (drop btrfs-avoid-RCU-stalls-while-running-delayed-iputs.patch)
- sync with upstream (drop btrfs-fix-removed-dentries-still-existing-after-log-.patch)

5.12-lucjan-ll44

- add Revert-blk-Fix-lock-inversion-between-ioc-lock-and-b.patch
- add Revert-block-Do-not-merge-recursively-in-elv_attempt.patch
- add bfq-Remove-merged-request-already-in-bfq_requests_me.patch
- add blk-Fix-lock-inversion-between-ioc-lock-and-bfqd-loc.patch
- add block-bfq-fix-delayed-stable-merge-check.patch
- add block-bfq-avoid-delayed-merge-of-async-queues.patch

DROP 5.12-lucjan-ll44-rc1

5.12-lucjan-ll44-rc1

- sync with upstream (drop drm-i915-gt-Disable-HiZ-Raw-Stall-Optimization-on-br.patch)
- sync with upstream (drop btrfs-avoid-RCU-stalls-while-running-delayed-iputs.patch)
- sync with upstream (drop btrfs-fix-removed-dentries-still-existing-after-log-.patch)

5.12-lucjan-ll43

- add btrfs-handle-btrfs_record_root_in_trans-failure-in-b.patch
- add btrfs-change-handle_fs_error-in-recover_log_trees-to.patch

5.12-lucjan-ll42

- drop Revert-bus-mhi-core-Process-execution-environment-ch.patch
- drop Revert-net-tso-add-UDP-segmentation-support.patch
- add drm-i915-gt-Disable-HiZ-Raw-Stall-Optimization-on-br.patch

5.12-lucjan-ll41

- add Revert-block-bfq-move-spin_unlock_irq-to-release-req.patch
- add block-Do-not-merge-recursively-in-elv_attempt_insert.patch
- add blk-Fix-lock-inversion-between-ioc-lock-and-bfqd-loc.patch

5.12-lucjan-ll40

- add Revert-block-bfq-fix-delayed-stable-merge-check.patch

5.12-lucjan-ll39

- add block-Do-not-pull-requests-from-the-scheduler-when-w.patch

5.12-lucjan-ll38

- add btrfs-abort-the-transaction-if-we-fail-to-replay-log.patch
- add btrfs-check-error-value-from-btrfs_update_inode-in-t.patch
- add btrfs-do-not-infinite-loop-in-data-reclaim-if-we-abo.patch
- add btrfs-fix-error-handling-in-btrfs_del_csums.patch
- add btrfs-mark-ordered-extent-and-inode-with-error-if-we.patch
- add btrfs-return-errors-from-btrfs_del_csums-in-cleanup_.patch

5.12-lucjan-ll37

- add AUFS 20210517
- add spadfs-5.12-merge-v1.0.14.patch

5.12-lucjan-ll36

- add block-bfq-fix-delayed-stable-merge-check.patch

5.12-lucjan-ll35

- add btrfs-scrub-per-device-bandwidth-control.patch

5.12-lucjan-ll34-rc1 --> 5.12-lucjan-ll34

5.12-lucjan-ll34-rc1

- sync with upstream (update block-fix-trivial-typos-in-comments.patch)
- sync with upstream (drop drm-i915-dp-Use-slow-and-wide-link-training-for-ever.patch)
- sync with upstream (drop kyber-fix-out-of-bounds-access-when-preempted.patch)

5.12-lucjan-ll33

- add Revert-bus-mhi-core-Process-execution-environment-ch.patch

DROP 5.12-lucjan-ll33-rc1

5.12-lucjan-ll33-rc1

- sync with upstream (update block-fix-trivial-typos-in-comments.patch)
- sync with upstream (drop drm-i915-dp-Use-slow-and-wide-link-training-for-ever.patch)
- sync with upstream (drop kyber-fix-out-of-bounds-access-when-preempted.patch)

5.12-lucjan-ll32

- add init-Kconfig-add-O1-flag.patch

DROP 5.12-lucjan-ll32-rc1

5.12-lucjan-ll32-rc1

- sync with upstream (update block-fix-trivial-typos-in-comments.patch)
- sync with upstream (drop drm-i915-dp-Use-slow-and-wide-link-training-for-ever.patch)
- sync with upstream (drop kyber-fix-out-of-bounds-access-when-preempted.patch)

5.12-lucjan-ll31

- update futex2-resync-from-gitlab.collabora.com.patch

5.12-lucjan-ll30

- add init-wait-for-partition-and-retry-scan.patch 
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch

5.12-lucjan-ll29

- add fs-ntfs3-Fix-unsupported-flags-by-clang.patch

5.12-lucjan-ll28

- add btrfs-fix-removed-dentries-still-existing-after-log-.patch

5.12-lucjan-ll27-rc1 --> 5.12-lucjan-ll27

5.12-lucjan-ll27-rc1

- sync with upstream (update Port-microcode-patches.patch)

5.12-lucjan-ll26

- add drm-i915-dp-Use-slow-and-wide-link-training-for-ever.patch

DROP 5.12-lucjan-ll26-rc1

5.12-lucjan-ll26-rc1

- sync with upstream (update Port-microcode-patches.patch)

5.12-lucjan-ll25

- add Revert-block-bfq-avoid-circular-stable-merges.patch
- add block-bfq-avoid-circular-stable-merges.patch

DROP 5.12-lucjan-ll25-rc1

5.12-lucjan-ll25-rc1

- sync with upstream (update Port-microcode-patches.patch)

5.12-lucjan-ll24

- add block-elevator-remove-un-used-input-parameter-reques.patch
- add kyber-fix-out-of-bounds-access-when-preempted.patch

DROP 5.12-lucjan-ll24-rc1

5.12-lucjan-ll24-rc1

- sync with upstream (update Port-microcode-patches.patch)

5.12-lucjan-ll23-rc1 --> 5.12-lucjan-ll23-rc1

5.12-lucjan-ll23-rc1

- sync with upstream (drop btrfs-fix-race-between-transaction-aborts-and-fsyncs.patch)
- sync with upstream (drop block-bfq-fix-weight-raising-resume-with-low_latency.patch)

5.12-lucjan-ll22

- add mm-vmscan.c-fix-warnings-from-walk_pud_range.patch

DROP 5.12-lucjan-ll22-rc1

5.12-lucjan-ll22-rc1

- sync with upstream (drop btrfs-fix-race-between-transaction-aborts-and-fsyncs.patch)
- sync with upstream (drop block-bfq-fix-weight-raising-resume-with-low_latency.patch)

5.12-lucjan-ll21

- add igb-fix-netpoll-exit-with-traffic.patch

5.12-lucjan-ll20-rc1 --> 5.12-lucjan-ll20

5.12-lucjan-ll20-rc1

- add block-bfq-avoid-circular-stable-merges.patch

5.12-lucjan-ll19-rc1

- update futex2-resync-from-gitlab.collabora.com.patch

5.12-lucjan-ll18-rc1

- update futex2-resync-from-gitlab.collabora.com.patch

5.12-lucjan-ll17-rc1

- add Update-vmscan.c.patch

5.12-lucjan-ll16-rc1

- drop block-bfq-DEBUG-add-logs-and-BUG_ONs-to-for-next.patch
- drop block-bfq-DEBUG-add-BUG_ONs-to-bfq_reparent_leaf_ent.patch
- drop block-bfq-DEBUG-remove-useless-BUG_ON-in-bfq_pd_offl.patch
- drop block-bfq-DEBUG-check-that-queues-to-move-are-actual.patch
- drop block-bfq-DEBUG-log-and-check-total-number-of-reqs-q.patch
- drop block-bfq-DEBUG-log-early-exit-from-finish_requeue_r.patch
- drop block-bfq-DEBUG-move-check-bfqd-queued-to-lock-prote.patch
- drop block-bfq-DEBUG-print-weights-on-idle-busy-switch.patch
- drop block-bfq-DEBUG-improve-log-messages-in-handle_idle_.patch
- drop block-bfq-DEBUG-check-tot_busy-and-log-asymmetric-sc.patch
- drop block-bfq-DEBUG-log-I-O-intensity-parameters.patch
- drop block-bfq-DEBUG-print-all-pids-associated-with-a-sha.patch
- drop block-bfq-DEBUG-log-better_to_idle-in-handle_idle_bu.patch
- drop block-bfq-DEBUG-log-exact-actions-in-forced-stop-of-.patch
- drop block-bfq-DEBUG-add-BUG_ONs-and-logs-on-new-waker-de.patch
- drop block-bfq-DEBUG-add-more-logs-and-BUG_ONs-on-woken-l.patch
- drop block-bfq-DEBUG-add-detailed-log-on-denied-dispatch-.patch
- drop block-bfq-DEBUG-improve-detailed-log-on-denied-dispa.patch
- drop block-bfq-DEBUG-log-and-BUG_ONs-for-waker-inheritanc.patch
- drop block-bfq-DEBUG-avoid-double-del-of-same-task-from-t.patch
- drop block-bfq-DEBUG-logs-and-BUG_ONs-for-stable-merging.patch
- drop block-bfq-avoid-circular-stable-merges.patch
- drop block-bfq-DEBUG-add-BUG_ON-on-circular-stable-merge.patch
- add block-bfq-move-spin_unlock_irq-to-release-request-ou.patch
- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch
- add bfq-reset-entity-prio_changed-in-bfq_init_entity.patch
- add bfq-remove-unnecessary-BFQ_DEFAULT_GRP_IOPRIO.patch

5.12-lucjan-ll15-rc1

- drop block-bfq-move-spin_unlock_irq-to-release-request-ou.patch
- drop bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- drop bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- drop bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- drop bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- drop bfq-remove-unnecessary-initialization-logic.patch
- drop bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch
- drop bfq-reset-entity-prio_changed-in-bfq_init_entity.patch
- drop bfq-remove-unnecessary-BFQ_DEFAULT_GRP_IOPRIO.patch
- add block-bfq-DEBUG-add-logs-and-BUG_ONs-to-for-next.patch
- add block-bfq-DEBUG-add-BUG_ONs-to-bfq_reparent_leaf_ent.patch
- add block-bfq-DEBUG-remove-useless-BUG_ON-in-bfq_pd_offl.patch
- add block-bfq-DEBUG-check-that-queues-to-move-are-actual.patch
- add block-bfq-DEBUG-log-and-check-total-number-of-reqs-q.patch
- add block-bfq-DEBUG-log-early-exit-from-finish_requeue_r.patch
- add block-bfq-DEBUG-move-check-bfqd-queued-to-lock-prote.patch
- add block-bfq-DEBUG-print-weights-on-idle-busy-switch.patch
- add block-bfq-DEBUG-improve-log-messages-in-handle_idle_.patch
- add block-bfq-DEBUG-check-tot_busy-and-log-asymmetric-sc.patch
- add block-bfq-DEBUG-log-I-O-intensity-parameters.patch
- add block-bfq-DEBUG-print-all-pids-associated-with-a-sha.patch
- add block-bfq-DEBUG-log-better_to_idle-in-handle_idle_bu.patch
- add block-bfq-DEBUG-log-exact-actions-in-forced-stop-of-.patch
- add block-bfq-DEBUG-add-BUG_ONs-and-logs-on-new-waker-de.patch
- add block-bfq-DEBUG-add-more-logs-and-BUG_ONs-on-woken-l.patch
- add block-bfq-DEBUG-add-detailed-log-on-denied-dispatch-.patch
- add block-bfq-DEBUG-improve-detailed-log-on-denied-dispa.patch
- add block-bfq-DEBUG-log-and-BUG_ONs-for-waker-inheritanc.patch
- add block-bfq-DEBUG-avoid-double-del-of-same-task-from-t.patch
- add block-bfq-DEBUG-logs-and-BUG_ONs-for-stable-merging.patch
- add block-bfq-avoid-circular-stable-merges.patch
- add block-bfq-DEBUG-add-BUG_ON-on-circular-stable-merge.patch

5.12-lucjan-ll14-rc1

- add AUFS 20210503

5.12-lucjan-ll13-rc1

- add Project-C v5.12-r1

5.12-lucjan-ll12-rc1

- add mm-5.12-protect-file-mappings-under-memory-pressure.patch

5.12-lucjan-ll11-rc1

- add btrfs-check-worker-before-need_preemptive_reclaim.patch
- add btrfs-only-clamp-the-first-time-we-have-to-start-flu.patch
- add btrfs-don-t-include-the-global-rsv-size-in-the-preem.patch
- add btrfs-take-into-account-global-rsv-in-need_preemptiv.patch
- add btrfs-use-the-global-rsv-size-in-the-preemptive-thre.patch
- add btrfs-only-ignore-delalloc-if-delalloc-is-much-small.patch
- add btrfs-handle-preemptive-delalloc-flushing-slightly-d.patch
- add btrfs-avoid-RCU-stalls-while-running-delayed-iputs.patch

5.12-lucjan-ll10-rc1

- add zstd-5.12-update-to-submission-v11.patch

5.12-lucjan-ll9-rc1

- add sched-alt-Resync-with-lru-multigenerational.patch

5.12-lucjan-ll8-rc1

- drop mm-lru-5.12-protect-file-mappings-under-memory-pressure.patch

5.12-lucjan-ll7-rc1

- drop mm-5.12-protect-file-mappings-under-memory-pressure.patch
- add mm-lru-5.12-protect-file-mappings-under-memory-pressure.patch
- add include-linux-memcontrol.h-do-not-warn-in-page_memcg.patch
- add include-linux-nodemask.h-define-next_memory_node-if-.patch
- add include-linux-huge_mm.h-define-is_huge_zero_pmd-if-C.patch
- add include-linux-cgroup.h-export-cgroup_mutex.patch
- add mm-swap.c-export-activate_page.patch
- add mm-x86-support-the-access-bit-on-non-leaf-PMD-entrie.patch
- add mm-vmscan.c-refactor-shrink_node.patch
- add mm-multigenerational-lru-groundwork.patch
- add mm-multigenerational-lru-activation.patch
- add mm-multigenerational-lru-mm_struct-list.patch
- add mm-multigenerational-lru-aging.patch
- add mm-multigenerational-lru-eviction.patch
- add mm-multigenerational-lru-page-reclaim.patch
- add mm-multigenerational-lru-user-interface.patch
- add mm-multigenerational-lru-Kconfig.patch
- add mm-multigenerational-lru-documentation.patch

5.12-lucjan-ll6-rc1

- update futex2-resync-from-gitlab.collabora.com.patch

5.12-lucjan-ll5-rc1

- add sched-alt-Fix-WARNING-CPU-2-PID-26-at-kernel-sched-a.patch

5.12-lucjan-ll4-rc1

- add MAINTAINERS-Add-maintainer-entry-for-zstd.patch

5.12-lucjan-ll3-rc1

- add fs-ntfs3-Add-headers-and-misc-files.patch
- add fs-ntfs3-Add-initialization-of-super-block.patch
- add fs-ntfs3-Add-bitmap.patch
- add fs-ntfs3-Add-file-operations-and-implementation.patch
- add fs-ntfs3-Add-attrib-operations.patch
- add fs-ntfs3-Add-compression.patch
- add fs-ntfs3-Add-NTFS-journal.patch
- add fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- add fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- add fs-ntfs3-Add-MAINTAINERS.patch

5.12-lucjan-ll2-rc1

- fix bbr2-5.12-introduce-BBRv2.patch

5.12-lucjan-ll1-rc1

- add android-export-symbold-and-enable-building-ashmem-an.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add bbr2-5.12-introduce-BBRv2.patch
- add block-bfq-always-inject-I-O-of-queues-blocked-by-wak.patch
- add block-bfq-put-reqs-of-waker-and-woken-in-dispatch-li.patch
- add block-bfq-make-shared-queues-inherit-wakers.patch
- add block-bfq-fix-weight-raising-resume-with-low_latency.patch
- add block-bfq-keep-shared-queues-out-of-the-waker-mechan.patch
- add block-bfq-merge-bursts-of-newly-created-queues.patch
- add bfq-silence-lockdep-for-bfqd-ioc-lock-inversion.patch
- add block-bfq-fix-the-timeout-calculation-in-bfq_bfqq_ch.patch
- add block-bfq-move-spin_unlock_irq-to-release-request-ou.patch
- add blk-mq-bypass-IO-scheduler-s-limit_depth-for-passthr.patch
- add bfq-mq-deadline-remove-redundant-check-for-passthrou.patch
- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch
- add bfq-reset-entity-prio_changed-in-bfq_init_entity.patch
- add bfq-remove-unnecessary-BFQ_DEFAULT_GRP_IOPRIO.patch
- add block-bfq-set-bfq-lucjan-branding.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O.patch
- add block-Add-CONFIG-to-rename-the-mq-deadline-scheduler.patch
- add ZEN-Fix-mq-deadline-scheduler-renaming.patch
- add ZEN-Increase-max-elevator-name-size.patch
- add block-fix-trivial-typos-in-comments.patch
- add btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- add btrfs-do-not-evaluate-the-expression-with-CONFIG_BTR.patch
- add btrfs-restart-snapshot-delete-if-we-have-to-end-the-.patch
- add btrfs-use-percpu_read_positive-instead-of-sum_positi.patch
- add btrfs-add-btree-read-ahead-for-full-send-operations.patch
- add btrfs-add-btree-read-ahead-for-incremental-send-oper.patch
- add btrfs-fix-race-between-transaction-aborts-and-fsyncs.patch
- add btrfs-return-whole-extents-in-fiemap.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add print-fsync-count-for-bootchart.patch
- add clearlinux-5.12-port-Add-boot-option-to-allow-unsign.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add Port-microcode-patches.patch
- add cpu-5.12-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add mm-Disable-watermark-boosting-by-default.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch
- add kbuild-Disable-stack-conservation-for-GCC.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add ZEN-Add-OpenRGB-patches.patch
- add tty-Allow-setting-the-number-of-available-virtual-TT.patch
- add scsi-sd-Optimal-I-O-size-should-be-a-multiple-of-rep.patch
- add iomap-avoid-deadlock-if-memory-reclaim-is-triggered-.patch
- add xfs-log-stripe-roundoff-is-a-property-of-the-log.patch
- add xfs-separate-CIL-commit-record-IO.patch
- add xfs-journal-IO-cache-flush-reductions.patch
- add xfs-Fix-CIL-throttle-hang-when-CIL-space-used-going-.patch
- add xfs-reduce-buffer-log-item-shadow-allocations.patch
- add xfs-Skip-repetitive-warnings-about-mount-options.patch
- add nfsd-Ensure-knfsd-shuts-down-when-the-nfsd-pseudofs-.patch
- add xfs-No-need-for-inode-number-error-injection-in-__xf.patch
- add xfs-type-verification-is-expensive.patch
- add xfs-only-reset-incore-inode-health-state-flags-when-.patch
- add NFS-Fix-up-the-support-for-CONFIG_NFS_DISABLE_UDP_SU.patch
- add futex-resync-from-gitlab.collabora.com.patch
- add futex2-resync-from-gitlab.collabora.com.patch
- add init-initramfs.c-do-unpacking-asynchronously.patch
- add modules-add-CONFIG_MODPROBE_PATH.patch
- add Revert-net-tso-add-UDP-segmentation-support.patch
- add zen-Allow-MSR-writes-by-default.patch
- add mm-5.12-protect-file-mappings-under-memory-pressure.patch
- add genirq-i2c-Provide-and-use-generic_dispatch_irq.patch
- add spadfs-5.12-merge-v1.0.13.patch
- add v4l2loopback-5.12-merge-v0.12.5.patch
- add v4l2loopback-5.12-confine-v4l2loopback_cleanup_modul.patch
- add sched-autogroup-Add-kernel-parameter-and-config-opti.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add ZEN-vhba-Update-to-20210418.patch
- add lib-zstd-Add-kernel-specific-API.patch
- add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- add init-add-support-for-zstd-compressed-modules.patch
- add allow-setting-zstd-compression-level-for-kernel.patch
- add allow-setting-zstd-compression-level-for-modules.patch
- add init-optimize-zstd-compression-settings.patch
- add Project-C v5.12-r0
- add alt-Export-can_nice-symbol-for-Android-Binder-.patch
- add init-Kconfig-set-default-value-of-SCHED_PDS.patch
- add init-Kconfig-Restore-original-PDS-description.patch
- add sched-pds-1.1-Implement-bitmap-allocator.patch
- add sched-pds-Set-pds-dev-instead-of-pds.patch
- add UKSM for 5.12
- add AUFS 20210412

5.11-lucjan-ll86

- aufs-nodocs --> aufs (fix htmldocs error)

5.11-lucjan-ll85

- add ZEN-vhba-Update-to-20210418.patch

5.11-lucjan-ll84

- add block-bfq-improve-bfq-lucjan-branding.patch

5.11-lucjan-ll83

- add Revert-bfq-optimize-the-calculation-of-bfq_weight_to.patch
- add Revert-bfq-remove-unnecessary-initialization-logic.patch
- add Revert-bfq-disable-merging-between-different-groups-.patch
- add Revert-bfq-disable-idle-for-prio_expire-under-better.patch
- add Revert-bfq-optimize-IO-injection-under-better_fairne.patch
- add Revert-bfq-expire-in_serv_queue-for-prio_expire-unde.patch
- add Revert-bfq-introduce-prio_expire-flag-for-bfq_queue.patch
- add Revert-bfq-introduce-better_fairness-for-container-s.patch
- add Revert-bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- add Revert-bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- add Revert-bfq-introduce-bfq_ioprio_class-to-get-ioprio-.patch
- add Revert-bfq-introduce-bfq.ioprio-for-cgroup.patch
- add Revert-bfq-convert-the-type-of-bfq_group.bfqd-to-bfq.patch
- add Revert-bfq-introduce-bfq_entity_to_bfqg-helper-metho.patch
- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch
- add bfq-reset-entity-prio_changed-in-bfq_init_entity.patch
- add bfq-remove-unnecessary-BFQ_DEFAULT_GRP_IOPRIO.patch

5.11-lucjan-ll82

- add block-bfq-set-bfq-lucjan-branding.patch

5.11-lucjan-ll81

- add blk-mq-bypass-IO-scheduler-s-limit_depth-for-passthr.patch
- add bfq-mq-deadline-remove-redundant-check-for-passthrou.patch

5.11-lucjan-ll80

- add block-bfq-move-spin_unlock_irq-to-release-request-ou.patch

5.11-lucjan-ll79

- add drm-i915-ilk-glk-Fix-link-training-on-links-with-LTT.patch
- add drm-i915-dp-Prevent-setting-the-LTTPR-LT-mode-if-no-.patch
- add drm-i915-Disable-LTTPR-support-when-the-DPCD-rev-1.4.patch
- add drm-i915-Fix-modesetting-in-case-of-unexpected-AUX-t.patch
- drop iommu-amd-Don-t-initialise-remapping-irqdomain-if-IO.patch

5.11-lucjan-ll78

- add AUFS 20210412

5.11-lucjan-ll77

- update cpu-5.11-merge-graysky-s-patchset.patch

5.11-lucjan-ll76

- drop drm-i915-ilk-glk-Fix-link-training-on-links-with-LTT.patch
- drop drm-i915-dp-Prevent-setting-the-LTTPR-LT-mode-if-no-.patch
- drop drm-i915-Disable-LTTPR-support-when-the-DPCD-rev-1.4.patch

5.11-lucjan-ll75

- add btrfs-fix-race-between-transaction-aborts-and-fsyncs.patch
- add btrfs-return-whole-extents-in-fiemap.patch

5.11-lucjan-ll74

- add mm-5.11-do-not-disable-file-pages-protection-under-d.patch

5.11-lucjan-ll73

- add mm-5.11-nits-on-branching.patch
- add mm-5.11-remove-WARN_ON-since-it-really-can-happen-du.patch
- add mm-5.11-call-node_page_state-closer-to-each-other.patch
- add mm-5.11-explain-non-atomicity.patch

5.11-lucjan-ll72

- add mm-5.11-do-not-protect-dirty-pages.patch
- add mm-5.11-be-more-concise-about-clean-pages.patch

5.11-lucjan-ll71

- add btrfs-add-btree-read-ahead-for-full-send-operations.patch
- add btrfs-add-btree-read-ahead-for-incremental-send-oper.patch

5.11-lucjan-ll70

- add Makefile-use-smaller-dictionary-size-for-xz-module-c.patch (sync with 5.12-rc)
- update init-add-support-for-zstd-compressed-modules.patch (sync with linux-next)
- update allow-setting-zstd-compression-level-for-modules.patch (sync with linux-next)

5.11-lucjan-ll69

- add NFS-Fix-up-the-support-for-CONFIG_NFS_DISABLE_UDP_SU.patch

5.11-lucjan-ll68

- add drm-i915-ilk-glk-Fix-link-training-on-links-with-LTT.patch
- add drm-i915-dp-Prevent-setting-the-LTTPR-LT-mode-if-no-.patch
- add drm-i915-Disable-LTTPR-support-when-the-DPCD-rev-1.4.patch

5.11-lucjan-ll67

- add initrd-Add-the-preprocessor-guard-in-initrd.h.patch
- add initramfs-Provide-a-common-initrd-reserve-function.patch
- add riscv-Covert-to-reserve_initrd_mem.patch
- add init-initramfs.c-do-unpacking-asynchronously.patch
- add modules-add-CONFIG_MODPROBE_PATH.patch

5.11-lucjan-ll66

- add ntfs3-5.11-update-to-v26.patch

5.11-lucjan-ll65

- update allow-setting-zstd-compression-level-for-modules.patch

5.11-lucjan-ll64

- add allow-setting-zstd-compression-level-for-kernel.patch
- add allow-setting-zstd-compression-level-for-modules.patch

5.11-lucjan-ll63

- update cpu-5.11-merge-graysky-s-patchset.patch

5.11-lucjan-ll62

- update init-add-support-for-zstd-compressed-modules.patch

5.11-lucjan-ll61

- add btrfs-use-percpu_read_positive-instead-of-sum_positi.patch

5.11-lucjan-ll60

- update init-add-support-for-zstd-compressed-modules.patch

5.11-lucjan-ll59

- add Revert-zstd-5.11-export-ZSTD_maxCLevel.patch
- add zstd-5.11-update-to-1.4.10-v9.patch

5.11-lucjan-ll58-rc1 --> 5.11-lucjan-ll58

5.11-lucjan-ll58-rc1

- sync with upstream (drop btrfs-fix-sleep-while-in-non-sleep-context-during-qg.patch)
- sync with upstream (drop z3fold-prevent-reclaim-free-race-for-headless-pages.patch)

5.11-lucjan-ll57

- add Project-C v5.11-r3

DROP 5.11-lucjan-ll57-rc1

5.11-lucjan-ll57-rc1

- sync with upstream (drop btrfs-fix-sleep-while-in-non-sleep-context-during-qg.patch)
- sync with upstream (drop z3fold-prevent-reclaim-free-race-for-headless-pages.patch)

5.11-lucjan-ll56

- drop lib-zstd-Add-kernel-specific-API.patch (ZSTD 1.4.6)
- drop lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch (ZSTD 1.4.6)
- drop lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch (ZSTD 1.4.6) 
- add lib-zstd-Add-kernel-specific-API.patch (ZSTD 1.4.10)
- add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch (ZSTD 1.4.10)
- add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch (ZSTD 1.4.10)
- add zstd-5.11-export-ZSTD_maxCLevel.patch (ZSTD 1.4.10)

DROP 5.11-lucjan-ll56-rc1

5.11-lucjan-ll56-rc1

- sync with upstream (drop btrfs-fix-sleep-while-in-non-sleep-context-during-qg.patch)
- sync with upstream (drop z3fold-prevent-reclaim-free-race-for-headless-pages.patch)

5.11-lucjan-ll55

- add ntfs3-5.11-update-to-v25.patch

DROP 5.11-lucjan-ll55-rc1

5.11-lucjan-ll55-rc1

- sync with upstream (drop btrfs-fix-sleep-while-in-non-sleep-context-during-qg.patch)
- sync with upstream (drop z3fold-prevent-reclaim-free-race-for-headless-pages.patch)

5.11-lucjan-ll54

- update cpu-5.11-merge-graysky-s-patchset.patch

DROP 5.11-lucjan-ll54-rc1

5.11-lucjan-ll54-rc1

- sync with upstream (drop btrfs-fix-sleep-while-in-non-sleep-context-during-qg.patch)
- sync with upstream (drop z3fold-prevent-reclaim-free-race-for-headless-pages.patch)

5.11-lucjan-ll53

- update cpu-5.11-merge-graysky-s-patchset.patch

5.11-lucjan-ll52

- add block-fix-trivial-typos-in-comments.patch

5.11-lucjan-ll51

- add xfs-only-reset-incore-inode-health-state-flags-when-.patch

5.11-lucjan-ll50

- add Revert-bfq-optimize-the-calculation-of-bfq_weight_to.patch
- add Revert-bfq-remove-unnecessary-initialization-logic.patch
- add Revert-bfq-disallow-merge-CLASS_RT-with-other-class.patch
- add Revert-bfq-disallow-idle-if-CLASS_RT-waiting-for-ser.patch
- add Revert-bfq-optimse-IO-injection-for-CLASS_RT.patch
- add Revert-bfq-expire-other-class-if-CLASS_RT-is-waiting.patch
- add Revert-bfq-keep-the-minimun-bandwidth-for-be_class.patch
- add Revert-bfq-limit-the-IO-depth-of-idle_class-to-1.patch
- add Revert-bfq-introduce-bfq.ioprio-for-cgroup.patch
- add Revert-bfq-convert-the-type-of-bfq_group.bfqd-to-bfq.patch
- add Revert-bfq-introduce-bfq_entity_to_bfqg-helper-metho.patch
- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-introduce-bfq.ioprio-for-cgroup.patch
- add bfq-introduce-bfq_ioprio_class-to-get-ioprio-class.patch
- add bfq-limit-the-IO-depth-of-CLASS_IDLE-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-CLASS_BE.patch
- add bfq-introduce-better_fairness-for-container-scene.patch
- add bfq-introduce-prio_expire-flag-for-bfq_queue.patch
- add bfq-expire-in_serv_queue-for-prio_expire-under-bette.patch
- add bfq-optimize-IO-injection-under-better_fairness.patch
- add bfq-disable-idle-for-prio_expire-under-better_fairne.patch
- add bfq-disable-merging-between-different-groups-under-b.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch

5.11-lucjan-ll49

- add block-bfq-fix-the-timeout-calculation-in-bfq_bfqq_ch.patch

5.11-lucjan-ll48

- add AUFS 20210308

5.11-lucjan-ll47

- update lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch

5.11-lucjan-ll46

- add ntfs3-5.11-update-to-v24.patch

5.11-lucjan-ll45

- update init-add-support-for-zstd-compressed-modules.patch

5.11-lucjan-ll44

- add btrfs-fix-sleep-while-in-non-sleep-context-during-qg.patch

5.11-lucjan-ll43

- add xfs-No-need-for-inode-number-error-injection-in-__xf.patch
- add xfs-type-verification-is-expensive.patch

5.11-lucjan-ll42

- add bfq-silence-lockdep-for-bfqd-ioc-lock-inversion.patch

5.11-lucjan-ll41

- add mm-use-add_page_to_lru_list.patch
- add mm-shuffle-lru-list-addition-and-deletion-functions.patch
- add mm-don-t-pass-enum-lru_list-to-lru-list-addition-fun.patch
- add mm-don-t-pass-enum-lru_list-to-trace_mm_lru_insertio.patch
- add mm-don-t-pass-enum-lru_list-to-del_page_from_lru_lis.patch
- add mm-add-__clear_page_lru_flags-to-replace-page_off_lr.patch
- add mm-VM_BUG_ON-lru-page-flags.patch
- add mm-fold-page_lru_base_type-into-its-sole-caller.patch
- add mm-fold-__update_lru_size-into-its-sole-caller.patch
- add mm-make-lruvec_lru_size-static.patch

5.11-lucjan-ll40

- add nfsd-Ensure-knfsd-shuts-down-when-the-nfsd-pseudofs-.patch

5.11-lucjan-ll39-rc1 --> 5.11-lucjan-ll39

5.11-lucjan-ll39-rc1

- sync with upstream (drop drm-amdgpu-display-simplify-backlight-setting.patch)
- sync with upstream (drop drm-amdgpu-display-don-t-assert-in-set-backlight-fun.patch)
- sync with upstream (drop drm-amdgpu-display-handle-aux-backlight-in-backlight.patch)
- sync with upstream (drop block-Try-to-handle-busy-underlying-device-on-discar.patch)

5.11-lucjan-ll38

- add ntfs3-5.11-update-to-v23.patch

DROP 5.11-lucjan-ll38-rc1

5.11-lucjan-ll38-rc1

- sync with upstream (drop drm-amdgpu-display-simplify-backlight-setting.patch)
- sync with upstream (drop drm-amdgpu-display-don-t-assert-in-set-backlight-fun.patch)
- sync with upstream (drop drm-amdgpu-display-handle-aux-backlight-in-backlight.patch)
- sync with upstream (drop block-Try-to-handle-busy-underlying-device-on-discar.patch)

5.11-lucjan-ll37

- add iommu-amd-Don-t-initialise-remapping-irqdomain-if-IO.patch

DROP 5.11-lucjan-ll37-rc1

5.11-lucjan-ll37-rc1

- sync with upstream (drop drm-amdgpu-display-simplify-backlight-setting.patch)
- sync with upstream (drop drm-amdgpu-display-don-t-assert-in-set-backlight-fun.patch)
- sync with upstream (drop drm-amdgpu-display-handle-aux-backlight-in-backlight.patch)
- sync with upstream (drop block-Try-to-handle-busy-underlying-device-on-discar.patch)

5.11-lucjan-ll36

- update cpu-5.11-merge-graysky-s-patchset.patch

DROP 5.11-lucjan-ll36-rc2

5.11-lucjan-ll36-rc2

- sync with upstream (drop block-Try-to-handle-busy-underlying-device-on-discar.patch)

5.11-lucjan-ll36-rc1

- sync with upstream (drop drm-amdgpu-display-simplify-backlight-setting.patch)
- sync with upstream (drop drm-amdgpu-display-don-t-assert-in-set-backlight-fun.patch)
- sync with upstream (drop drm-amdgpu-display-handle-aux-backlight-in-backlight.patch)

5.11-lucjan-ll35

- add Revert-bfq-optimize-the-calculation-of-bfq_weight_to.patch
- add Revert-bfq-remove-unnecessary-initialization-logic.patch
- add Revert-bfq-convert-the-type-of-bfq_group.bfqd-to-bfq.patch
- add Revert-bfq-introduce-bfq.ioprio-for-cgroup.patch
- add Revert-bfq-expire-bfqq-if-a-higher-priority-class-is.patch
- add Revert-bfq-keep-the-minimun-bandwidth-for-be_class.patch
- add Revert-bfq-limit-the-IO-depth-of-idle_class-to-1.patch
- add Revert-bfq-introduce-bfq_entity_to_bfqg-helper-metho.patch
- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-introduce-bfq.ioprio-for-cgroup.patch
- add bfq-limit-the-IO-depth-of-idle_class-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-be_class.patch
- add bfq-expire-other-class-if-CLASS_RT-is-waiting.patch
- add bfq-optimse-IO-injection-for-CLASS_RT.patch
- add bfq-disallow-idle-if-CLASS_RT-waiting-for-service.patch
- add bfq-disallow-merge-CLASS_RT-with-other-class.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch

5.11-lucjan-ll34

- add spadfs-5.11-merge-v1.0.13.patch

5.11-lucjan-ll33-rc1 --> 5.11-lucjan-ll33

5.11-lucjan-ll33-rc1

- sync with upstream (drop btrfs-Fix-race-between-extent-freeing-allocation-whe.patch)
- sync with upstream (drop btrfs-do-not-error-out-if-the-extent-ref-hash-doesn-.patch)
- sync with upstream (drop btrfs-Unlock-extents-in-btrfs_zero_range-in-case-of-.patch)

5.11-lucjan-ll32

- update cpu-5.11-merge-graysky-s-patchset.patch

DROP 5.11-lucjan-ll32-rc1

5.11-lucjan-ll32-rc1

- sync with upstream (drop btrfs-Fix-race-between-extent-freeing-allocation-whe.patch)
- sync with upstream (drop btrfs-do-not-error-out-if-the-extent-ref-hash-doesn-.patch)
- sync with upstream (drop btrfs-Unlock-extents-in-btrfs_zero_range-in-case-of-.patch)

5.11-lucjan-ll31

- add bfq-introduce-bfq_entity_to_bfqg-helper-method.patch
- add bfq-limit-the-IO-depth-of-idle_class-to-1.patch
- add bfq-keep-the-minimun-bandwidth-for-be_class.patch
- add bfq-expire-bfqq-if-a-higher-priority-class-is-waitin.patch
- add bfq-introduce-bfq.ioprio-for-cgroup.patch
- add bfq-convert-the-type-of-bfq_group.bfqd-to-bfq_data.patch
- add bfq-remove-unnecessary-initialization-logic.patch
- add bfq-optimize-the-calculation-of-bfq_weight_to_ioprio.patch

DROP 5.11-lucjan-ll31-rc1

5.11-lucjan-ll31-rc1

- sync with upstream (drop btrfs-Fix-race-between-extent-freeing-allocation-whe.patch)
- sync with upstream (drop btrfs-do-not-error-out-if-the-extent-ref-hash-doesn-.patch)
- sync with upstream (drop btrfs-Unlock-extents-in-btrfs_zero_range-in-case-of-.patch)

5.11-lucjan-ll30

- add Project-C v5.11-r2

DROP 5.11-lucjan-ll30-rc1

5.11-lucjan-ll30-rc1

- sync with upstream (drop btrfs-Fix-race-between-extent-freeing-allocation-whe.patch)
- sync with upstream (drop btrfs-do-not-error-out-if-the-extent-ref-hash-doesn-.patch)
- sync with upstream (drop btrfs-Unlock-extents-in-btrfs_zero_range-in-case-of-.patch)

5.11-lucjan-ll29

- update cpu-5.11-merge-graysky-s-patchset.patch
- drop Documentation-Fix-sphinx-3.5-causes-compilation-erro.patch

DROP 5.11-lucjan-ll29-rc1

5.11-lucjan-ll29-rc1

- sync with upstream (drop btrfs-Fix-race-between-extent-freeing-allocation-whe.patch)
- sync with upstream (drop btrfs-do-not-error-out-if-the-extent-ref-hash-doesn-.patch)
- sync with upstream (drop btrfs-Unlock-extents-in-btrfs_zero_range-in-case-of-.patch)

5.11-lucjan-ll28

- add Revert-block-bfq-merge-bursts-of-newly-created-queue.patch
- add Revert-block-bfq-keep-shared-queues-out-of-the-waker.patch
- add Revert-block-bfq-fix-weight-raising-resume-with-low_.patch
- add Revert-block-bfq-make-shared-queues-inherit-wakers.patch
- add Revert-block-bfq-put-reqs-of-waker-and-woken-in-disp.patch
- add Revert-block-bfq-always-inject-I-O-of-queues-blocked.patch
- add block-bfq-always-inject-I-O-of-queues-blocked-by-wak.patch (V2)
- add block-bfq-put-reqs-of-waker-and-woken-in-dispatch-li.patch (V2)
- add block-bfq-make-shared-queues-inherit-wakers.patch (V2)
- add block-bfq-fix-weight-raising-resume-with-low_latency.patch (V2)
- add block-bfq-keep-shared-queues-out-of-the-waker-mechan.patch (V2)
- add block-bfq-merge-bursts-of-newly-created-queues.patch (V2)

5.11-lucjan-ll27-rc1 --> 5.11-lucjan-ll27

5.11-lucjan-ll27-rc1

- sync with upstream (drop Revert-drm-amd-display-reuse-current-context-instead.patch)
- sync with upstream (drop drm-amdgpu-fix-shutdown-with-s0ix.patch)
- sync with upstream (drop smp-Process-pending-softirqs-in-flush_smp_call_funct.patch)
- sync with upstream (drop btrfs-handle-total_bytes_pinned-inside-the-delayed-r.patch)
- sync with upstream (drop btrfs-account-for-new-extents-being-deleted-in-total.patch)
- sync with upstream (drop drm-amd-display-Remove-Assert-from-dcn10_get_dig_fro.patch)
- sync with upstream (drop bfq-Avoid-false-bfq-queue-merging.patch)

5.11-lucjan-ll26

- add ntfs3-5.11-update-to-v22.patch

DROP 5.11-lucjan-ll26-rc2

5.11-lucjan-ll26-rc2

- sync with upstream (drop Revert-drm-amd-display-reuse-current-context-instead.patch)
- sync with upstream (drop drm-amdgpu-fix-shutdown-with-s0ix.patch)
- sync with upstream (drop smp-Process-pending-softirqs-in-flush_smp_call_funct.patch)
- sync with upstream (drop btrfs-handle-total_bytes_pinned-inside-the-delayed-r.patch)
- sync with upstream (drop btrfs-account-for-new-extents-being-deleted-in-total.patch)
- sync with upstream (drop drm-amd-display-Remove-Assert-from-dcn10_get_dig_fro.patch)

5.11-lucjan-ll26-rc1

- sync with upstream (drop bfq-Avoid-false-bfq-queue-merging.patch)

5.11-lucjan-ll25

- add locking-mutex-Don-t-hog-RCU-read-lock-while-optimist.patch
- add locking-rwsem-Don-t-hog-RCU-read-lock-while-optimist.patch

DROP DROP 5.11-lucjan-ll25-rc1

5.11-lucjan-ll25-rc1

- sync with upstream (drop bfq-Avoid-false-bfq-queue-merging.patch)

5.11-lucjan-ll24

- add Project-C v5.11-r1

DROP 5.11-lucjan-ll24-rc1

5.11-lucjan-ll24-rc1

- sync with upstream (drop bfq-Avoid-false-bfq-queue-merging.patch)

5.11-lucjan-ll23

- drop BFQ-dev 20210223
- add block-bfq-use-half-slice_idle-as-a-threshold-to-chec.patch
- add block-bfq-set-next_rq-to-waker_bfqq-next_rq-in-waker.patch
- add block-bfq-increase-time-window-for-waker-detection.patch
- add block-bfq-do-not-raise-non-default-weights.patch
- add block-bfq-avoid-spurious-switches-to-soft_rt-of-inte.patch
- add block-bfq-do-not-expire-a-queue-when-it-is-the-only-.patch
- add block-bfq-replace-mechanism-for-evaluating-I-O-inten.patch
- add block-bfq-re-evaluate-convenience-of-I-O-plugging-on.patch
- add block-bfq-fix-switch-back-from-soft-rt-weitgh-raisin.patch
- add block-bfq-save-also-weight-raised-service-on-queue-m.patch
- add block-bfq-save-also-injection-state-on-queue-merging.patch
- add block-bfq-make-waker-queue-detection-more-robust.patch
- add bfq-bfq_check_waker-should-be-static.patch
- add block-bfq-always-inject-I-O-of-queues-blocked-by-wak.patch
- add block-bfq-put-reqs-of-waker-and-woken-in-dispatch-li.patch
- add block-bfq-make-shared-queues-inherit-wakers.patch
- add block-bfq-fix-weight-raising-resume-with-low_latency.patch
- add block-bfq-keep-shared-queues-out-of-the-waker-mechan.patch
- add block-bfq-merge-bursts-of-newly-created-queues.patch
- add bfq-don-t-duplicate-code-for-different-paths.patch
- add bfq-Avoid-false-bfq-queue-merging.patch
- add bfq-Use-ttime-local-variable.patch
- add bfq-Use-only-idle-IO-periods-for-think-time-calculat.patch
- add block-bfq-update-comments-and-default-value-in-docs-.patch
- add Revert-blk-mq-elevator-Count-requests-per-hctx-to-im.patch

5.11-lucjan-ll22

- add smp-Process-pending-softirqs-in-flush_smp_call_funct.patch

5.11-lucjan-ll21

- add blk-mq-Always-complete-remote-completions-requests-i.patch
- add blk-mq-Use-llist_head-for-blk_cpu_done.patch

5.11-lucjan-ll20-rc1 --> 5.11-lucjan-ll20

5.11-lucjan-ll20-rc1

- sync with upstream (drop Bluetooth-btusb-Some-Qualcomm-Bluetooth-adapters-sto.patch)

5.11-lucjan-ll19-rc1 --> 5.11-lucjan-ll19

5.11-lucjan-ll19-rc1

- add btrfs-Unlock-extents-in-btrfs_zero_range-in-case-of-.patch

5.11-lucjan-ll18-rc1

- add drm-amdgpu-display-simplify-backlight-setting.patch
- add drm-amdgpu-display-don-t-assert-in-set-backlight-fun.patch
- add drm-amdgpu-display-handle-aux-backlight-in-backlight.patch
- add xfs-don-t-reuse-busy-extents-on-extent-trim.patch

5.11-lucjan-ll17-rc1

- add BFQ-dev 20210223

5.11-lucjan-ll16-rc1

- update UKSM for 5.11

5.11-lucjan-ll15-rc1

- add AUFS 20210222

5.11-lucjan-ll14-rc1

- add drm-amd-display-Remove-Assert-from-dcn10_get_dig_fro.patch
- add xfs-Skip-repetitive-warnings-about-mount-options.patch

5.11-lucjan-ll13-rc1

- add mm-5.11-simplify-file_is_low.patch

5.11-lucjan-ll12-rc1

- drop Revert-block-Do-not-discard-buffers-under-a-mounted-.patch
- add block-Try-to-handle-busy-underlying-device-on-discar.patch

5.11-lucjan-ll11-rc1

- add btrfs-do-not-error-out-if-the-extent-ref-hash-doesn-.patch

5.11-lucjan-ll10-rc1

- add Revert-drm-amd-display-reuse-current-context-instead.patch
- add drm-amdgpu-fix-shutdown-with-s0ix.patch

5.11-lucjan-ll9-rc1

- add mm-5.11-v2-of-zsmalloc-vs-zswap-fixes.patch

5.11-lucjan-ll8-rc1

- add Bluetooth-btusb-Some-Qualcomm-Bluetooth-adapters-sto.patch

5.11-lucjan-ll7-rc1

- update futex2-resync-from-gitlab.collabora.com.patch

5.11-lucjan-ll6-rc1

- update Export-symbols-needed-by-Android-drivers.patch

5.11-lucjan-ll5-rc1

- update bbr2-5.11-introduce-BBRv2.patch

5.11-lucjan-ll4-rc1

- add SUNRPC-Set-TCP_CORK-until-the-transmit-queue-is-empt.patch
- add SUNRPC-Use-TCP_CORK-to-optimise-send-performance-on-.patch
- add SUNRPC-Remove-redundant-socket-flags-from-svc_tcp_se.patch
- add xfs-log-stripe-roundoff-is-a-property-of-the-log.patch
- add xfs-separate-CIL-commit-record-IO.patch
- add xfs-journal-IO-cache-flush-reductions.patch
- add xfs-Fix-CIL-throttle-hang-when-CIL-space-used-going-.patch
- add xfs-reduce-buffer-log-item-shadow-allocations.patch

5.11-lucjan-ll3-rc1

- update futex2-resync-from-gitlab.collabora.com.patch

5.11-lucjan-ll2-rc1

- add AUFS 20210215

5.11-lucjan-ll1-rc1

- add Export-symbols-needed-by-Android-drivers.patch
- add android-Enable-building-ashmem-and-binder-as-modules.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add bbr2-5.11-introduce-BBRv2.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O.patch
- add block-Add-CONFIG-to-rename-the-mq-deadline-scheduler.patch
- add ZEN-Fix-mq-deadline-scheduler-renaming.patch
- add blk-mq-Improve-performance-of-non-mq-IO-schedulers-w.patch
- add ZEN-Increase-max-elevator-name-size.patch
- add btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- add btrfs-do-not-evaluate-the-expression-with-CONFIG_BTR.patch
- add btrfs-do-not-block-on-deleted-bgs-mutex-in-the-clean.patch
- add btrfs-only-let-one-thread-pre-flush-delayed-refs-in-.patch
- add btrfs-delayed-refs-pre-flushing-should-only-run-the-.patch
- add btrfs-only-run-delayed-refs-once-before-committing.patch
- add btrfs-move-delayed-ref-flushing-for-qgroup-into-qgro.patch
- add btrfs-remove-bogus-BUG_ON-in-alloc_reserved_tree_blo.patch
- add btrfs-stop-running-all-delayed-refs-during-snapshot.patch
- add btrfs-run-delayed-refs-less-often-in-commit_cowonly_.patch
- add btrfs-make-flush_space-take-a-enum-btrfs_flush_state.patch
- add btrfs-add-a-trace-point-for-reserve-tickets.patch
- add btrfs-track-ordered-bytes-instead-of-just-dio-ordere.patch
- add btrfs-introduce-a-FORCE_COMMIT_TRANS-flush-operation.patch
- add btrfs-improve-preemptive-background-space-flushing.patch
- add btrfs-rename-need_do_async_reclaim.patch
- add btrfs-check-reclaim_size-in-need_preemptive_reclaim.patch
- add btrfs-rework-btrfs_calc_reclaim_metadata_size.patch
- add btrfs-simplify-the-logic-in-need_preemptive_flushing.patch
- add btrfs-implement-space-clamping-for-preemptive-flushi.patch
- add btrfs-adjust-the-flush-trace-point-to-include-the-so.patch
- add btrfs-add-a-trace-class-for-dumping-the-current-ENOS.patch
- add btrfs-restart-snapshot-delete-if-we-have-to-end-the-.patch
- add btrfs-handle-total_bytes_pinned-inside-the-delayed-r.patch
- add btrfs-account-for-new-extents-being-deleted-in-total.patch
- add btrfs-remove-unnecessary-directory-inode-item-update.patch
- add btrfs-stop-setting-nbytes-when-filling-inode-item-fo.patch
- add btrfs-avoid-logging-new-ancestor-inodes-when-logging.patch
- add btrfs-skip-logging-directories-already-logged-when-l.patch
- add btrfs-skip-logging-inodes-already-logged-when-loggin.patch
- add btrfs-remove-unnecessary-check_parent_dirs_for_sync.patch
- add btrfs-make-concurrent-fsyncs-wait-less-when-waiting-.patch
- add btrfs-Fix-race-between-extent-freeing-allocation-whe.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add Port-microcode-patches.patch
- add cpu-5.11-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add mm-Disable-watermark-boosting-by-default.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch
- add kbuild-Disable-stack-conservation-for-GCC.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add ZEN-Add-OpenRGB-patches.patch
- add tty-Allow-setting-the-number-of-available-virtual-TT.patch
- add scsi-sd-Optimal-I-O-size-should-be-a-multiple-of-rep.patch
- add iomap-avoid-deadlock-if-memory-reclaim-is-triggered-.patch
- add mm-Add-become_kswapd-and-restore_kswapd.patch
- add xfs-fix-an-ABBA-deadlock-in-xfs_rename.patch
- add xfs-use-memalloc_nofs_-save-restore-in-xfs-transacti.patch
- add xfs-refactor-the-usage-around-xfs_trans_context_-set.patch
- add xfs-use-current-journal_info-to-avoid-transaction-re.patch
- add xfs-set-inode-size-after-creating-symlink.patch
- add vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch
- add xfs-restore-shutdown-check-in-mapped-write-fault-pat.patch
- add futex-resync-from-gitlab.collabora.com.patch
- add futex2-resync-from-gitlab.collabora.com.patch
- add Revert-net-tso-add-UDP-segmentation-support.patch
- add zen-Allow-MSR-writes-by-default.patch
- add mm-5.11-protect-file-mappings-under-memory-pressure.patch
- add mm-5.11-inequality-should-not-exclude-lower-threshol.patch
- add mm-5.11-throttle-file-pages-scan-regardless-of-scan-.patch
- add fs-ntfs3-Add-headers-and-misc-files.patch
- add fs-ntfs3-Add-initialization-of-super-block.patch
- add fs-ntfs3-Add-bitmap.patch
- add fs-ntfs3-Add-file-operations-and-implementation.patch
- add fs-ntfs3-Add-attrib-operations.patch
- add fs-ntfs3-Add-compression.patch
- add fs-ntfs3-Add-NTFS-journal.patch
- add fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- add fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- add fs-ntfs3-Add-MAINTAINERS.patch
- add ntfs3-5.11-throw-away-userns-changes-from-linux-next.patch
- add genirq-i2c-Provide-and-use-generic_dispatch_irq.patch
- add HID-logitech-hidpp-add-support-for-Unified-Battery-1.patch
- add mm-compaction-correct-deferral-logic-for-proactive-c.patch
- add z3fold-prevent-reclaim-free-race-for-headless-pages.patch
- add Revert-block-Do-not-discard-buffers-under-a-mounted-.patch
- add Project-C v5.11-r0
- add alt-Export-can_nice-symbol-for-Android-Binder-.patch
- add init-Kconfig-set-default-value-of-SCHED_PDS.patch
- add init-Kconfig-Restore-original-PDS-description.patch
- add sched-pds-1.1-Implement-bitmap-allocator.patch
- add sched-pds-Set-pds-dev-instead-of-pds.patch
- add spadfs-5.11-merge-v1.0.12.patch
- add v4l2loopback-5.11-merge-v0.12.5.patch
- add sched-autogroup-Add-kernel-parameter-and-config-opti.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add lib-zstd-Add-kernel-specific-API.patch
- add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- add init-add-support-for-zstd-compressed-modules.patch
- add mm-zswap-add-the-flag-can_sleep_mapped.patch
- add mm-zswap-fix-potential-memory-leak.patch
- add mm-zswap-fix-variable-entry-is-uninitialized-when-us.patch
- add mm-set-the-sleep_mapped-to-true-for-zbud-and-z3fold.patch
- add BFQ-dev 20210208
- add UKSM for 5.11
- add AUFS 20210111

5.10-lucjan-ll86-rc1

- sync with upstream (drop btrfs-fix-crash-after-non-aligned-direct-IO-write-wi.patch)

5.10-lucjan-ll85

- add Documentation-Fix-sphinx-3.5-causes-compilation-erro.patch

5.10-lucjan-ll84-rc1 --> 5.10-lucjan-ll84

5.10-lucjan-ll84-rc1

- add BFQ-dev 20210214

5.10-lucjan-ll83

- add btrfs-fix-crash-after-non-aligned-direct-IO-write-wi.patch

5.10-lucjan-ll82

- add ntfs3-5.10-update-to-v21.patch

5.10-lucjan-ll80

- add Revert-radeon-amdgpu-Firmware-is-required-for-DRM-an.pat

5.10-lucjan-ll80

- add init-enable-FUTEX2.patch

5.10-lucjan-ll79

- add xfs-restore-shutdown-check-in-mapped-write-fault-pat.patch

5.10-lucjan-ll78

- add sched-pds-Set-pds-dev-instead-of-pds.patch

5.10-lucjan-ll77-rc1 --> 5.10-lucjan-ll77

5.10-lucjan-ll77-rc1

- resync vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch

5.10-lucjan-ll76

- update bbr2-5.10-introduce-BBRv2.patch
- add btrfs-Fix-race-between-extent-freeing-allocation-whe.patch

DROP 5.10-lucjan-ll76-rc1

5.10-lucjan-ll76-rc1

- resync vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch

5.10-lucjan-ll75

- add radeon-amdgpu-Firmware-is-required-for-DRM-and-KMS-o.patch

DROP 5.10-lucjan-ll75-rc1

5.10-lucjan-ll75-rc1

- resync vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch

5.10-lucjan-ll74

- add ntfs3-5.10-update-to-v20.patch

5.10-lucjan-ll73-rc1 --> 5.10-lucjan-ll73

5.10-lucjan-ll73-rc1

- sync with upstream (drop iwlwifi-provide-gso_type-to-GSO-packets.patch)

5.10-lucjan-ll72

- add BFQ-dev 20210203

DROP 5.10-lucjan-ll72-rc1

5.10-lucjan-ll72-rc1

- sync with upstream (drop iwlwifi-provide-gso_type-to-GSO-packets.patch)

5.10-lucjan-ll71

- add btrfs-remove-unnecessary-directory-inode-item-update.patch
- add btrfs-stop-setting-nbytes-when-filling-inode-item-fo.patch
- add btrfs-avoid-logging-new-ancestor-inodes-when-logging.patch
- add btrfs-skip-logging-directories-already-logged-when-l.patch
- add btrfs-skip-logging-inodes-already-logged-when-loggin.patch
- add btrfs-remove-unnecessary-check_parent_dirs_for_sync.patch
- add btrfs-make-concurrent-fsyncs-wait-less-when-waiting-.patch

DROP 5.10-lucjan-ll71-rc1

5.10-lucjan-ll71-rc1

- sync with upstream (drop iwlwifi-provide-gso_type-to-GSO-packets.patch)

5.10-lucjan-ll70

- drop iwlwifi-Fix-regression-from-UDP-segmentation-support.patch
- add iwlwifi-provide-gso_type-to-GSO-packets.patch

5.10-lucjan-ll69-rc1 --> 5.10-lucjan-ll69

5.10-lucjan-ll69-rc1

- sync with upstream (drop HID-wacom-Correct-NULL-dereference-on-AES-pen-proxim.patch)
- resync futex-resync-from-gitlab.collabora.com.patch
- resync futex2-resync-from-gitlab.collabora.com.patch

5.10-lucjan-ll68

- add ntfs3-5.10-update-to-v19.patch

5.10-lucjan-ll67

- add ZEN-Increase-max-elevator-name-size.patch

5.10-lucjan-ll66

- add ZEN-Fix-mq-deadline-scheduler-renaming.patch

5.10-lucjan-ll65

- add blk-mq-Improve-performance-of-non-mq-IO-schedulers-w.patch

5.10-lucjan-ll64

- add BFQ-dev 20210125

5.10-lucjan-ll63

- add ntfs3-5.10-update-to-v18.patch

5.10-lucjan-ll62

- add xfs-set-inode-size-after-creating-symlink.patch

5.10-lucjan-ll61

- add HID-wacom-Correct-NULL-dereference-on-AES-pen-proxim.patch

5.10-lucjan-ll59

- restore of a previous version BFQ-dev 20210122

5.10-lucjan-ll59

- update BFQ-dev 20210122

5.10-lucjan-ll58

- add BFQ-dev 20210122

5.10-lucjan-ll57-rc1 --> 5.10-lucjan-ll57

5.10-lucjan-ll57-rc1

- sync with upstream (drop btrfs-relocation-fix-wrong-file-extent-type-check-to.patch)
- sync with upstream (drop drm-i915-gt-Limit-VFE-threads-based-on-GT.patch)
- sync with upstream (drop drm-i915-Allow-the-sysadmin-to-override-security-mit.patch)
- sync with upstream (drop drm-i915-gt-Restore-clear-residual-mitigations-for-I.patch)

5.10-lucjan-ll56

- add HID-logitech-hidpp-add-support-for-Unified-Battery-1.patch
- add mm-compaction-correct-deferral-logic-for-proactive-c.patch

DROP 5.10-lucjan-ll56-rc1

5.10-lucjan-ll56-rc1

- sync with upstream (drop btrfs-relocation-fix-wrong-file-extent-type-check-to.patch)
- sync with upstream (drop drm-i915-gt-Limit-VFE-threads-based-on-GT.patch)
- sync with upstream (drop drm-i915-Allow-the-sysadmin-to-override-security-mit.patch)
- sync with upstream (drop drm-i915-gt-Restore-clear-residual-mitigations-for-I.patch)

5.10-lucjan-ll55

- update futex2-resync-from-gitlab.collabora.com.patch

DROP 5.10-lucjan-ll55-rc2

5.10-lucjan-ll55-rc2

- add BFQ-dev 20210118

5.10-lucjan-ll55-rc1

- sync with upstream (drop btrfs-relocation-fix-wrong-file-extent-type-check-to.patch)
- sync with upstream (drop drm-i915-gt-Limit-VFE-threads-based-on-GT.patch)
- sync with upstream (drop drm-i915-Allow-the-sysadmin-to-override-security-mit.patch)

5.10-lucjan-ll54

- add btrfs-handle-total_bytes_pinned-inside-the-delayed-r.patch
- add btrfs-account-for-new-extents-being-deleted-in-total.patch

DROP 5.10-lucjan-ll54-rc1

5.10-lucjan-ll54-rc1

- sync with upstream (drop btrfs-relocation-fix-wrong-file-extent-type-check-to.patch)
- sync with upstream (drop drm-i915-gt-Limit-VFE-threads-based-on-GT.patch)
- sync with upstream (drop drm-i915-Allow-the-sysadmin-to-override-security-mit.patch)

5.10-lucjan-ll53

- drop xfs-introduce-xfs_trans_context_swap-for-rolling-tra.patch
- add xfs-refactor-the-usage-around-xfs_trans_context_-set.patch

DROP 5.10-lucjan-ll53-rc1

5.10-lucjan-ll53-rc1

- sync with upstream (drop btrfs-relocation-fix-wrong-file-extent-type-check-to.patch)
- sync with upstream (drop drm-i915-gt-Limit-VFE-threads-based-on-GT.patch)
- sync with upstream (drop drm-i915-Allow-the-sysadmin-to-override-security-mit.patch)

5.10-lucjan-ll52-rc1 --> 5.10-lucjan-ll52

5.10-lucjan-ll52-rc1

- sync with upstream (drop btrfs-fix-deadlock-when-cloning-inline-extent-and-lo.patch)
- sync with upstream (drop btrfs-shrink-delalloc-pages-instead-of-full-inodes.patch)
- sync with upstream (drop btrfs-skip-unnecessary-searches-for-xattrs-when-logg.patch)

DROP 5.10-lucjan-ll51

- add net-tcp_bbr-v2-don-t-assume-prior_cwnd-was-set-enter.patch

DROP 5.10-lucjan-ll51-rc1

5.10-lucjan-ll51-rc1

- sync with upstream (drop btrfs-fix-deadlock-when-cloning-inline-extent-and-lo.patch)
- sync with upstream (drop btrfs-shrink-delalloc-pages-instead-of-full-inodes.patch)
- sync with upstream (drop btrfs-skip-unnecessary-searches-for-xattrs-when-logg.patch)

DROP 5.10-lucjan-ll50

- add bbr2-5.10-introduce-BBRv2.patch

DROP 5.10-lucjan-ll50-rc1

5.10-lucjan-ll50-rc1

- sync with upstream (drop btrfs-fix-deadlock-when-cloning-inline-extent-and-lo.patch)
- sync with upstream (drop btrfs-shrink-delalloc-pages-instead-of-full-inodes.patch)
- sync with upstream (drop btrfs-skip-unnecessary-searches-for-xattrs-when-logg.patch)

5.10-lucjan-ll49

- update drm-i915-gt-Limit-VFE-threads-based-on-GT.patch
- update drm-i915-gt-Restore-clear-residual-mitigations-for-I.patch
- update drm-i915-Allow-the-user-to-override-security-mitigat.patch

DROP 5.10-lucjan-ll49-rc1

5.10-lucjan-ll49-rc1

- sync with upstream (drop btrfs-fix-deadlock-when-cloning-inline-extent-and-lo.patch)
- sync with upstream (drop btrfs-shrink-delalloc-pages-instead-of-full-inodes.patch)
- sync with upstream (drop btrfs-skip-unnecessary-searches-for-xattrs-when-logg.patch)

5.10-lucjan-ll48

- add BFQ-dev 20210114

5.10-lucjan-ll47

- add AUFS 20210111

5.10-lucjan-ll46

- add BFQ-dev 20210113

5.10-lucjan-ll45

- update init-add-support-for-zstd-compressed-modules.patch

5.10-lucjan-ll44

- drop overlayfs-over-xfs-whiteout-operation-may-cause-dead.patch
- add xfs-fix-an-ABBA-deadlock-in-xfs_rename.patch

5.10-lucjan-ll43-rc1 --> 5.10-lucjan-ll43

5.10-lucjan-ll43-rc1

- sync with upstream (drop btrfs-send-fix-wrong-file-path-when-there-is-an-inod.patch)

5.10-lucjan-ll42

- add drm-i915-gt-Limit-VFE-threads-based-on-GT.patch
- add drm-i915-gt-Restore-clear-residual-mitigations-for-I.patch
- add drm-i915-Allow-the-user-to-override-security-mitigat.patch

5.10-lucjan-ll41

- drop Partially-revert-commit-38d715f494f2-btrfs-use-btrfs.patch
- add btrfs-fix-deadlock-when-cloning-inline-extent-and-lo.patch
- add btrfs-shrink-delalloc-pages-instead-of-full-inodes.patch

5.10-lucjan-ll40-rc1 --> 5.10-lucjan-ll40

5.10-lucjan-ll40-rc1

- sync with upstream (drop Revert-drm-amd-display-Fix-memory-leaks-in-S3-resume.patch)
- sync with upstream (drop Bluetooth-Fix-attempting-to-set-RPA-timeout-when-uns.patch)
- sync with upstream (drop ALSA-hda-hdmi-fix-locking-in-silent_stream_disable.patch)

5.10-lucjan-ll39-rc1 --> 5.10-lucjan-ll39

5.10-lucjan-ll39-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll38

- add Revert-drm-amd-display-Fix-memory-leaks-in-S3-resume.patch

DROP 5.10-lucjan-ll38-rc1

5.10-lucjan-ll38-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll37

- fix AUFS 20210104

DROP 5.10-lucjan-ll37-rc1

5.10-lucjan-ll37-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll36

- add v4l2loopback-5.10-confine-v4l2loopback_cleanup_modul.patch

DROP 5.10-lucjan-ll36-rc1

5.10-lucjan-ll36-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll35

- drop z3fold-remove-preempt-disabled-sections-for-RT.patch
- add genirq-i2c-export-generic_dispatch_irq.patch

DROP 5.10-lucjan-ll35-rc1

5.10-lucjan-ll35-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll34

- add AUFS 20210104

DROP 5.10-lucjan-ll34-rc1

5.10-lucjan-ll34-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll33

- add ALSA-hda-hdmi-fix-locking-in-silent_stream_disable.patch

DROP 5.10-lucjan-ll33-rc1

5.10-lucjan-ll33-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll32

- add ntfs3-5.10-update-to-v16.patch

DROP 5.10-lucjan-ll32-rc1

5.10-lucjan-ll32-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll31

- add Project-C v5.10-r2

DROP 5.10-lucjan-ll31-rc1

5.10-lucjan-ll31-rc1

- sync with upstream (drop drm-amd-display-Add-get_dig_frontend-implementation-.patch)

5.10-lucjan-ll30

- add zen-Allow-MSR-writes-by-default.patch

5.10-lucjan-ll29

- add btrfs-relocation-fix-wrong-file-extent-type-check-to.patch

5.10-lucjan-ll28-rc1 --> 5.10-lucjan-ll28

5.10-lucjan-ll28-rc1

- sync with upstream (drop drm-amdgpu-only-set-DP-subconnector-type-on-DP-and-e.patch)
- sync with upstream (drop Bluetooth-Fix-LL-PRivacy-BLE-device-fails-to-connect.patch)
- sync with upstream (drop z3fold-simplify-freeing-slots.patch)
- sync with upstream (drop z3fold-stricter-locking-and-more-careful-reclaim.patch)
- sync with upstream (update mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch)

5.10-lucjan-ll27

- add spadfs-5.10-merge-v1.0.12.patch

DROP 5.10-lucjan-ll27-rc1

5.10-lucjan-ll27-rc1

- sync with upstream (drop drm-amdgpu-only-set-DP-subconnector-type-on-DP-and-e.patch)
- sync with upstream (drop Bluetooth-Fix-LL-PRivacy-BLE-device-fails-to-connect.patch)
- sync with upstream (drop z3fold-simplify-freeing-slots.patch)
- sync with upstream (drop z3fold-stricter-locking-and-more-careful-reclaim.patch)
- sync with upstream (update mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch)

5.10-lucjan-ll26

- add BFQ-dev 20201228

DROP 5.10-lucjan-ll26-rc1

5.10-lucjan-ll26-rc1

- sync with upstream (drop drm-amdgpu-only-set-DP-subconnector-type-on-DP-and-e.patch)
- sync with upstream (drop Bluetooth-Fix-LL-PRivacy-BLE-device-fails-to-connect.patch)
- sync with upstream (drop z3fold-simplify-freeing-slots.patch)
- sync with upstream (drop z3fold-stricter-locking-and-more-careful-reclaim.patch)
- sync with upstream (update mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch)

5.10-lucjan-ll25

- add BFQ-dev 20201227

DROP 5.10-lucjan-ll25-rc1

5.10-lucjan-ll25-rc1

- sync with upstream (drop drm-amdgpu-only-set-DP-subconnector-type-on-DP-and-e.patch)
- sync with upstream (drop Bluetooth-Fix-LL-PRivacy-BLE-device-fails-to-connect.patch)
- sync with upstream (drop z3fold-simplify-freeing-slots.patch)
- sync with upstream (drop z3fold-stricter-locking-and-more-careful-reclaim.patch)
- sync with upstream (update mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch)

5.10-lucjan-ll24

- add drm-amd-display-Add-get_dig_frontend-implementation-.patch
- add drm-amdgpu-only-set-DP-subconnector-type-on-DP-and-e.patch
- add iwlwifi-Fix-regression-from-UDP-segmentation-support.patch

5.10-lucjan-ll23

- drop xfs-refactor-the-usage-around-xfs_trans_context_-set.patch
- add xfs-introduce-xfs_trans_context_swap-for-rolling-tra.patch

5.10-lucjan-ll22

- add mm-5.10-respect-soft-active-file-pages-eviction.patch

5.10-lucjan-ll21

- add btrfs-make-flush_space-take-a-enum-btrfs_flush_state.patch
- add btrfs-add-a-trace-point-for-reserve-tickets.patch
- add btrfs-track-ordered-bytes-instead-of-just-dio-ordere.patch
- add btrfs-introduce-a-FORCE_COMMIT_TRANS-flush-operation.patch
- add btrfs-improve-preemptive-background-space-flushing.patch
- add btrfs-rename-need_do_async_reclaim.patch
- add btrfs-check-reclaim_size-in-need_preemptive_reclaim.patch
- add btrfs-rework-btrfs_calc_reclaim_metadata_size.patch
- add btrfs-simplify-the-logic-in-need_preemptive_flushing.patch
- add btrfs-implement-space-clamping-for-preemptive-flushi.patch
- add btrfs-adjust-the-flush-trace-point-to-include-the-so.patch
- add btrfs-add-a-trace-class-for-dumping-the-current-ENOS.patch
- add Partially-revert-commit-38d715f494f2-btrfs-use-btrfs.patch

5.10-lucjan-ll20-rc1 --> 5.10-lucjan-ll20

5.10-lucjan-ll20-rc1

- sync with upstream (drop f2fs-fix-to-seek-incorrect-data-offset-in-inline-dat.patch)

5.10-lucjan-ll19

- add ntfs3-5.10-update-to-v16.patch

DROP 5.10-lucjan-ll19-rc1

5.10-lucjan-ll19-rc1

- sync with upstream (drop f2fs-fix-to-seek-incorrect-data-offset-in-inline-dat.patch)

5.10-lucjan-ll18

- add Project-C v5.10-r1
- add sched-alt-Fix-UP-compilation-warning.patch

DROP 5.10-lucjan-ll18-rc1

5.10-lucjan-ll18-rc1

- sync with upstream (drop f2fs-fix-to-seek-incorrect-data-offset-in-inline-dat.patch)

5.10-lucjan-ll17

- add mm-5.10-make-activefile-protection-more-soft-and-use.patch

5.10-lucjan-ll16-rc1 --> 5.10-lucjan-ll16

5.10-lucjan-ll16-rc1

- add f2fs-fix-to-seek-incorrect-data-offset-in-inline-dat.patch
- add overlayfs-over-xfs-whiteout-operation-may-cause-dead.patch

5.10-lucjan-ll15-rc1

- add btrfs-return-bool-from-should_end_transaction.patch
- add btrfs-return-bool-from-btrfs_should_end_transaction.patch
- add btrfs-do-not-block-on-deleted-bgs-mutex-in-the-clean.patch
- add btrfs-only-let-one-thread-pre-flush-delayed-refs-in-.patch
- add btrfs-delayed-refs-pre-flushing-should-only-run-the-.patch
- add btrfs-only-run-delayed-refs-once-before-committing.patch
- add btrfs-move-delayed-ref-flushing-for-qgroup-into-qgro.patch
- add btrfs-remove-bogus-BUG_ON-in-alloc_reserved_tree_blo.patch
- add btrfs-stop-running-all-delayed-refs-during-snapshot.patch
- add btrfs-run-delayed-refs-less-often-in-commit_cowonly_.patch

5.10-lucjan-ll14-rc1

- add cpu-5.10-add-support-for-Zen-3-with-trunk-GCC.patch

5.10-lucjan-ll13-rc1

- add mm-5.10-fix-unevictable-nits.patch

5.10-lucjan-ll12-rc1

- add mm-5.10-protect-file-mappings-under-memory-pressure.patch
- resync LL-Implement-ll-branding-v5.10.patch

5.10-lucjan-ll11-rc1

- drop mm-z3fold-fix-scheduling-while-atomic.patch
- drop mm-z3fold-Remove-preempt-disabled-sections-for-RT.patch
- add z3fold-simplify-freeing-slots.patch
- add z3fold-stricter-locking-and-more-careful-reclaim.patch
- add z3fold-remove-preempt-disabled-sections-for-RT.patch

5.10-lucjan-ll10-rc1

- restore init-add-support-for-zstd-compressed-modules.patch

5.10-lucjan-ll9-rc1

- update readfile-implement-readfile-syscall.patch
- update arch-wire-up-the-readfile-syscall.patch
- update selftests-add-readfile-2-selftests.patch
- update readfile.2-new-page-describing-readfile-2.patch
- add futex2-resync-from-gitlab.collabora.com.patch

5.10-lucjan-ll8-rc1

- drop futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- drop selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- drop selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- drop selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- drop futex-Change-WAIT_MULTIPLE-opcode-to-31.patch
- add futex-resync-from-gitlab.collabora.com.patch

5.10-lucjan-ll7-rc1

- update init-add-support-for-zstd-compressed-modules.patch

5.10-lucjan-ll6-rc1

- update init-add-support-for-zstd-compressed-modules.patch

5.10-lucjan-ll5-rc1

- add btrfs-fix-race-causing-unnecessary-inode-logging-dur.patch
- add btrfs-fix-race-that-results-in-logging-old-extents-d.patch
- add btrfs-fix-race-that-causes-unnecessary-logging-of-an.patch
- add btrfs-fix-race-that-makes-inode-logging-fallback-to-.patch
- add btrfs-fix-race-leading-to-unnecessary-transaction-co.patch
- add btrfs-do-not-block-inode-logging-for-so-long-during-.patch

5.10-lucjan-ll4-rc1

- drop xfs-avoid-transaction-reservation-recursion.patch (1)
- drop xfs-avoid-transaction-reservation-recursion.patch (2)
- add xfs-use-memalloc_nofs_-save-restore-in-xfs-transacti.patch
- add xfs-refactor-the-usage-around-xfs_trans_context_-set.patch
- add xfs-use-current-journal_info-to-avoid-transaction-re.patch

5.10-lucjan-ll3-rc1

- add BFQ-dev 20201215 (fix htmldocs warining)

5.10-lucjan-ll2-rc1

- add sched-bmq-Fix-compilation-issue.patch

5.10-lucjan-ll1-rc1

- add Export-symbols-needed-by-Android-drivers.patch
- add android-Enable-building-ashmem-and-binder-as-modules.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add Bluetooth-Fix-LL-PRivacy-BLE-device-fails-to-connect.patch
- add Bluetooth-Fix-attempting-to-set-RPA-timeout-when-uns.patch
- add HID-quirks-Add-Apple-Magic-Trackpad-2-to-hid_have_sp.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O.patch
- add block-Add-CONFIG-to-rename-the-mq-deadline-scheduler.patch
- add btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- add btrfs-restart-snapshot-delete-if-we-have-to-end-the-.patch
- add btrfs-do-not-evaluate-the-expression-with-CONFIG_BTR.patch
- add btrfs-remove-unnecessary-attempt-do-drop-extent-maps.patch
- add btrfs-stop-incrementing-log-batch-when-joining-log-t.patch
- add btrfs-send-fix-wrong-file-path-when-there-is-an-inod.patch
- add btrfs-skip-unnecessary-searches-for-xattrs-when-logg.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add Port-microcode-patches.patch
- add clearlinux-Add-pageflip-patches.patch
- add cpu-5.10-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add mm-Disable-watermark-boosting-by-default.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch
- add mm-Add-become_kswapd-and-restore_kswapd.patch
- add kbuild-Disable-stack-conservation-for-GCC.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add ZEN-Add-OpenRGB-patches.patch
- add tty-Allow-setting-the-number-of-available-virtual-TT.patch
- add scsi-sd-Optimal-I-O-size-should-be-a-multiple-of-rep.patch
- add vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch
- add fs-Break-generic_file_buffered_read-up-into-multiple.patch
- add fs-generic_file_buffered_read-now-uses-find_get_page.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- add futex-Change-WAIT_MULTIPLE-opcode-to-31.patch
- add iomap-avoid-deadlock-if-memory-reclaim-is-triggered-.patch
- add xfs-avoid-transaction-reservation-recursion.patch (1)
- add xfs-avoid-transaction-reservation-recursion.patch (2)
- add fs-ntfs3-Add-headers-and-misc-files.patch
- add fs-ntfs3-Add-initialization-of-super-block.patch
- add fs-ntfs3-Add-bitmap.patch
- add fs-ntfs3-Add-file-operations-and-implementation.patch
- add fs-ntfs3-Add-attrib-operations.patch
- add fs-ntfs3-Add-compression.patch
- add fs-ntfs3-Add-NTFS-journal.patch
- add fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- add fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- add fs-ntfs3-Add-MAINTAINERS.patch
- add mm-z3fold-fix-scheduling-while-atomic.patch
- add genirq-i2c-Provide-and-use-generic_dispatch_irq.patch
- add mm-z3fold-Remove-preempt-disabled-sections-for-RT.patch
- add x86-msr-index-sort-AMD-RAPL-MSRs-by-address.patch
- add powercap-intel_rapl_msr-Convert-rapl_msr_priv-into-p.patch
- add powercap-Add-AMD-Fam17h-RAPL-support.patch
- add powercap-RAPL-Add-AMD-Fam19h-RAPL-support.patch
- add readfile-implement-readfile-syscall.patch
- add arch-wire-up-the-readfile-syscall.patch
- add selftests-add-readfile-2-selftests.patch
- add readfile.2-new-page-describing-readfile-2.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add lib-zstd-Add-kernel-specific-API.patch
- add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- add init-add-support-for-zstd-compressed-modules.patch
- add sched-autogroup-Add-kernel-parameter-and-config-opti.patch
- add Project-C v5.10-r0
- add init-Kconfig-set-default-value-of-SCHED_PDS.patch
- add init-Kconfig-Restore-original-PDS-description.patch
- add sched-alt-Export-can_nice-symbol-for-Android-Binder-.patch
- add sched-pds-1.1-Implement-bitmap-allocator.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add Disable-CPU_FREQ_GOV_SCHEDUTIL.patch
- add BFQ-dev 20201214
- add UKSM for 5.10

5.9-lucjan-ll79

- restore init-add-support-for-zstd-compressed-modules.patch

5.9-lucjan-ll78

- update init-add-support-for-zstd-compressed-modules.patch

5.9-lucjan-ll77

- update init-add-support-for-zstd-compressed-modules.patch

5.9-lucjan-ll76

- drop xfs-avoid-transaction-reservation-recursion.patch (1)
- drop xfs-avoid-transaction-reservation-recursion.patch (2)
- add xfs-use-memalloc_nofs_-save-restore-in-xfs-transacti.patch
- add xfs-refactor-the-usage-around-xfs_trans_context_-set.patch
- add xfs-use-current-journal_info-to-avoid-transaction-re.patch

5.9-lucjan-ll75

- add drm-dp_mst-Support-remote-i2c-writes.patch

5.9-lucjan-ll74

- add Revert-md-change-mddev-chunk_sectors-from-int-to-uns.patch
- add Revert-dm-raid-fix-discard-limits-for-raid1-and-raid.patch

5.9-lucjan-ll73

- add block backport from 5.10 line

5.9-lucjan-ll72

- update fs-ntfs3-Add-headers-and-misc-files.patch
- update fs-ntfs3-Add-initialization-of-super-block.patch
- update fs-ntfs3-Add-bitmap.patch
- update fs-ntfs3-Add-file-operations-and-implementation.patch
- update fs-ntfs3-Add-attrib-operations.patch
- update fs-ntfs3-Add-compression.patch
- update fs-ntfs3-Add-NTFS-journal.patch
- update fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- update fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- update fs-ntfs3-Add-MAINTAINERS.patch

5.9-lucjan-ll71

- add btrfs-send-fix-wrong-file-path-when-there-is-an-inod.patch

5.9-lucjan-ll70-rc1 --> 5.9-lucjan-ll70

5.9-lucjan-ll70-rc1

- resync dm backport against 5.9.14

5.9-lucjan-ll69

- add BFQ-dev 20201210

DROP 5.9-lucjan-ll69-rc2

5.9-lucjan-ll69-rc2

- resync dm backport against 5.9.14

5.9-lucjan-ll69-rc1

- resync dm backport against 5.9.14

5.9-lucjan-ll68

- add Project-C v5.9-r3

5.9-lucjan-ll67

- add dm backport from 5.10 line

5.9-lucjan-ll66

- add block backport from 5.10 line

5.9-lucjan-ll65

- update fs-ntfs3-Add-headers-and-misc-files.patch
- update fs-ntfs3-Add-initialization-of-super-block.patch
- update fs-ntfs3-Add-bitmap.patch
- update fs-ntfs3-Add-file-operations-and-implementation.patch
- update fs-ntfs3-Add-attrib-operations.patch
- update fs-ntfs3-Add-compression.patch
- update fs-ntfs3-Add-NTFS-journal.patch
- update fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- update fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- update fs-ntfs3-Add-MAINTAINERS.patch

5.9-lucjan-ll64

- update lib-zstd-Add-kernel-specific-API.patch
- update lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- update lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch

5.9-lucjan-ll63

- drop lib-zstd-Add-zstd-compatibility-wrapper.patch
- drop lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- drop lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- drop crypto-zstd-Switch-to-zstd-1.4.6-API.patch
- drop btrfs-zstd-Switch-to-the-zstd-1.4.6-API.patch
- drop f2fs-zstd-Switch-to-the-zstd-1.4.6-API.patch
- drop squashfs-zstd-Switch-to-the-zstd-1.4.6-API.patch
- drop lib-unzstd-Switch-to-the-zstd-1.4.6-API.patch
- drop lib-zstd-Remove-zstd-compatibility-wrapper.patch
- add lib-zstd-Add-kernel-specific-API.patch
- re-add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- re-add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch

5.9-lucjan-ll62

- add HID-quirks-Add-Apple-Magic-Trackpad-2-to-hid_have_sp.patch

5.9-lucjan-ll61-rc1 --> 5.9-lucjan-ll61

5.9-lucjan-ll61-rc1

- resync block backport against 5.9.12
- sync with upstream (drop efivarfs-revert-fix-memory-leak-in-efivarfs_create.patch)

5.9-lucjan-ll60

- add Revert-net-tso-add-UDP-segmentation-support.patch

5.9-lucjan-ll59

- update efivarfs-revert-fix-memory-leak-in-efivarfs_create.patch
- drop fs-efivarfs-attempt-to-get-the-last-fix-to-build.patch
- add Bluetooth-Fix-attempting-to-set-RPA-timeout-when-uns.patch

5.9-lucjan-ll58

- add block backport from 5.10 line

5.9-lucjan-ll57

- drop block-bfq-Disable-low_latency-when-blk_iolatency-is-.patch

5.9-lucjan-ll56

- add efivarfs-revert-fix-memory-leak-in-efivarfs_create.patch
- add fs-efivarfs-attempt-to-get-the-last-fix-to-build.patch

5.9-lucjan-ll55

- drop mm-madvise-introduce-process_madvise-syscall-an-exte.patch
- drop readfile-implement-readfile-syscall.patch
- drop arch-wire-up-the-readfile-syscall.patch
- drop selftests-add-readfile-2-selftests.patch
- drop readfile.2-new-page-describing-readfile-2.patch

5.9-lucjan-ll54

- add mm-madvise-introduce-process_madvise-syscall-an-exte.patch
- add readfile-implement-readfile-syscall.patch
- add arch-wire-up-the-readfile-syscall.patch
- add selftests-add-readfile-2-selftests.patch
- add readfile.2-new-page-describing-readfile-2.patch

5.9-lucjan-ll53

- add v4l2loopback-5.9-initial-merge.patch

5.9-lucjan-ll52

- add fs-Break-generic_file_buffered_read-up-into-multiple.patch
- add fs-generic_file_buffered_read-now-uses-find_get_page.patch

5.9-lucjan-ll51-rc1 --> 5.9-lucjan-ll51

5.9-lucjan-ll51-rc1

- resync block backport against 5.9.11
- drop fs-Break-generic_file_buffered_read-up-into-multiple.patch
- drop fs-generic_file_buffered_read-now-uses-find_get_page.patch

5.9-lucjan-ll50

- update fs-ntfs3-Add-headers-and-misc-files.patch
- update fs-ntfs3-Add-initialization-of-super-block.patch
- update fs-ntfs3-Add-bitmap.patch
- update fs-ntfs3-Add-file-operations-and-implementation.patch
- update fs-ntfs3-Add-attrib-operations.patch
- update fs-ntfs3-Add-compression.patch
- update fs-ntfs3-Add-NTFS-journal.patch
- update fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- update fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- update fs-ntfs3-Add-MAINTAINERS.patch

5.9-lucjan-ll49

- add block backport from 5.10 line

5.9-lucjan-ll48

- add Project-C v5.9-r2

5.9-lucjan-ll47

- drop btrfs-skip-unnecessary-searches-for-xattrs-when-logg.patch

5.9-lucjan-ll46

- add btrfs-remove-unnecessary-attempt-do-drop-extent-maps.patch
- add btrfs-skip-unnecessary-searches-for-xattrs-when-logg.patch
- add btrfs-stop-incrementing-log-batch-when-joining-log-t.patch

5.9-lucjan-ll45-rc1 --> 5.9-lucjan-ll45

5.9-lucjan-ll45-rc1

- resync block backport against 5.9.9
- sync with upstream (drop btrfs-fix-min-reserved-size-calculation-in-merge_rel.patch)

5.9-lucjan-ll44

- add powercap-intel_rapl-Fix-domain-detection.patch
- add powercap-intel_rapl-enumerate-Psys-RAPL-domain-toget.patch
- add x86-msr-index-sort-AMD-RAPL-MSRs-by-address.patch
- add powercap-intel_rapl_msr-Convert-rapl_msr_priv-into-p.patch
- add powercap-Add-AMD-Fam17h-RAPL-support.patch
- add powercap-RAPL-Add-AMD-Fam19h-RAPL-support.patch

DROP 5.9-lucjan-ll44-rc1

5.9-lucjan-ll44-rc1

- resync block backport against 5.9.9
- sync with upstream (drop btrfs-fix-min-reserved-size-calculation-in-merge_rel.patch)

5.9-lucjan-ll43

- drop futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- drop futex-Add-Proton-compatibility-code.patch
- re-add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- add futex-Change-WAIT_MULTIPLE-opcode-to-31.patch

DROP 5.9-lucjan-ll43-rc1

5.9-lucjan-ll43-rc1

- resync block backport against 5.9.9
- sync with upstream (drop btrfs-fix-min-reserved-size-calculation-in-merge_rel.patch)

5.9-lucjan-ll42

- drop raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch

5.9-lucjan-ll41

- add block backport from 5.10 line

5.9-lucjan-ll40

- update xfs-avoid-transaction-reservation-recursion.patch

5.9-lucjan-ll39

- add fs-ntfs3-Add-headers-and-misc-files.patch
- add fs-ntfs3-Add-initialization-of-super-block.patch
- add fs-ntfs3-Add-bitmap.patch
- add fs-ntfs3-Add-file-operations-and-implementation.patch
- add fs-ntfs3-Add-attrib-operations.patch
- add fs-ntfs3-Add-compression.patch
- add fs-ntfs3-Add-NTFS-journal.patch
- add fs-ntfs3-Add-Kconfig-Makefile-and-doc.patch
- add fs-ntfs3-Add-NTFS3-in-fs-Kconfig-and-fs-Makefile.patch
- add fs-ntfs3-Add-MAINTAINERS.patch

5.9-lucjan-ll38

- add Bluetooth-Fix-LL-PRivacy-BLE-device-fails-to-connect.patch

5.9-lucjan-ll37-rc1 --> 5.9-lucjan-ll37

5.9-lucjan-ll37-rc1

- resync block backport against 5.9.7
- sync with upstream (drop mac80211-fix-regression-where-EAPOL-frames-were-sent.patch)

5.9-lucjan-ll36

- add block backport from 5.10 line

5.9-lucjan-ll35

- sync with upstream (drop Fix-ASoC-SOF-fix-a-runtime-pm-issue-in-SOF-when-HDMI.patch)

5.9-lucjan-ll34

- add Fix-ASoC-SOF-fix-a-runtime-pm-issue-in-SOF-when-HDMI.patch

5.9-lucjan-ll33-rc2

- resync block backport against 5.9.4

5.9-lucjan-ll33-rc1

- resync block backport against 5.9.4
- sync with upstream (drop vt-keyboard-reorder-user-buffer-handling-in-vt_do_kd.patch )
- sync with upstream (drop vt-keyboard-simplify-vt_kdgkbsent.patch)
- sync with upstream (drop vt-keyboard-extend-func_buf_lock-to-readers.patch)
- sync with upstream (drop selftests-x86-fsgsbase-Reap-a-forgotten-child.patch)
- sync with upstream (drop selftests-x86-fsgsbase-Test-PTRACE_PEEKUSER-for-GSBA.patch)
- sync with upstream (drop btrfs-trace-output-proper-root-owner-for-trace_find_.patch)
- sync with upstream (drop btrfs-reschedule-if-necessary-when-logging-directory.patch)
- sync with upstream (drop btrfs-tree-checker-fix-false-alert-caused-by-legacy-.patch)
- sync with upstream (drop btrfs-reschedule-when-cloning-lots-of-extents.patch)
- sync with upstream (drop btrfs-cleanup-cow-block-on-error.patch)
- update f2fs-zstd-Switch-to-the-zstd-1.4.6-API.patch

5.9-lucjan-ll32

- update fs-Break-generic_file_buffered_read-up-into-multiple.patch
- update fs-generic_file_buffered_read-now-uses-find_get_page.patch

5.9-lucjan-ll31-rc1 --> 5.9-lucjan-ll31

5.9-lucjan-ll31-rc1

- resync fs-Break-generic_file_buffered_read-up-into-multiple.patch
- resync fs-generic_file_buffered_read-now-uses-find_get_page.patch
- resync UKSM for 5.9

5.9-lucjan-ll30-rc1 --> 5.9-lucjan-ll30

5.9-lucjan-ll30-rc1

- add block backport from 5.10 line

5.9-lucjan-ll29

- update LL-Brading v5.9

5.9-lucjan-ll28

- add mac80211-fix-regression-where-EAPOL-frames-were-sent.patch

5.9-lucjan-ll27

- add btrfs-fix-min-reserved-size-calculation-in-merge_rel.patch

5.9-lucjan-ll26-rc1 --> 5.9-lucjan-ll26

5.9-lucjan-ll26-rc1

- resync block backport against 5.9.2
- sync with upstream (drop i2c-core-Restore-acpi_walk_dep_device_list-getting-c.patch)
- sync with upstream (drop iomap-Mark-read-blocks-uptodate-in-write_begin.patch)
- sync with upstream (drop iomap-Clear-page-error-before-beginning-a-write.patch)

5.9-lucjan-ll25-rc1 --> 5.9-lucjan-ll25

5.9-lucjan-ll25-rc1

- add block backport from 5.10 line

5.9-lucjan-ll24-rc1 --> 5.9-lucjan-ll24

5.9-lucjan-ll24-rc1

- add BFQ-dev 20201022
- add block backport from 5.10 line
- resync block-set-rq_affinity-2-for-full-multithreading-I-O-.patch

5.9-lucjan-ll23

- add fs-Break-generic_file_buffered_read-up-into-multiple.patch
- add fs-generic_file_buffered_read-now-uses-find_get_page.patch

5.9-lucjan-ll22

- add Project-C v5.9-r1
- add sched-alt-Fix-compilation-when-NR_CPUS-64.patch

5.9-lucjan-ll21

- drop  Project-C v5.9-r1 (https://gitlab.com/alfredchen/linux-prjc/-/issues/17)

5.9-lucjan-ll20

- add Project-C v5.9-r1

5.9-lucjan-ll19-rc1 --> 5.9-lucjan-ll19

5.9-lucjan-ll19-rc1

- drop Restore-futex_key.patch
- drop Import-Fsync-v3-patchset-Squashed-from-https-gitlab..patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add futex-Add-Proton-compatibility-code.patch

5.9-lucjan-ll18-rc1

- update sched-autogroup-Add-kernel-parameter-and-config-opti.patch

5.9-lucjan-ll17-rc1

- add i2c-core-Restore-acpi_walk_dep_device_list-getting-c.patch

5.9-lucjan-ll16-rc1

- add vt-keyboard-reorder-user-buffer-handling-in-vt_do_kd.patch
- add vt-keyboard-simplify-vt_kdgkbsent.patch
- add vt-keyboard-extend-func_buf_lock-to-readers.patch

5.9-lucjan-ll15-rc1

- update UKSM for 5.9

5.9-lucjan-ll14-rc1

- add xfs-avoid-transaction-reservation-recursion.patch

5.9-lucjan-ll13-rc1

- add mm-Add-become_kswapd-and-restore_kswapd.patch

5.9-lucjan-ll12-rc1

- drop fs-use-READ_ONCE-WRITE_ONCE-with-the-i_size-helpers.patch
- add btrfs-add-a-force_chunk_alloc-to-space_info-s-sysfs.patch
- add btrfs-restart-snapshot-delete-if-we-have-to-end-the-.patch

5.9-lucjan-ll11-rc1

- add x86-entry-64-Correct-the-comment-over-SAVE_AND_SET_G.patch
- add x86-fsgsbase-Replace-static_cpu_has-with-boot_cpu_ha.patch
- add selftests-x86-fsgsbase-Reap-a-forgotten-child.patch
- add selftests-x86-fsgsbase-Test-PTRACE_PEEKUSER-for-GSBA.patch

5.9-lucjan-ll10-rc1

- update lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch

5.9-lucjan-ll9-rc1

- add lib-zstd-Add-zstd-compatibility-wrapper.patch
- add lib-zstd-Add-decompress_sources.h-for-decompress_unz.patch
- add lib-zstd-Upgrade-to-latest-upstream-zstd-version-1.4.patch
- add crypto-zstd-Switch-to-zstd-1.4.6-API.patch
- add btrfs-zstd-Switch-to-the-zstd-1.4.6-API.patch
- add f2fs-zstd-Switch-to-the-zstd-1.4.6-API.patch
- add squashfs-zstd-Switch-to-the-zstd-1.4.6-API.patch
- add lib-unzstd-Switch-to-the-zstd-1.4.6-API.patch
- add lib-zstd-Remove-zstd-compatibility-wrapper.patch

5.9-lucjan-ll8-rc1

- add Restore-futex_key.patch
- add Import-Fsync-v3-patchset-Squashed-from-https-gitlab..patch

5.9-lucjan-ll7-rc1

- update UKSM for 5.9

5.9-lucjan-ll6-rc1

- fix BFQ-dev 20201012

5.9-lucjan-ll5-rc1

- drop futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- drop selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- drop selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- drop selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch

5.9-lucjan-ll4-rc1

- fix UKSM for 5.9

5.9-lucjan-ll3-rc1

- fix ZEN-Add-VHBA-driver.patch
- fix tty-Allow-setting-the-number-of-available-virtual-TT.patch

5.9-lucjan-ll2-rc1

- add sched-alt-Fix-compilation-erro-in-pelt.c.patch

5.9-lucjan-ll1-rc1

- add Export-symbols-needed-by-Android-drivers.patch
- add android-Enable-building-ashmem-and-binder-as-modules.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O-.patch
- add block-Add-CONFIG-to-rename-the-mq-deadline-scheduler.patch
- add block-bfq-Disable-low_latency-when-blk_iolatency-is-.patch
- add block-Fix-use-after-free-issue-while-accessing-iosch.patch
- add btrfs-do-not-evaluate-the-expression-with-CONFIG_BTR.patch
- add btrfs-trace-output-proper-root-owner-for-trace_find_.patch
- add btrfs-Remove-spurious-BUG_ON-in-btrfs_get_extent.patch
- add btrfs-do-not-commit-logs-and-transactions-during-lin.patch
- add btrfs-do-not-take-the-log_mutex-of-the-subvolume-whe.patch
- add btrfs-reschedule-if-necessary-when-logging-directory.patch
- add btrfs-tree-checker-fix-false-alert-caused-by-legacy-.patch
- add btrfs-reschedule-when-cloning-lots-of-extents.patch
- add btrfs-cleanup-cow-block-on-error.patch
- add fs-use-READ_ONCE-WRITE_ONCE-with-the-i_size-helpers.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add Port-microcode-patches.patch
- add clearlinux-Add-pageflip-patches.patch
- add cpu-5.9-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add Documentation-Fix-sphinx-3.0-causes-compilation-erro.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add mm-Disable-watermark-boosting-by-default.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch
- add kbuild-Disable-stack-conservation-for-GCC.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add ZEN-Add-OpenRGB-patches.patch
- add vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch
- add tty-Allow-setting-the-number-of-available-virtual-TT.patch
- add scsi-sd-Optimal-I-O-size-should-be-a-multiple-of-rep.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- add iomap-avoid-deadlock-if-memory-reclaim-is-triggered-.patch
- add iomap-Clear-page-error-before-beginning-a-write.patch
- add iomap-Mark-read-blocks-uptodate-in-write_begin.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add init-add-support-for-zstd-compressed-modules.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add Disable-CPU_FREQ_GOV_SCHEDUTIL.patch
- add BFQ-dev 20201012
- add Project-C v5.9-r0
- add sched-alt-Export-can_nice-symbol-for-Android-Binder-.patch
- add init-Kconfig-set-default-value-of-SCHED_PDS.patch
- add init-Kconfig-Restore-original-PDS-description.patch
- add sched-pds-1.1-Implement-bitmap-allocator.patch
- add UKSM for 5.9 
- add LL-Brading v5.9
- add LL-Add-.ll-version.patch

5.8-lucjan-ll39

- add fs-direct-io-fix-one-time-init-of-s_dio_done_wq.patch

5.8-lucjan-ll38

- resync vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch

5.8-lucjan-ll37

- add iomap-avoid-deadlock-if-memory-reclaim-is-triggered-.patch
- add iomap-Clear-page-error-before-beginning-a-write.patch
- add iomap-Mark-read-blocks-uptodate-in-write_begin.patch

5.8-lucjan-ll36

- add btrfs-kill-update_block_group_flags.patch
- add we-re-restriping-use-the-target.patch
- add btrfs-restart-snapshot-delete-if-we-have-to-end-the-.patch
- add btrfs-Don-t-balance-btree-inode-pages-from-buffered-.patch
- add btrfs-add-little-endian-optimized-key-helpers.patch
- add btrfs-relocation-allow-signal-to-cancel-balance.patch
- add btrfs-Add-comments-for-btrfs_reserve_flush_enum.patch
- add btrfs-prefetch-chunk-tree-leaves-at-mount.patch
- add btrfs-document-special-case-error-codes-for-fs-error.patch
- add btrfs-release-old-extent-maps-during-page-release.patch
- add btrfs-do-not-set-the-full-sync-flag-on-the-inode-dur.patch
- add btrfs-do-not-evaluate-the-expression-with-CONFIG_BTR.patch
- add btrfs-handle-errors-from-async-submission.patch
- add btrfs-trace-output-proper-root-owner-for-trace_find_.patch
- add btrfs-Remove-spurious-BUG_ON-in-btrfs_get_extent.patch
- add btrfs-do-not-commit-logs-and-transactions-during-lin.patch
- add btrfs-do-not-take-the-log_mutex-of-the-subvolume-whe.patch
- add btrfs-reschedule-if-necessary-when-logging-directory.patch
- add btrfs-tree-checker-fix-false-alert-caused-by-legacy-.patch
- add btrfs-reschedule-when-cloning-lots-of-extents.patch
- add btrfs-cleanup-cow-block-on-error.patch
- add fs-use-READ_ONCE-WRITE_ONCE-with-the-i_size-helpers.patch

5.8-lucjan-ll35

- add mm-rewrite-wait_on_page_bit_common-logic.patch
- add mm-add-list_del_init_careful-to-go-with-list_empty_c.patch
- add list-add-list_del_init_careful-to-go-with-list_empty.patch
- add mm-filemap.c-fix-a-data-race-in-filemap_fault.patch
- add mm-allow-a-controlled-amount-of-unfairness-in-the-pa.patch

5.8-lucjan-ll34

- add scsi-sd-Optimal-I-O-size-should-be-a-multiple-of-rep.patch

5.8-lucjan-ll33

- add block-Fix-use-after-free-issue-while-accessing-iosch.patch

5.8-lucjan-ll32

- add BFQ-dev 20200929

5.8-lucjan-ll31

- add sched-alt-Export-can_nice-symbol-for-Android-Binder-.patch

5.8-lucjan-ll30

- add Export-symbols-needed-by-Android-drivers.patch
- add android-Enable-building-ashmem-and-binder-as-modules.patch

5.8-lucjan-ll29

- update UKSM for 5.8

5.8-lucjan-ll28

- add tty-Allow-setting-the-number-of-available-virtual-TT.patch

5.8-lucjan-ll27

- add Documentation-Fix-sphinx-3.0-causes-compilation-erro.patch

5.8-lucjan-ll26-rc1 --> 5.8-lucjan-ll26

5.8-lucjan-ll26-rc1

- sync with upstream (resync x86-Add-support-for-ZSTD-compressed-kernel.patch)

5.8-lucjan-ll25

- add BFQ-dev 20200922

DROP 5.8-lucjan-ll25-rc1

5.8-lucjan-ll25-rc1

- sync with upstream (resync x86-Add-support-for-ZSTD-compressed-kernel.patch)

5.8-lucjan-ll24

- add init-Kconfig-Restore-original-PDS-description.patch

5.8-lucjan-ll23-rc1 --> 5.8-lucjan-ll23

5.8-lucjan-ll23-rc1

- sync with upstream (drop block-restore-a-specific-error-code-in-bdev_del_part.patch)

5.8-lucjan-ll22

- add init-Kconfig-set-default-value-of-SCHED_PDS.patch

DROP 5.8-lucjan-ll22-rc1

5.8-lucjan-ll22-rc1

- sync with upstream (drop block-restore-a-specific-error-code-in-bdev_del_part.patch)

5.8-lucjan-ll21

- add Project-C v5.8-r3

5.8-lucjan-ll20

- add block-restore-a-specific-error-code-in-bdev_del_part.patch

5.8-lucjan-ll19

- add sched-pds-1.1-Implement-bitmap-allocator.patch

5.8-lucjan-ll18

- add sched-alt-Call-check_preempt_curr-in-ttwu_do_wakeup.patch

5.8-lucjan-ll17

- add BFQ-dev 20200909

5.8-lucjan-ll16

- add sched-pds-Update-ALT_SCHED_VERSION_MSG.patch

5.8-lucjan-ll15

- add prjc-Fix-PDS-selection-doesn-t-disable-unsupported-f.patch

5.8-lucjan-ll14

- add sched-pds-Fix-compilation-issue-with-CONFIG_SCHED_TR.patch

5.8-lucjan-ll13

- add sched-pds-Port-of-PDS.patch
- add sched-alt-Refill-time_slice-in-time_slice_expired.patch
- add sched-alt-PDS-rework.patch
- add sched-alt-Documentation-and-comments-updates.patch
- add sched-alt-Revert-NORMAL_PRIO-defination-for-powerpc-.patch
- add sched-alt-Add-ALT_SCHED_VERSION-micro.patch
- resync LL-Brading v5.8

5.8-lucjan-l12

- add clearlinux-Add-pageflip-patches.patch

5.8-lucjan-ll11-rc1 --> 5.8-lucjan-ll11

5.8-lucjan-ll11-rc1

- sync with upstream (drop usb-renesas-xhci-remove-version-check.patch)
- sync with upstream (resync vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch)

5.8-lucjan-ll10-rc1

- add sched-alt-Fix-compilation-issue-when-CONFIG_SCHED_TH.patch

5.8-lucjan-ll9-rc1

- add block-bfq-Disable-low_latency-when-blk_iolatency-is-.patch
- add vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch

5.8-lucjan-ll8-rc1

- add usb-renesas-xhci-remove-version-check.patch

5.8-lucjan-ll7-rc1

- add BFQ-dev 20200819

5.8-lucjan-ll6-rc1

- sync with upstream (drop x86-fsgsbase-64-Fix-NULL-deref-in-86_fsgsbase_read_t.patch)

5.8-lucjan-ll5-rc1

- add block-Convert-to-use-the-preferred-fallthrough-macro.patch

5.8-lucjan-ll4-rc1

- add x86-fsgsbase-64-Fix-NULL-deref-in-86_fsgsbase_read_t.patch

5.8-lucjan-ll3-rc1

- add Project-C v5.8-r1

5.8-lucjan-ll2-rc1

- add sched-alt-Fix-UP-compilation-issue.patch

5.8-lucjan-ll1-rc1

- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add virt-vbox-Add-support-for-the-new-VBG_IOCTL_ACQUIRE_.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add x86-microcode-Force-update-a-uCode-even-if-the-rev-i.patch
- add x86-microcode-echo-2-reload-to-force-load-ucode.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O-.patch
- add block-Add-CONFIG-to-rename-the-mq-deadline-scheduler.patch
- add block-bfq-iosched-fix-duplicated-word.patch
- add block-bio-delete-duplicated-words.patch
- add block-elevator-delete-duplicated-word-and-fix-typos.patch
- add block-blk-mq-delete-duplicated-word.patch
- add block-blk-mq-sched-delete-duplicated-word.patch
- add block-blk-timeout-delete-duplicated-word.patch
- add cpu-5.8-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add capabilities-Introduce-CAP_CHECKPOINT_RESTORE.patch
- add pid-use-checkpoint_restore_ns_capable-for-set_tid.patch
- add pid_namespace-use-checkpoint_restore_ns_capable-for-.patch
- add proc-allow-access-in-init-userns-for-map_files-with-.patch
- add prctl-Allow-local-CAP_CHECKPOINT_RESTORE-to-change-p.patch
- add prctl-exe-link-permission-error-changed-from-EINVAL-.patch
- add selftests-add-clone3-CAP_CHECKPOINT_RESTORE-test.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add mm-Disable-watermark-boosting-by-default.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch
- add kbuild-Disable-stack-conservation-for-GCC.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add mm-Proactive-compaction.patch
- add mm-Use-unsigned-types-for-fragmentation-score.patch
- add mm-Fix-compile-error-due-to-COMPACTION_HPAGE_ORDER.patch
- add net-sched-Allow-changing-default-qdisc-to-FQ-PIE.patch
- add ALSA-hda-hdmi-Add-Intel-silent-stream-support.patch
- add ZEN-Add-OpenRGB-patches.patch
- add vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch
- add x86-ptrace-Prevent-ptrace-from-clearing-the-FS-GS-se.patch
- add x86-cpu-Add-unsafe_fsgsbase-to-enable-CR4.FSGSBASE.patch
- add x86-fsgsbase-64-Add-intrinsics-for-FSGSBASE-instruct.patch
- add x86-fsgsbase-64-Enable-FSGSBASE-instructions-in-help.patch
- add x86-process-64-Make-save_fsgs_for_kvm-ready-for-FSGS.patch
- add x86-process-64-Use-FSBSBASE-in-switch_to-if-availabl.patch
- add x86-process-64-Use-FSGSBASE-instructions-on-thread-c.patch
- add x86-speculation-swapgs-Check-FSGSBASE-in-enabling-SW.patch
- add x86-entry-64-Switch-CR3-before-SWAPGS-in-paranoid-en.patch
- add x86-entry-64-Introduce-the-FIND_PERCPU_BASE-macro.patch
- add x86-entry-64-Handle-FSGSBASE-enabled-paranoid-entry-.patch
- add x86-cpu-Enable-FSGSBASE-on-64bit-by-default-and-add-.patch
- add x86-elf-Enumerate-kernel-FSGSBASE-capability-in-AT_H.patch
- add Documentation-x86-64-Add-documentation-for-GS-FS-add.patch
- add selftests-x86-fsgsbase-Test-GS-selector-on-ptracer-i.patch
- add selftests-x86-fsgsbase-Test-ptracer-induced-GS-base-.patch
- add selftests-x86-fsgsbase-Fix-a-comment-in-the-ptrace_w.patch
- add selftests-x86-fsgsbase-Add-a-missing-memory-constrai.patch
- add x86-ptrace-Fix-32-bit-PTRACE_SETREGS-vs-fsbase-and-g.patch
- add selftests-x86-Add-a-syscall_arg_fault_64-test-for-ne.patch
- add fsgsbase-5.8-remove-erroneous-if-expression-bit.patch
- add x86-fsgsbase-Fix-Xen-PV-support.patch
- add fsgsbase-5.8-minor-resync-with-upstream-PR.patch
- add lib-prepare-zstd-for-preboot-environment.patch
- add lib-add-zstd-support-to-decompress.patch
- add init-add-support-for-zstd-compressed-kernel.patch
- add usr-add-support-for-zstd-compressed-initramfs.patch
- add x86-bump-ZO_z_extra_bytes-margin-for-zstd.patch
- add x86-Add-support-for-ZSTD-compressed-kernel.patch
- add .gitignore-add-ZSTD-compressed-files.patch
- add Documentation-dontdiff-Add-zstd-compressed-files.patch
- add init-add-support-for-zstd-compressed-modules.patch
- add x86-boot-compressed-Use-builtin-mem-functions-for-de.patch
- add sched-autogroup-Add-kernel-parameter-and-config-opti.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add mm-Disable-watermark-boosting-by-default.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch
- add kbuild-Disable-stack-conservation-for-GCC.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add mm-Proactive-compaction.patch
- add mm-Use-unsigned-types-for-fragmentation-score.patch
- add mm-Fix-compile-error-due-to-COMPACTION_HPAGE_ORDER.patch
- add net-sched-Allow-changing-default-qdisc-to-FQ-PIE.patch
- add ALSA-hda-hdmi-Add-Intel-silent-stream-support.patch
- add ZEN-Add-OpenRGB-patches.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add Disable-CPU_FREQ_GOV_SCHEDUTIL.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add BFQ-dev 20200803
- add Project-C v5.8-r0
- add UKSM for 5.8 
- add LL-Brading v5.8
- add LL-Add-.ll-version.patch

5.7-lucjan-ll62

- add sched-autogroup-Add-kernel-parameter-and-config-opti.patch

5.7-lucjan-ll61

- drop fsgsbase-5.7-minor-resync-with-upstream-PR.patch

5.7-lucjan-ll60

- add fsgsbase-5.7-minor-resync-with-upstream-PR.patch
- add x86-boot-compressed-Use-builtin-mem-functions-for-de.patch

5.7-lucjan-ll59-rc1 --> 5.7-lucjan-ll59

5.7-lucjan-ll59-rc1

- sync with upstream (drop drm-amd-display-Clear-dm_state-for-fast-updates.patch)

5.7-lucjan-ll58

- add openrgb-Deduplicate-piix4-setup-for-HUDSON2-KERNCZ-S.patch

DROP 5.7-lucjan-ll58-rc1

5.7-lucjan-ll58-rc1

- sync with upstream (drop drm-amd-display-Clear-dm_state-for-fast-updates.patch)

5.7-lucjan-ll57

- update zstd-patches

5.7-lucjan-ll56

- add block-bfq-iosched-fix-duplicated-word.patch
- add block-bio-delete-duplicated-words.patch
- add block-elevator-delete-duplicated-word-and-fix-typos.patch
- add block-blk-timeout-delete-duplicated-word.patch

5.7-lucjan-ll55

- update zstd-patches

5.7-lucjan-ll54

- add drm-amd-display-Clear-dm_state-for-fast-updates.patch

5.7-lucjan-ll53

- add BFQ-dev 20200729
- add Project-C v5.7-r3
- update zstd-patches
- sync with upstream (drop iwlwifi-Make-some-Killer-Wireless-AC-1550-cards-work.patch)

5.7-lucjan-ll52

- add BFQ-dev 20200723

5.7-lucjan-ll51

- add ALSA-hda-hdmi-Add-Intel-silent-stream-support.patch

5.7-lucjan-ll50-rc1 --> 5.7-lucjan-ll50

5.7-lucjan-ll50-rc1

- update virt-vbox-Add-support-for-the-new-VBG_IOCTL_ACQUIRE_.patch

DROP 5.7-lucjan-ll49-rc1

5.7-lucjan-ll49

- add BFQ-dev 20200720

5.7-lucjan-ll49-rc1

- update virt-vbox-Add-support-for-the-new-VBG_IOCTL_ACQUIRE_.patch

5.7-lucjan-ll48

- add virt-vbox-Add-support-for-the-new-VBG_IOCTL_ACQUIRE_.patch

5.7-lucjan-ll47-rc1 --> 5.7-lucjan-ll47

5.7-lucjan-ll47-rc1

- sync with upstream (drop sched-core-Check-cpus_mask-not-cpus_ptr-in-__set_cpu.patch,
                      drop Revert-ath9k-Fix-general-protection-fault-in-ath9k_h.patch)

5.7-lucjan-ll46

- add net-sched-Allow-changing-default-qdisc-to-FQ-PIE.patch

DROP 5.7-lucjan-ll46-rc1

5.7-lucjan-ll46-rc1

- sync with upstream (drop sched-core-Check-cpus_mask-not-cpus_ptr-in-__set_cpu.patch,
                      drop Revert-ath9k-Fix-general-protection-fault-in-ath9k_h.patch)

5.7-lucjan-ll45

- add sched-core-Check-cpus_mask-not-cpus_ptr-in-__set_cpu.patch
- add sched-alt-Backport-update-to-__set_cpus_allowed_ptr-.patch

5.7-lucjan-ll44

- add drivers-Revert-i2c-patches.patch

5.7-lucjan-ll43

- update zstd-patches

5.7-lucjan-ll42

- add BFQ-dev 20200708

5.7-lucjan-ll41-rc1 --> 5.7-lucjan-ll41

5.7-lucjan-ll41-rc1

- drop ALSA-usb-audio-Fix-packet-size-calculation.patch
- sync wit upstream (drop drm-amd-display-Only-revalidate-bandwidth-on-medium-.patch)

5.7-lucjan-ll40

- add Revert-ath9k-Fix-general-protection-fault-in-ath9k_h.patch
- add iwlwifi-Make-some-Killer-Wireless-AC-1550-cards-work.patch

5.7-lucjan-ll39

- i2c-designware-Only-check-the-first-byte-for-SMBus-b.patch --> i2c-designware-Fix-transfer-failures-for-invalid-SMB.patch
- update i2c-designware-Allow-block-reads-up-to-255-bytes.patch
- update HID-i2c-hid-Use-block-reads-when-possible-to-save-po.patch

5.7-lucjan-ll38

- drop block-Flag-elevators-suitable-for-single-queue.patch

5.6-lucjan-ll37

- add i2c-designware-Only-check-the-first-byte-for-SMBus-b.patch
- add i2c-designware-Allow-block-reads-up-to-255-bytes.patch
- add HID-i2c-hid-Use-block-reads-when-possible-to-save-po.patch

5.7-lucjan-ll36

- add BFQ-dev 20200702

5.7-lucjan-ll35

- add block-Add-CONFIG-to-rename-the-mq-deadline-scheduler.patch
- update LL-Brading v5.7

5.7-lucjan-ll34

- add BFQ-dev 20200701

5.7-lucjan-ll33

- update block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- update block-Fix-depends-for-BLK_DEV_ZONED.patch

5.7-lucjan-ll32

- add sched-alt-Fix-compilation-issue-when-CONFIG_SCHED_TR.patch

5.7-lucjan-l31-rc1 --> 5.7-lucjan-l31

5.7-lucjan-l31-rc1

- sync wit upstream (drop efi-libstub-Fix-path-separator-regression.patch)

5.7-lucjan-l30

- BMQ v5.7-r1 --> Project-C v5.7-r2

DROP 5.7-lucjan-l30-rc1

5.7-lucjan-l30-rc1

- sync wit upstream efi-libstub-Fix-path-separator-regression.patch)

5.7-lucjan-ll29

- add ALSA-usb-audio-Fix-packet-size-calculation.patch
- add drm-amd-display-Only-revalidate-bandwidth-on-medium-.patch

DROP 5.7-lucjan-ll29-rc1

5.7-lucjan-ll29-rc1

- sync wit upstream efi-libstub-Fix-path-separator-regression.patch)

5.7-lucjan-ll28

- add fixes-5.7-remove-unused-dev-variable.patch

DROP 5.7-lucjan-ll28-rc1

5.7-lucjan-ll28-rc1

- sync wit upstream efi-libstub-Fix-path-separator-regression.patch)

5.7-lucjan-ll27

- add BFQ-dev 20200628

5.7-lucjan-ll26

- add AUFS 20200518
- add fixes-5.7-remove-unnecessary-mt76x02_dma_reset.patch

5.7-lucjan-ll25

- add PCI-EDR-Log-only-ACPI_NOTIFY_DISCONNECT_RECOVER-even.patch
- add x86-fsgsbase-Fix-Xen-PV-support.patch
- add mt76-5.7-mt76x2-fix-pci-suspend.patch

5.7-lucjan-ll24

- add fsgsbase-5.7-remove-erroneous-if-expression-bit.patch

5.7-lucjan-ll23

- add selftests-x86-Add-a-syscall_arg_fault_64-test-for-ne.patch

5.7-lucjan-ll22

- add efi-libstub-Fix-path-separator-regression.patch

5.7-lucjan-ll21-rc1 --> 5.7-lucjan-ll21

5.7-lucjan-ll21-rc1

- sync wit upstream (drop aspm-simpler.patch)

5.7-lucjan-ll20

- add selftests-x86-fsgsbase-Fix-a-comment-in-the-ptrace_w.patch
- add selftests-x86-fsgsbase-Add-a-missing-memory-constrai.patch
- add x86-ptrace-Fix-32-bit-PTRACE_SETREGS-vs-fsbase-and-g.patch

DROP 5.7-lucjan-ll20-rc1

5.7-lucjan-ll20-rc1

- sync wit upstream (drop aspm-simpler.patch)

5.7-lucjan-ll19

- add mm-Fix-compile-error-due-to-COMPACTION_HPAGE_ORDER.patch

DROP 5.7-lucjan-ll19-rc1

5.7-lucjan-ll19-rc1

- sync wit upstream (drop aspm-simpler.patch)

5.7-lucjan-ll18-rc1 --> 5.7-lucjan-ll18

5.7-lucjan-ll18-rc1

- sync with upstream (drop mm-pagealloc.c-call-touch_nmi_watchdog-on-max-order-.patch,
                      drop mm-initialize-deferred-pages-with-interrupts-enabled.patch,
                      drop mm-call-cond_resched-from-deferred_init_memmap.patch)

5.7-lucjan-ll17

- drop mt76-mt76x2-fix-pci-suspend.patch
- drop mt76-5.7-pick-mt76_for_each_q_rx.patch

5.7-lucjan-ll16

- add mt76-mt76x2-fix-pci-suspend.patch
- add mt76-5.7-pick-mt76_for_each_q_rx.patch

5.7-lucjan-ll15

- add mm-Use-unsigned-types-for-fragmentation-score.patch

5.7-lucjan-ll14

- add Add-OpenRGB-patch-0c45e26c.patch

5.7-lucjan-ll13

- add mm-5.7-fix-proactive-compaction-build-with-THP-disab.patch

5.7-lucjan-ll12-rc1 --> 5.7-lucjan-ll12

5.7-lucjan-ll12-rc1

- sync wit upstream (drop KVM-x86-only-do-L1TF-workaround-on-affected-processo.patch)

5.7-lucjan-ll11

- update cpu-5.7-merge-graysky-s-patchset.patch

DROP 5.7-lucjan-ll11-rc1

5.7-lucjan-ll11-rc1

- sync wit upstream (drop KVM-x86-only-do-L1TF-workaround-on-affected-processo.patch)

5.7-lucjan-ll10

- add aspm-simpler.patch

5.7-lucjan-ll9

- add BFQ-dev 20200607

5.7-lucjan-ll8

- add BMQ v5.7-r1

5.7-lucjan-ll7-rc1 --> 5.7-lucjan-ll7

5.7-lucjan-ll7-rc1

- add Disable-CPU_FREQ_GOV_SCHEDUTIL.patch

5.7-lucjan-ll6-rc1

- add fixes-5.7-update-applesmc-fix-to-upstream-version.patch

5.7-lucjan-ll5-rc1

- drop BMQ-tkg v5.7-r0
- add bmq-Sync-14533a16c46d-thermal-cpu-cooling-sched-core.patch

5.7-lucjan-ll4-rc1

- add BMQ-tkg v5.7-r0

5.7-lucjan-ll3-rc1

- add mm-pagealloc.c-call-touch_nmi_watchdog-on-max-order-.patch
- add mm-initialize-deferred-pages-with-interrupts-enabled.patch
- add mm-call-cond_resched-from-deferred_init_memmap.patch
- add padata-remove-exit-routine.patch
- add padata-initialize-earlier.patch
- add padata-allocate-work-structures-for-parallel-jobs-fr.patch
- add padata-add-basic-support-for-multithreaded-jobs.patch
- add mm-move-zone-iterator-outside-of-deferred_init_maxor.patch
- add mm-parallelize-deferred_init_memmap.patch
- add padata-document-multithreaded-jobs.patch

5.7-lucjan-ll2-rc1

- add bmq-Fix-compile-error-in-psi.c.patch

5.7-lucjan-ll1-rc1

- add driver-core-remove-device_create_vargs.patch
- add bdi-unexport-bdi_register_va.patch
- add bdi-remove-bdi_register_owner.patch
- add bdi-simplify-bdi_alloc.patch
- add bdi-remove-the-name-field-in-struct-backing_dev_info.patch
- add bdi-fix-up-for-remove-the-name-field-in-struct-backi.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O-.patch
- add blk-mq-remove-the-bio-argument-to-prepare_request.patch
- add block-Flag-elevators-suitable-for-single-queue.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add x86-microcode-Force-update-a-uCode-even-if-the-rev-i.patch
- add x86-microcode-echo-2-reload-to-force-load-ucode.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add mm-Disable-watermark-boosting-by-default.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch
- add pci-Enable-overrides-for-missing-ACS-capabilities.patch
- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch
- add mm-Proactive-compaction.patch
- add mm-5.7-proactive-compaction-v6.patch
- add kbuild-Disable-stack-conservation-for-GCC.patch
- add x86-ptrace-Prevent-ptrace-from-clearing-the-FS-GS-se.patch
- add x86-cpu-Add-unsafe_fsgsbase-to-enable-CR4.FSGSBASE.patch
- add x86-fsgsbase-64-Add-intrinsics-for-FSGSBASE-instruct.patch
- add x86-fsgsbase-64-Enable-FSGSBASE-instructions-in-help.patch
- add x86-process-64-Use-FSBSBASE-in-switch_to-if-availabl.patch
- add x86-process-64-Make-save_fsgs-public-available.patch
- add x86-process-64-Use-FSGSBASE-instructions-on-thread-c.patch
- add x86-speculation-swapgs-Check-FSGSBASE-in-enabling-SW.patch
- add x86-entry-64-Switch-CR3-before-SWAPGS-in-paranoid-en.patch
- add x86-entry-64-Introduce-the-FIND_PERCPU_BASE-macro.patch
- add x86-entry-64-Handle-FSGSBASE-enabled-paranoid-entry-.patch
- add x86-cpu-Enable-FSGSBASE-on-64bit-by-default-and-add-.patch
- add x86-elf-Enumerate-kernel-FSGSBASE-capability-in-AT_H.patch
- add Documentation-x86-64-Add-documentation-for-GS-FS-add.patch
- add selftests-x86-fsgsbase-Test-GS-selector-on-ptracer-i.patch
- add selftests-x86-fsgsbase-Test-ptracer-induced-GS-base-.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- add lib-prepare-zstd-for-preboot-environment.patch
- add lib-prepare-xxhash-for-preboot-environment.patch
- add lib-add-zstd-support-to-decompress.patch
- add init-add-support-for-zstd-compressed-kernel.patch
- add usr-add-support-for-zstd-compressed-initramfs.patch
- add x86-bump-ZO_z_extra_bytes-margin-for-zstd.patch
- add x86-Add-support-for-ZSTD-compressed-kernel.patch
- add .gitignore-add-ZSTD-compressed-files.patch
- add init-add-support-for-zstd-compressed-modules.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add cpu-5.7-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add BFQ-dev 2020530
- add BMQ v5.7-r0
- add AUFS 20200518
- add UKSM for 5.7 
- add LL-Brading v5.7
- add LL-Add-.ll-version.patch

5.6-lucjan-ll61

- add fixes-5.6-update-applesmc-fix-to-upstream-version.patch

5.6-lucjan-ll60

- add kbuild-Disable-stack-conservation-for-GCC.patch

5.6-lucjan-ll59

- add mm-5.6-proactive-compaction-v6.patch

5.6-lucjan-ll58

- add fsgsbase-5.6-v13.patch

5.6-lucjan-ll57

- add block-Flag-elevators-suitable-for-single-queue.patch

5.6-lucjan-ll56-rc1 --> 5.6-lucjan-ll56

5.6-lucjan-ll56-rc1

- sync wit upstream (drop gcc-common.h-Update-for-GCC-10.patch)
- resync gcc-plugins-drop-support-for-GCC-4.7.patch

5.6-lucjan-ll55

- add mm-Don-t-stop-kswapd-on-a-per-node-basis-when-there-.patch

DROP 5.6-lucjan-ll55-rc1

5.6-lucjan-ll55-rc1

- sync wit upstream (drop gcc-common.h-Update-for-GCC-10.patch)
- resync gcc-plugins-drop-support-for-GCC-4.7.patch

5.6-lucjan-ll54

- update UKSM for 5.6

5.6-lucjan-ll53

- update UKSM for 5.6

5.6-lucjan-ll52

- add init-add-support-for-zstd-compressed-modules.patch

5.6-lucjan-ll51-rc1 --> 5.6-lucjan-ll51

5.6-lucjan-ll51-rc1

- sync with upstream (drop gcc-10-warnings-fix-low-hanging-fruit.patch,
                      drop Stop-the-ad-hoc-games-with-Wno-maybe-initialized.patch,
                      drop gcc-10-disable-zero-length-bounds-warning-for-now.patch,
                      drop gcc-10-disable-array-bounds-warning-for-now.patch,
                      drop gcc-10-disable-stringop-overflow-warning-for-now.patch,
                      drop gcc-10-disable-restrict-warning-for-now.patch,
                      drop gcc-10-avoid-shadowing-standard-library-free-in-cryp.patch,
                      drop gcc-10-mark-more-functions-__init-to-avoid-section-m.patch,
                      drop x86-Fix-early-boot-crash-on-gcc-10-next-try.patch,
                      drop Makefile-disallow-data-races-on-gcc-10-as-well.patch)

5.6-lucjan-ll50

- add KVM-x86-only-do-L1TF-workaround-on-affected-processo.patch

DROP 5.6-lucjan-ll50-rc1

5.6-lucjan-ll50-rc1

- sync with upstream (drop gcc-10-warnings-fix-low-hanging-fruit.patch,
                      drop Stop-the-ad-hoc-games-with-Wno-maybe-initialized.patch,
                      drop gcc-10-disable-zero-length-bounds-warning-for-now.patch,
                      drop gcc-10-disable-array-bounds-warning-for-now.patch,
                      drop gcc-10-disable-stringop-overflow-warning-for-now.patch,
                      drop gcc-10-disable-restrict-warning-for-now.patch,
                      drop gcc-10-avoid-shadowing-standard-library-free-in-cryp.patch,
                      drop gcc-10-mark-more-functions-__init-to-avoid-section-m.patch,
                      drop x86-Fix-early-boot-crash-on-gcc-10-next-try.patch,
                      drop Makefile-disallow-data-races-on-gcc-10-as-well.patch)

5.6-lucjan-ll49

- add mm-5.6-update-proactive-compaction-to-v5.patch

DROP 5.6-lucjan-ll49-rc2

5.6-lucjan-ll49-rc2

- sync wit upstream (drop Makefile-disallow-data-races-on-gcc-10-as-well.patch)

5.6-lucjan-ll49-rc1

- sync with upstream (drop gcc-10-warnings-fix-low-hanging-fruit.patch,
                      drop Stop-the-ad-hoc-games-with-Wno-maybe-initialized.patch,
                      drop gcc-10-disable-zero-length-bounds-warning-for-now.patch,
                      drop gcc-10-disable-array-bounds-warning-for-now.patch,
                      drop gcc-10-disable-stringop-overflow-warning-for-now.patch,
                      drop gcc-10-disable-restrict-warning-for-now.patch,
                      drop gcc-10-avoid-shadowing-standard-library-free-in-cryp.patch,
                      drop gcc-10-mark-more-functions-__init-to-avoid-section-m.patch,
                      drop x86-Fix-early-boot-crash-on-gcc-10-next-try.patch)

5.6-lucjan-ll48

- add blk-mq-remove-the-bio-argument-to-prepare_request.patch

5.6-lucjan-ll47

- add AUFS 20200518

5.6-lucjan-ll46

- update cpu-5.6-merge-graysky-s-patchset.patch

5.6-lucjan-ll45

- add gcc-10-warnings-fix-low-hanging-fruit.patch
- add Stop-the-ad-hoc-games-with-Wno-maybe-initialized.patch
- add gcc-10-disable-zero-length-bounds-warning-for-now.patch
- add gcc-10-disable-array-bounds-warning-for-now.patch
- add gcc-10-disable-stringop-overflow-warning-for-now.patch
- add gcc-10-disable-restrict-warning-for-now.patch
- add gcc-10-avoid-shadowing-standard-library-free-in-cryp.patch
- add gcc-10-mark-more-functions-__init-to-avoid-section-m.patch

5.6-lucjan-ll44

- add BFQ-dev 20200514

5.6-lucjan-ll43-rc1 --> 5.6-lucjan-ll43

5.6-lucjan-ll43-rc1

- sync with upstream (drop kvm-ioapic-Restrict-lazy-EOI-update-to-edge-triggere.patch,
                      drop bdi-move-bdi_dev_name-out-of-line.patch,
                      drop bdi-add-a-dev_name-field-to-struct-backing_dev_info.patch)

5.6-lucjan-ll42

- add vboxsf-don-t-use-the-source-name-in-the-bdi-name.patch
- add bdi-move-bdi_dev_name-out-of-line.patch
- add bdi-use-bdi_dev_name-to-get-device-name.patch
- add bdi-add-a-dev_name-field-to-struct-backing_dev_info.patch
- add driver-core-remove-device_create_vargs.patch
- add bdi-unexport-bdi_register_va.patch
- add bdi-remove-bdi_register_owner.patch
- add bdi-simplify-bdi_alloc.patch
- add bdi-remove-the-name-field-in-struct-backing_dev_info.patch
- add bdi-fix-up-for-remove-the-name-field-in-struct-backi.patch

5.6-lucjan-ll41

- update x86-fsgsbase-64-move-save_fsgs-to-header-file.patch
- update x86-fsgsbase-64-Use-FSGSBASE-instructions-on-thread-.patch

5.6-lucjan-ll40

- add x86-ptrace-Prevent-ptrace-from-clearing-the-FS-GS-se.patch
- add selftests-x86-fsgsbase-Test-GS-selector-on-ptracer-i.patch
- add x86-cpu-Add-unsafe_fsgsbase-to-enable-CR4.FSGSBASE.patch
- add x86-entry-64-Clean-up-paranoid-exit.patch
- add x86-entry-64-Switch-CR3-before-SWAPGS-in-paranoid-en.patch
- add x86-entry-64-Introduce-the-FIND_PERCPU_BASE-macro.patch
- add x86-entry-64-Handle-FSGSBASE-enabled-paranoid-entry-.patch
- add x86-entry-64-Document-GSBASE-handling-in-the-paranoi.patch
- add x86-fsgsbase-64-Add-intrinsics-for-FSGSBASE-instruct.patch
- add x86-fsgsbase-64-Enable-FSGSBASE-instructions-in-help.patch
- add x86-fsgsbase-64-Use-FSGSBASE-in-switch_to-if-availab.patch
- add x86-fsgsbase-64-move-save_fsgs-to-header-file.patch
- add x86-fsgsbase-64-Use-FSGSBASE-instructions-on-thread-.patch
- add x86-speculation-swapgs-Check-FSGSBASE-in-enabling-SW.patch
- add selftests-x86-fsgsbase-Test-ptracer-induced-GS-base-.patch
- add x86-fsgsbase-64-Enable-FSGSBASE-on-64bit-by-default-.patch
- add x86-elf-Enumerate-kernel-FSGSBASE-capability-in-AT_H.patch
- add Documentation-x86-64-Add-documentation-for-GS-FS-add.patch

5.6-lucjan-ll39

- add Makefile-disallow-data-races-on-gcc-10-as-well.patch
- add x86-Fix-early-boot-crash-on-gcc-10-next-try.patch

5.6-lucjan-ll38

- add BMQ v5.6-r4

5.6-lucjan-ll37

- add gcc-plugins-drop-support-for-GCC-4.7.patch
- add gcc-common.h-Update-for-GCC-10.patch

5.6-lucjan-ll36

- drop scatterlist-Don-t-allocate-sg-lists-using-__get_free.patch

5.6-lucjan-ll35

- add scatterlist-Don-t-allocate-sg-lists-using-__get_free.patch

5.6-lucjan-ll34

- add kvm-ioapic-Restrict-lazy-EOI-update-to-edge-triggere.patch

5.6-lucjan-ll33

- add BFQ-dev 20200506

5.6-lucjan-ll32

- add BFQ-dev 20200505

5.6-lucjan-ll31

- add pci-Enable-overrides-for-missing-ACS-capabilities.patch

5.6-lucjan-ll30

- add mm-pagealloc.c-call-touch_nmi_watchdog-on-max-order-.patch
- add mm-initialize-deferred-pages-with-interrupts-enabled.patch
- add mm-call-cond_resched-from-deferred_init_memmap.patch
- add padata-remove-exit-routine.patch
- add padata-initialize-earlier.patch
- add padata-allocate-work-structures-for-parallel-jobs-fr.patch
- add padata-add-basic-support-for-multithreaded-jobs.patch
- add mm-move-zone-iterator-outside-of-deferred_init_maxor.patch
- add mm-parallelize-deferred_init_memmap.patch
- add padata-document-multithreaded-jobs.patch

5.6-lucjan-ll29

- add BFQ-dev 20200424

5.6-lucjan-ll28

- add mm-5.6-update-proactive-compaction-to-v4.patch

5.6-lucjan-ll27

- update LL-Brading v5.6

5.6-lucjan-ll26

- BFQ-dev 20200424

5.6-lucjan-ll25

- drop cpufreq-intel_pstate-Set-default-cpufreq_driver-to-i.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch

5.6-lucjan-ll24

- drop Glitched-ondemand-BMQ.patch
- update LL-Brading v5.6

5.6-lucjan-ll23

- add Glitched-ondemand-BMQ.patch

5.6-lucjan-ll22

- drop ZEN-intel-pstate-Implement-enable-parameter.patch
- add cpufreq-intel_pstate-Set-default-cpufreq_driver-to-i.patch

5.6-lucjan-ll21-rc1 --> 5.6-lucjan-ll21

5.6-lucjan-ll21-rc1

- sync with upstream (drop Revert-ACPI-EC-Do-not-clear-boot_ec_is_ecdt-in-acpi_.patch,
                      drop drm-amdgpu-fix-the-hw-hang-during-perform-system-reb.patch)

5.6-lucjan-ll20

- drop x86-mm-pat-Restore-large-pages-after-fragmentation.patch
- add Revert-ACPI-EC-Do-not-clear-boot_ec_is_ecdt-in-acpi_.patch
- add drm-amdgpu-fix-the-hw-hang-during-perform-system-reb.patch
- add BMQ v5.6-r3

5.6-lucjan-ll19

- add x86-mm-pat-Restore-large-pages-after-fragmentation.patch

5.6-lucjan-ll18-rc1 --> 5.6-lucjan-ll18

5.6-lucjan-ll18-rc1

- resync UKSM for 5.6
- sync with upstream (drop ALSA-hda-Fix-potential-access-overflow-in-beep-helpe.patch,
                      drop drm-Remove-PageReserved-manipulation-from-drm_pci_al.patch)

5.6-lucjan-ll17

- add mm-Proactive-compaction.patch

5.6-lucjan-ll16

- add AUFS 20200413

5.6-lucjan-ll15

- drop consolemap-Fix-a-memory-leaking-bug-in-drivers-tty-v.patch

5.6-lucjan-ll14

- add BMQ v5.6-r2

5.6-lucjan-ll13

- update mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add mm-Disable-watermark-boosting-by-default.patch
- add mm-Fully-disable-watermark-boosting-when-it-isn-t-us.patch

5.6-lucjan-ll12

- update LL-Brading v5.6

5.6-lucjan-ll11

- add ALSA-hda-Fix-potential-access-overflow-in-beep-helpe.patch

5.6-lucjan-ll10

- drop bmq-5.6-fix-build-error-with-BMQ-disabled.patch
- add bmq-Fix-sync-up-error-when-BMQ-applied-but-not-enabl.patch
- add bmq-Fix-cpu-topology-setup-for-BMQ-in-ryzen-system.patch

5.6-lucjan-ll9

- add bmq-5.6-fix-build-error-with-BMQ-disabled.patch

5.6-lucjan-ll8

- add BMQ v5.6-r1

5.6-lucjan-ll7

- add lib-prepare-zstd-for-preboot-environment.patch
- add lib-prepare-xxhash-for-preboot-environment.patch
- add lib-add-zstd-support-to-decompress.patch
- add init-add-support-for-zstd-compressed-kernel.patch
- add usr-add-support-for-zstd-compressed-initramfs.patch
- add x86-bump-ZO_z_extra_bytes-margin-for-zstd.patch
- add x86-Add-support-for-ZSTD-compressed-kernel.patch
- add .gitignore-add-ZSTD-compressed-files.patch

5.6-lucjan-ll6-rc1 --> 5.6-lucjan-ll6

5.6-lucjan-ll6-rc1

- sync wit upstream (drop mac80211-fix-authentication-with-iwlwifi-mvm.patch)

5.6-lucjan-ll5-rc2

- sync wit upstream (drop bpf-Undo-incorrect-__reg_bound_offset32-handling.patch)

5.6-lucjan-ll15-rc1

- add mac80211-fix-authentication-with-iwlwifi-mvm.patch

DROP 5.6-lucjan-ll4-rc1 && 5.6-lucjan-ll4-rc2

5.6-lucjan-ll4-rc2

- sync wit upstream (drop bpf-Undo-incorrect-__reg_bound_offset32-handling.patch)

5.6-lucjan-ll4-rc1

- update exfat patches

DROP 5.6-lucjan-ll3-rc1 && 5.6-lucjan-ll3-rc2

5.6-lucjan-ll3-rc2

- sync wit upstream (drop bpf-Undo-incorrect-__reg_bound_offset32-handling.patch)

5.6-lucjan-ll3-rc1

- update exfat patches

DROP 5.6-lucjan-ll2-rc1 && 5.6-lucjan-ll2-rc2

5.6-lucjan-ll2-rc2

- sync wit upstream (drop bpf-Undo-incorrect-__reg_bound_offset32-handling.patch)

5.6-lucjan-ll2-rc1

- add UKSM for 5.6

DROP 5.6-lucjan-ll1-rc3 && 5.6-lucjan-ll1-rc4

5.6-lucjan-ll1-rc4

- sync with upstream (drop bpf-Undo-incorrect-__reg_bound_offset32-handling.patch)

5.6-lucjan-ll1-rc3

- add bpf-Undo-incorrect-__reg_bound_offset32-handling.patch

5.6-lucjan-ll1-rc2

- add exfat-Simplify-exfat_utf8_d_cmp-for-code-points-abov.patch
- add exfat-Fix-discard-support.patch
- add exfat-Remove-unnecessary-newlines-from-logging.patch

5.6-lucjan-ll1-rc1

- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add drm-Remove-PageReserved-manipulation-from-drm_pci_al.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O-.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add x86-microcode-Force-update-a-uCode-even-if-the-rev-i.patch
- add x86-microcode-echo-2-reload-to-force-load-ucode.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch
- add cpu-5.6-merge-graysky-s-patchset.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add consolemap-Fix-a-memory-leaking-bug-in-drivers-tty-v.patch
- add exfat-add-in-memory-and-on-disk-structures-and-heade.patch
- add exfat-add-super-block-operations.patch
- add exfat-add-inode-operations.patch
- add exfat-add-directory-operations.patch
- add exfat-add-file-operations.patch
- add exfat-add-fat-entry-operations.patch
- add exfat-add-bitmap-operations.patch
- add exfat-add-exfat-cache.patch
- add exfat-add-misc-operations.patch
- add exfat-add-nls-operations.patch
- add exfat-add-Kconfig-and-Makefile.patch
- add MAINTAINERS-add-exfat-filesystem.patch
- add exfat-update-file-system-parameter-handling.patch
- add staging-exfat-Remove-old-exfat-driver.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add kbuild-reuse-intermediate-linker-scripts-in-the-fina.patch
- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- add futex-Add-Proton-compatibility-code.patch
- add hwmon-applesmc-fix-UB-and-udelay-overflow.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add LL-elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add LL-Add-.ll-version.patch
- add LL-Implement-ll-branding-v5.6.patch
- add vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch
- add scsi-sd-block-Fix-regressions-in-read-only-block-dev.patch
- add scsi-sd-block-Update-fix-regressions-in-read-only-bl.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add BFQ-dev 20200330
- add BMQ v5.6-r0
- add AUFS 20200302
- add UKSM 

5.5-lucjan-ll55-rc1

- sync with upstream (drop iwlwifi-don-t-send-GEO_TX_POWER_LIMIT-if-no-wgds-tab.patch)

5.5-lucjan-ll55-rc1 --> 5.5-lucjan-ll55

5.5-lucjan-ll55-rc1

- sync with upstream (drop Revert-bpf-Provide-better-register-bounds-after-jmp3.patch)

5.5-lucjan-ll54

- add Revert-bpf-Provide-better-register-bounds-after-jmp3.patch
- add WireGuard 0.0.20200330

5.5-lucjan-ll53

- update BFQ-dev 20200327

5.5-lucjan-ll52

- add BFQ-dev 20200327

5.5-lucjan-ll51

- add BFQ-dev 20200324

5.5-lucjan-ll50

- add BFQ-dev 20200323

5.5-lucjan-ll49

- add iwlwifi-don-t-send-GEO_TX_POWER_LIMIT-if-no-wgds-tab.patch

5.5-lucjan-ll48

- add BFQ-dev 20200320

5.5-lucjan-ll47

- add WireGuard 0.0.20200318

5.5-lucjan-ll46

- add BFQ-dev 20200319

5.5-lucjan-ll45

- drop lib-add-support-for-ZSTD-compressed-kernel.patch
- drop x86-Enable-support-for-ZSTD-compressed-kernel.patch

5.5-lucjan-ll44

- add BFQ-dev 20200318
- add vfs-keep-inodes-with-page-cache-off-the-inode-shrink.patch
- add lib-add-support-for-ZSTD-compressed-kernel.patch
- add x86-Enable-support-for-ZSTD-compressed-kernel.patch

5.5-lucjan-ll43-rc1 --> 5.5-lucjan-ll43

5.5-lucjan-ll43-rc1

- sync with upstream (drop iwlwifi-mvm-Do-not-require-PHY_SKU-NVM-section-for-3.patch)

5.5-lucjan-ll42-rc1 --> 5.5-lucjan-ll42

5.5-lucjan-ll42-rc1

- sync with upstream (drop x86-boot-compressed-Don-t-declare-__force_order-in-k.patch)

5.5-lucjan-ll41

- add BFQ-dev 20200311

DROP 5.5-lucjan-ll41-rc1

5.5-lucjan-ll41-rc1

- sync with upstream (drop x86-boot-compressed-Don-t-declare-__force_order-in-k.patch)

5.5-lucjan-ll40

- add BMQ v5.5-r3

DROP 5.5-lucjan-ll40-rc1

5.5-lucjan-ll40-rc1

- sync with upstream (drop x86-boot-compressed-Don-t-declare-__force_order-in-k.patch)

5.5-lucjan-ll39

- add BFQ-dev 20200309

DROP 5.5-lucjan-ll39-rc1

5.5-lucjan-ll39-rc1

- sync with upstream (drop x86-boot-compressed-Don-t-declare-__force_order-in-k.patch)

5.5-lucjan-ll38

- add BFQ-dev 20200306

5.5-lucjan-ll37

- update LL-Implement-ll-branding-v5.5.patch

5.5-lucjan-ll36

- add BMQ v5.5-r2

5.5-lucjan-ll35

- add AUFS 20200302

5.5-lucjan-ll34-rc1 --> 5.5-lucjan-ll34

5.5-lucjan-ll34-rc1

- sync with upstream (drop drm-i915-Wean-off-drm_pci_alloc-drm_pci_free.patch,
                      drop drm-i915-execlists-Always-force-a-context-reload-whe.patch)

5.5-lucjan-ll33

- add x86-boot-compressed-Don-t-declare-__force_order-in-k.patch

5.5-lucjan-ll32-rc1 --> 5.5-lucjan-ll32

5.5-lucjan-ll32-rc1

- sync with upstream (drop rcu-nocb-Fix-dump_tree-hierarchy-print-always-active.patch)

5.5-lucjan-ll31

- update mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch

DROP 5.5-lucjan-ll31-rc1

5.5-lucjan-ll31-rc1

- sync with upstream (drop rcu-nocb-Fix-dump_tree-hierarchy-print-always-active.patch)

5.5-lucjan-ll30

- add mm-Stop-kswapd-early-when-nothing-s-waiting-for-it-t.patch

5.5-lucjan-ll29

- drop mm-ksm-introduce-ksm_madvise_merge-helper.patch
- drop mm-ksm-introduce-ksm_madvise_unmerge-helper.patch
- drop mm-ksm-proc-introduce-remote-merge.patch
- drop mm-ksm-proc-add-remote-KSM-documentation.patch
- add UKSM-for-5.5.patch

5.5-lucjan-ll28

- add hwmon-applesmc-fix-UB-and-udelay-overflow.patch
- update Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch

5.5-lucjan-ll27

- add WireGuard 0.0.20200215

5.5-lucjan-ll26

- add Don-t-report-an-error-if-PowerClamp-run-on-other-CPU.patch

5.5-lucjan-ll25

- fix drm-i915-Introduce-a-vma.kref.patch
- fix drm-i915-Serialise-i915_active_acquire-with-__active.patch
- add drm-i915-gem-Take-runtime-pm-wakeref-prior-to-unbind.patch
- add drm-i915-gem-Avoid-parking-the-vma-as-we-unbind.patch
- add drm-i915-gem-Try-to-flush-pending-unbind-events.patch
- add drm-i915-gem-Reinitialise-the-local-list-before-repe.patch
- add drm-i915-Add-a-simple-is-bound-check-before-unbindin.patch

5.5-lucjan-ll24

- add WireGuard 0.0.20200214

5.5-lucjan-ll23

- add compat-provide-compat_ptr-on-all-architectures.patch
- fix futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- fix selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- fix selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- fix selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- fix futex-Add-Proton-compatibility-code.patch

5.5-lucjan-ll22

- add drm-i915-Introduce-a-vma.kref.patch
- add drm-i915-Serialise-i915_active_acquire-with-__active.patch

5.5-lucjan-ll21

- drop futex-Split-key-setup-from-key-queue-locking-and-rea.patch
- drop futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- drop futex-Change-WAIT_MULTIPLE-opcode-to-31.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-timeout-test.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wouldblock-t.patch
- add selftests-futex-Add-FUTEX_WAIT_MULTIPLE-wake-up-test.patch
- add futex-Add-Proton-compatibility-code.patch

5.5-lucjan-ll20

- add drm-i915-Wean-off-drm_pci_alloc-drm_pci_free.patch
- add drm-Remove-PageReserved-manipulation-from-drm_pci_al.patch
- add drm-i915-execlists-Always-force-a-context-reload-whe.patch

5.5-lucjan-ll19-rc1 --> 5.5-lucjan-ll19

5.5-lucjan-ll19-rc1

- sync with upstream (drop Btrfs-send-fix-emission-of-invalid-clone-operations-.patch,
                      drop ALSA-hda-Fix-DP-MST-support-for-NVIDIA-codecs.patch)

5.5-lucjan-ll18

- add BFQ-dev 20200211

DROP 5.5-lucjan-ll18-rc1

5.5-lucjan-ll18-rc1

- sync with upstream (drop Btrfs-send-fix-emission-of-invalid-clone-operations-.patch,
                      drop ALSA-hda-Fix-DP-MST-support-for-NVIDIA-codecs.patch)

5.5-lucjan-ll17

- add BFQ-dev 20200204

DROP 5.5-lucjan-ll17-rc1

5.5-lucjan-ll17-rc1

- sync with upstream (drop Btrfs-send-fix-emission-of-invalid-clone-operations-.patch,
                      drop ALSA-hda-Fix-DP-MST-support-for-NVIDIA-codecs.patch)

5.5-lucjan-ll16

- add pipe-use-exclusive-waits-when-reading-or-writing.patch

DROP 5.5-lucjan-ll16-rc2

5.5-lucjan-ll16-rc2

- sync with upstream (drop Btrfs-send-fix-emission-of-invalid-clone-operations-.patch)

5.5-lucjan-ll16-rc1

- sync with upstream (drop ALSA-hda-Fix-DP-MST-support-for-NVIDIA-codecs.patch)

5.5-lucjan-ll15

- add WireGuard 0.0.20200205

5.5-lucjan-ll14

- update LL-Implement-ll-branding-v5.5.patch

5.5-lucjan-ll13

- fix ALSA-hda-Fix-DP-MST-support-for-NVIDIA-codecs.patch

5.5-lucjan-ll12

- add iwlwifi-mvm-Do-not-require-PHY_SKU-NVM-section-for-3.patch

5.5-lucjan-ll11-rc1 --> 5.5-lucjan-ll11

5.5-lucjan-ll11-rc1

- sync with upstream (drop btrfs-do-not-zero-f_bavail-if-we-have-available-spac.patch)

5.5-lucjan-ll10

- fix Btrfs-send-fix-emission-of-invalid-clone-operations-.patch
- add btrfs-do-not-zero-f_bavail-if-we-have-available-spac.patch

5.5-lucjan-ll9

- add ALSA-hda-Fix-DP-MST-support-for-NVIDIA-codecs.patch

5.5-lucjan-ll8

- add BMQ v5.5-r1

5.5-lucjan-ll7

- add AUFS 20200203

5.5-lucjan-ll6

- add BFQ-dev 20200203

5.5-lucjan-ll5

- add pci-Enable-overrides-for-missing-ACS-capabilities.patch

5.5-lucjan-ll4

- add Btrfs-send-fix-emission-of-invalid-clone-operations-.patch

5.5-lucjan-ll3

- add kbuild-reuse-intermediate-linker-scripts-in-the-fina.patch

5.5-lucjan-ll2

- add BFQ-dev 20200130

5.5-lucjan-ll1-rc2 --> 5.5-lucjan-ll1

5.5-lucjan-ll1-rc2

- add WireGuard 0.0.20200128

5.5-lucjan-ll1-rc1

- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add iwlwifi-pcie-restore-support-for-Killer-Qu-C0-NICs.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O-.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add x86-microcode-Force-update-a-uCode-even-if-the-rev-i.patch
- add x86-microcode-echo-2-reload-to-force-load-ucode.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add init-Kconfig-enable-O3-for-all-arches.patch
- add cpu-5.5-merge-graysky-s-patchset.patch
- add consolemap-Fix-a-memory-leaking-bug-in-drivers-tty-v.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add trace-add-trace-events-for-open-exec-and-uselib.patch
- add futex-Split-key-setup-from-key-queue-locking-and-rea.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add futex-Change-WAIT_MULTIPLE-opcode-to-31.patch
- add hwmon-Driver-for-disk-and-solid-state-drives-with-te.patch
- add mm-ksm-introduce-ksm_madvise_merge-helper.patch
- add mm-ksm-introduce-ksm_madvise_unmerge-helper.patch
- add mm-ksm-proc-introduce-remote-merge.patch
- add mm-ksm-proc-add-remote-KSM-documentation.patch
- add LL-Implement-ll-branding-v5.5.patch
- add LL-elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add sched-core-nr_migrate-256-increases-number-of-tasks-.patch
- add mm-set-2048-for-address_space-level-file-read-ahead-.patch
- add LL-Add-.ll-version.patch
- add scsi-sd-block-Fix-regressions-in-read-only-block-dev.patch
- add scsi-sd-block-Update-fix-regressions-in-read-only-bl.patch
- add ZEN-Add-VHBA-driver.patch
- add ZEN-intel-pstate-Implement-enable-parameter.patch
- add exfat-add-in-memory-and-on-disk-structures-and-heade.patch
- add exfat-add-super-block-operations.patch
- add exfat-add-inode-operations.patch
- add exfat-add-directory-operations.patch
- add exfat-add-file-operations.patch
- add exfat-add-fat-entry-operations.patch
- add exfat-add-bitmap-operations.patch
- add exfat-add-exfat-cache.patch
- add exfat-add-misc-operations.patch
- add exfat-add-nls-operations.patch
- add exfat-add-Kconfig-and-Makefile.patch
- add MAINTAINERS-add-exfat-filesystem.patch
- add staging-exfat-Remove-old-exfat-driver.patch
- add BMQ v5.5-r0
- add BFQ-dev 20200127
- add WireGuard 0.0.20200121
- add AUFS 20200127

5.4-lucjan-ll55-rc1 --> 5.4-lucjan-ll55

5.4-lucjan-ll55-rc1

- sync with upstream (drop pinctrl-sunrisepoint-Add-missing-Interrupt-Status-re.patch,
                      drop Revert-iwlwifi-mvm-fix-scan-config-command-size.patch)

5.4-lucjan-ll54

- add AUFS 20200127

5.4-lucjan-ll53

- add staging-exfat-Remove-old-exfat-driver.patch

5.4-lucjan-ll52-rc1 --> 5.4-lucjan-ll52

5.4-lucjan-ll52-rc1

- sync with upstream (drop ipmi-Fix-memory-leak-in-__ipmi_bmc_register.patch)

5.4-lucjan-ll51

- add exfat-add-in-memory-and-on-disk-structures-and-heade.patch
- add exfat-add-super-block-operations.patch
- add exfat-add-inode-operations.patch
- add exfat-add-directory-operations.patch
- add exfat-add-file-operations.patch
- add exfat-add-fat-entry-operations.patch
- add exfat-add-bitmap-operations.patch
- add exfat-add-exfat-cache.patch
- add exfat-add-misc-operations.patch
- add exfat-add-nls-operations.patch
- add exfat-add-Kconfig-and-Makefile.patch
- add MAINTAINERS-add-exfat-filesystem.patch
- add staging-exfat-make-staging-exfat-and-fs-exfat-mutual.patch
- add staging-exfat-Rename-EXFAT_FS-to-EXFAT_FS_SAMSUNG.patch
- add exfat-Depend-on-EXFAT_FS_SAMSUNG-n-from-mainline-exf.patch

5.4-lucjan-ll50-rc1 --> 5.4-lucjan-ll50

5.4-lucjan-ll50-rc1

- sync with upstream (drop i40e-prevent-memory-leak-in-i40e_setup_macvlans.patch,
                      drop ptp-free-ptp-device-pin-descriptors-properly.patch)

5.4-lucjan-ll49

- add WireGuard 0.0.20200121

5.4-lucjan-ll48

- add AUFS 20200120

5.4-lucjan-ll47

- update LL-Implement-ll-branding-v5.4.patch

5.4-lucjan-ll46

- add BMQ v5.4-r2
- update LL-Implement-ll-branding-v5.4.patch

5.4-lucjan-ll45

- add drm-amdgpu-Add-DC-feature-mask-to-disable-fractional.patch
- add ptp-free-ptp-device-pin-descriptors-properly.patch

5.4-lucjan-ll44-rc2 --> 5.4-lucjan-ll44

5.4-lucjan-ll44-rc2

- sync with upstream (drop spi-lpspi-fix-memory-leak-in-fsl_lpspi_probe.patch)

5.4-lucjan-ll44-rc1

- sync with upstream (drop PCI-pciehp-Do-not-disable-interrupt-twice-on-suspend.patch)

5.4-lucjan-ll43

- add ZEN-intel-pstate-Implement-enable-parameter.patch

5.4-lucjan-ll42-rc1 --> 5.4-lucjan-ll42

5.4-lucjan-ll42-rc1

- sync with upstream (drop rpmsg-char-release-allocated-memory.patch,
                           mwifiex-pcie-Fix-memory-leak-in-mwifiex_pcie_alloc_c.patch,
                           scsi-bfa-release-allocated-memory-in-case-of-error.patch,
                           rtl8xxxu-prevent-leaking-urb.patch,
                           ath10k-fix-memory-leak.patch)

5.4-lucjan-ll41

- drop drm-i915-gt-Detect-if-we-miss-WaIdleLiteRestore.patch

DROP 5.4-lucjan-ll41-rc1

5.4-lucjan-ll41-rc1

- sync with upstream (drop rpmsg-char-release-allocated-memory.patch,
                           mwifiex-pcie-Fix-memory-leak-in-mwifiex_pcie_alloc_c.patch,
                           scsi-bfa-release-allocated-memory-in-case-of-error.patch,
                           rtl8xxxu-prevent-leaking-urb.patch,
                           ath10k-fix-memory-leak.patch)

5.4-lucjan-ll40

- add AUFS 20200113

5.4-lucjan-ll39

- add drm-i915-Limit-audio-CDCLK-2-BCLK-constraint-back-to.patch

5.4-lucjan-ll38-rc1 --> 5.4-lucjan-ll38

5.4-lucjan-ll38-rc1

- sync with upstream (drop x86-intel-Disable-HPET-on-Intel-Ice-Lake-platforms.patch)

5.4-lucjan-ll37

- update LL-Implement-ll-branding-v5.4.patch

DROP 5.4-lucjan-ll37-rc1

5.4-lucjan-ll37-rc1

- sync with upstream (drop x86-intel-Disable-HPET-on-Intel-Ice-Lake-platforms.patch)

5.4-lucjan-ll36

- add Revert-iwlwifi-mvm-fix-scan-config-command-size.patch
- add e1000e-Revert-e1000e-Make-watchdog-use-delayed-work.patch

5.4-lucjan-ll35

- add ZEN-Update-VHBA-to-20200106.patch

5.4-lucjan-ll34

- add WireGuard 0.0.20200105

5.4-lucjan-ll33-rc1 --> 5.4-lucjan-ll33

5.4-lucjan-ll33-rc1

- sync with upstream (drop Revert-iwlwifi-assign-directly-to-iwl_trans-cfg-in-Q.patch)

5.4-lucjan-ll32

- add pinctrl-sunrisepoint-Add-missing-Interrupt-Status-re.patch

DROP 5.4-lucjan-ll32-rc1

5.4-lucjan-ll32-rc1

- sync with upstream (drop Revert-iwlwifi-assign-directly-to-iwl_trans-cfg-in-Q.patch)

5.4-lucjan-ll31

- add drm-i915-gt-Detect-if-we-miss-WaIdleLiteRestore.patch

5.4-lucjan-ll30-rc1 --> 5.4-lucjan-ll30

5.4-lucjan-ll30-rc1

- sync with upstream (drop x86-MCE-AMD-Do-not-use-rdmsr_safe_on_cpu-in-smca_con.patch,
                           x86-MCE-AMD-Allow-Reserved-types-to-be-overwritten-i.patch,
                           x86-mce-Fix-possibly-incorrect-severity-calculation-.patch,
                           iwlwifi-pcie-move-power-gating-workaround-earlier-in.patch,
                           x86-intel-Disable-HPET-on-Intel-Coffee-Lake-H-platfo.patch,
                           ASoC-SOF-enable-sync_write-in-hdac_bus.patch,
                           xhci-pci-Allow-host-runtime-PM-as-default-also-for-I.patch,
                           mwifiex-pcie-Fix-memory-leak-in-mwifiex_pcie_init_ev.patch.
                           rtlwifi-prevent-memory-leak-in-rtl_usb_probe.patch,
                           spi-gpio-prevent-memory-leak-in-spi_gpio_probe.patch,
                           loop-Better-discard-for-block-devices.patch)

5.4-lucjan-ll29

- drop mm-Proactive-compaction.patch

5.4-lucjan-ll28

- add WireGuard 0.0.20191226

5.4-lucjan-ll27

- add x86-intel-Disable-HPET-on-Intel-Coffee-Lake-H-platfo.patch
- add x86-intel-Disable-HPET-on-Intel-Ice-Lake-platforms.patch
- add drm-i915-save-AUD_FREQ_CNTRL-state-at-audio-domain-s.patch
- add drm-i915-Fix-audio-power-up-sequence-for-gen10-displ.patch
- add drm-i915-extend-audio-CDCLK-2-BCLK-constraint-to-mor.patch
- add ASoC-SOF-enable-sync_write-in-hdac_bus.patch
- add xhci-pci-Allow-host-runtime-PM-as-default-also-for-I.patch
- add iwlwifi-pcie-restore-support-for-Killer-Qu-C0-NICs.patch

5.4-lucjan-ll26

- add iwlwifi-pcie-move-power-gating-workaround-earlier-in.patch

5.4-lucjan-ll25

- add AUFS 20191223

5.4-lucjan-ll24

- add Merge-branch-ras-urgent-for-linus-of-git-git.kernel.patch

5.4-lucjan-ll23

- sync with upstream (drop ALSA-hda-Fix-regression-by-strip-mask-fix.patch)

5.4-lucjan-ll22-rc1 --> 5.4-lucjan-ll22

5.4-lucjan-ll22-rc1

- sync with upstream (drop drm-i915-fbc-Disable-fbc-by-default-on-all-glk.patch)

5.4-lucjan-ll21

- add rcu-nocb-Fix-dump_tree-hierarchy-print-always-active.patch

DROP 5.4-lucjan-ll21-rc1

5.4-lucjan-ll21-rc1

- sync with upstream (drop drm-i915-fbc-Disable-fbc-by-default-on-all-glk.patch)

5.4-lucjan-ll20

- add WireGuard 0.0.20191219

5.4-lucjan-ll19

- add Revert-iwlwifi-assign-directly-to-iwl_trans-cfg-in-Q.patch

5.4-lucjan-ll18

- add BMQ v5.4-r1

5.4-lucjan-ll17

- add drm-i915-fbc-Disable-fbc-by-default-on-all-glk.patch

5.4-lucjan-ll16-rc1 --> 5.4-lucjan-ll16

5.4-lucjan-ll16-rc1

- sync with upstream (drop ACPI-EC-Rework-flushing-of-pending-work.patch)

5.4-lucjan-ll15

- add ALSA-hda-Fix-regression-by-strip-mask-fix.patch

5.4-lucjan-ll14-rc1 --> 5.4-lucjan-ll14

5.4-lucjan-ll14-rc1

- sync with upstream (drop rsi-release-skb-if-rsi_prepare_beacon-fails.patch,
                      crypto-user-fix-memory-leak-in-crypto_reportstat.patch
                      and crypto-user-fix-memory-leak-in-crypto_report.patch)

5.4-lucjan-ll13

- add WireGuard 0.0.20191212

DROP 5.4-lucjan-ll13-rc1

5.4-lucjan-ll13-rc1

- sync with upstream (drop rsi-release-skb-if-rsi_prepare_beacon-fails.patch,
                      crypto-user-fix-memory-leak-in-crypto_reportstat.patch
                      and crypto-user-fix-memory-leak-in-crypto_report.patch)

5.4-lucjan-ll12

- add print-fsync-count-for-bootchart.patch

DROP 5.4-lucjan-ll12-rc1 && 5.4-lucjan-ll12-rc2

5.4-lucjan-ll12-rc2

- sync with upstream (drop crypto-user-fix-memory-leak-in-crypto_reportstat.patch
                      and crypto-user-fix-memory-leak-in-crypto_report.patch)

5.4-lucjan-ll12-rc1

- sync with upstream (drop rsi-release-skb-if-rsi_prepare_beacon-fails.patch)

5.4-lucjan-ll11

- add WireGuard 0.0.20191206

5.4-lucjan-ll10

- add BFQ-dev 20191206

5.4-lucjan-ll9

- add WireGuard 0.0.20191205

5.4-lucjan-ll8-rc1 --> 5.4-lucjan-ll8

5.4-lucjan-ll8-rc1

- sync with upstream (drop x86-fpu-Don-t-cache-access-to-fpu_fpregs_owner_ctx.patch)

5.4-lucjan-ll7

- add BFQ-dev 20191204

DROP 5.4-lucjan-ll7-rc1

5.4-lucjan-ll7-rc1

- sync with upstream (drop x86-fpu-Don-t-cache-access-to-fpu_fpregs_owner_ctx.patch)

5.4-lucjan-ll6

- add x86-fpu-Don-t-cache-access-to-fpu_fpregs_owner_ctx.patch

5.4-lucjan-ll5

- add ACPI-EC-Rework-flushing-of-pending-work.patch
- add ACPI-PM-s2idle-Rework-ACPI-events-synchronization.patch

5.4-lucjan-ll4

- drop block-bfq-Skip-tracing-hooks-if-possible.patch
- add block-bfq-DEBUG-add-logs-and-BUG_ONs.patch
- add block-bfq-do-not-idle-for-queues-with-no-proc-refs.patch
- add block-bfq-DEBUG-check-proc-refs-in-case-of-requeue.patch

5.4-lucjan-ll3

- add kbuild-reuse-intermediate-linker-scripts-in-the-fina.patch

5.4-lucjan-ll2

- add lib-devres-add-a-helper-function-for-ioremap_uc.patch
- add mfd-intel-lpss-Use-devm_ioremap_uc-for-MMIO.patch
- add PCI-pciehp-Do-not-disable-interrupt-twice-on-suspend.patch
- add PCI-pciehp-Prevent-deadlock-on-disconnect.patch

5.4-lucjan-ll1-rc3 --> 5.4-lucjan-ll1

5.4-lucjan-ll1-rc3

- add WireGuard 0.0.20191127

5.4-lucjan-ll1-rc2

- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch

5.4-lucjan-ll1-rc1

- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add blkcg-Make-bfq-disable-iocost-when-enabled.patch
- add block-bfq-present-a-double-cgroups-interface.patch
- add block-bfq-Skip-tracing-hooks-if-possible.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add x86-microcode-Force-update-a-uCode-even-if-the-rev-i.patch
- add x86-microcode-echo-2-reload-to-force-load-ucode.patch
- add fix-bug-in-ucode-force-reload-revision-check.patch
- add nvme-workaround.patch
- add cpu-5.4-make-O3-always-available.patch
- add cpu-5.4-merge-graysky-s-patchset.patch
- add consolemap-Fix-a-memory-leaking-bug-in-drivers-tty-v.patch
- add i40e-prevent-memory-leak-in-i40e_setup_macvlans.patch
- add ipmi-Fix-memory-leak-in-__ipmi_bmc_register.patch
- add rpmsg-char-release-allocated-memory.patch
- add media-rc-prevent-memory-leak-in-cx23888_ir_probe.patch
- add mwifiex-pcie-Fix-memory-leak-in-mwifiex_pcie_alloc_c.patch
- add mwifiex-pcie-Fix-memory-leak-in-mwifiex_pcie_init_ev.patch
- add rtlwifi-prevent-memory-leak-in-rtl_usb_probe.patch
- add spi-lpspi-fix-memory-leak-in-fsl_lpspi_probe.patch
- add scsi-bfa-release-allocated-memory-in-case-of-error.patch
- add rtl8xxxu-prevent-leaking-urb.patch
- add spi-gpio-prevent-memory-leak-in-spi_gpio_probe.patch
- add rsi-release-skb-if-rsi_prepare_beacon-fails.patch
- add ath10k-fix-memory-leak.patch
- add crypto-user-fix-memory-leak-in-crypto_reportstat.patch
- add crypto-user-fix-memory-leak-in-crypto_report.patch
- add net-sched-allow-configuring-cake-qdisc-as-default.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add -kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add loop-Better-discard-for-block-devices.patch
- add trace-add-trace-events-for-open-exec-and-uselib.patch
- add futex-Split-key-setup-from-key-queue-locking-and-rea.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add futex-Change-WAIT_MULTIPLE-opcode-to-31.patch
- add mm-ksm-introduce-ksm_madvise_merge-helper.patch
- add mm-ksm-introduce-ksm_madvise_unmerge-helper.patch
- add mm-ksm-proc-introduce-remote-merge.patch
- add mm-ksm-proc-add-remote-KSM-documentation.patch
- add LL-Implement-ll-branding-v5.4.patch
- add LL-elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add sched-core-nr_migrate-128-increases-number-of-tasks-.patch
- add mm-set-2048-for-address_space-level-file-read-ahead-.patch
- add LL-Add-.ll-version.patch
- add scsi-sd-block-Fix-regressions-in-read-only-block-dev.patch
- add scsi-sd-block-Update-fix-regressions-in-read-only-bl.patch
- add ZEN-Allow-setting-the-number-of-available-virtual-TT.patch
- add ZEN-Add-Thinkpad-SMAPI-driver.patch
- add ZEN-Allow-TCP-YeAH-as-default-congestion-control.patch
- add ZEN-Add-VHBA-driver.patch
- add BMQ v5.4-r0
- add WireGuard 0.0.20191012

5.3-lucjan-ll44

- add WireGuard 0.0.20191127

5.3-lucjan-ll43

- add Refresh-mm-Proactive-compaction-with-updated-version.patch

5.3-lucjan-ll42

- add i40e-prevent-memory-leak-in-i40e_setup_macvlans.patch
- add ipmi-Fix-memory-leak-in-__ipmi_bmc_register.patch
- add rpmsg-char-release-allocated-memory.patch
- add media-rc-prevent-memory-leak-in-cx23888_ir_probe.patch
- add nl80211-fix-memory-leak-in-nl80211_get_ftm_responder.patch
- add mwifiex-pcie-Fix-memory-leak-in-mwifiex_pcie_alloc_c.patch
- add mwifiex-pcie-Fix-memory-leak-in-mwifiex_pcie_init_ev.patch
- add iwlwifi-dbg_ini-fix-memory-leak-in-alloc_sgtable.patch
- add iwlwifi-pcie-fix-memory-leaks-in-iwl_pcie_ctxt_info_.patch
- add rtlwifi-prevent-memory-leak-in-rtl_usb_probe.patch
- add spi-lpspi-fix-memory-leak-in-fsl_lpspi_probe.patch
- add scsi-bfa-release-allocated-memory-in-case-of-error.patch
- add rtl8xxxu-prevent-leaking-urb.patch
- add spi-gpio-prevent-memory-leak-in-spi_gpio_probe.patch
- add rsi-release-skb-if-rsi_prepare_beacon-fails.patch
- add tracing-Have-error-path-in-predicate_parse-free-its-.patch
- add ath9k_htc-release-allocated-buffer-if-timed-out.patch
- add ath9k-release-allocated-buffer-if-timed-out.patch
- add RDMA-Fix-goto-target-to-release-the-allocated-memory.patch
- add ath10k-fix-memory-leak.patch
- add drm-amd-display-prevent-memory-leak.patch
- add Port-crypto-patches-from-clearlinux.patch

5.3-lucjan-ll41

- add BFQ-dev 20191119

5.3-lucjan-ll40

- update LL-Brading v5.3

5.3-lucjan-ll39

- add nvme-workaround.patch

5.3-lucjan-ll38

- add BFQ-dev 20191114

5.3-lucjan-ll37

- add BFQ-dev 20191113

5.3-lucjan-ll36-rc1 --> 5.3-lucjan-ll36

5.3-lucjan-ll36-rc1

- sync with upstream (drop mt76-dma-fix-buffer-unmap-with-non-linear-skbs.patch)

5.3-lucjan-ll35

- add BFQ-dev 20191112

DROP 5.3-lucjan-ll35-rc1

5.3-lucjan-ll35-rc1

- sync with upstream (drop mt76-dma-fix-buffer-unmap-with-non-linear-skbs.patch)

5.3-lucjan-ll34

- add fix-bug-in-ucode-force-reload-revision-check.patch

5.3-lucjan-ll33

- drop mm-Raise-hugepage-compaction-effort-to-60.patch

5.3-lucjan-ll32-rc1 --> 5.3-lucjan-ll32

5.3-lucjan-ll32-rc1

- sync with upstream (drop iwlwifi-exclude-GEO-SAR-support-for-3168.patch)

5.3-lucjan-ll31

- add mm-Raise-hugepage-compaction-effort-to-60.patch

DROP 5.3-lucjan-ll31-rc1

5.3-lucjan-ll31-rc1

- sync with upstream (drop iwlwifi-exclude-GEO-SAR-support-for-3168.patch)

5.3-lucjan-ll30

- add mm-Proactive-compaction.patch

DROP 5.3-lucjan-ll30-rc1

5.3-lucjan-ll30-rc1

- sync with upstream (drop iwlwifi-exclude-GEO-SAR-support-for-3168.patch)

5.3-lucjan-ll29

- drop mt76-mt76x2-disable-pcie_aspm-by-default.patch
- drop mt76-mt76x2-disable-frag_list-support.patch
- add mt76-mt76x2e-disable-pcie_aspm-by-default.patch
- add mt76-dma-fix-buffer-unmap-with-non-linear-skbs.patch
- add mt76-add-missing-ASPM-include.patch

5.3-lucjan-ll28

- add mm-ksm-proc-rework-error-handling.patch

5.3-lucjan-ll27

- add mm-ksm-proc-bail-out-on-kthreads.patch

5.3-lucjan-ll26

- add BMQ v5.3-r2

5.3-lucjan-ll25

- add iwlwifi-exclude-GEO-SAR-support-for-3168.patch

5.3-lucjan-ll24

- add AUFS 20191021
- add HID-Increase-maximum-report-size-allowed-by-hid_fiel.patch

5.3-lucjan-ll23

- drop add-trace-events-for-open-exec-and-uselib.patch
- add trace-add-trace-events-for-open-exec-and-uselib.patch

5.3-lucjan-ll22

- drop ath-do-not-enforce-EEPROM-regulatory-restrictions.patch
- add mt76-mt76x2-disable-pcie_aspm-by-default.patch
- add mt76-mt76x2-disable-frag_list-support.patch

5.3-lucjan-ll21-rc0

- add Revert-io_uring-only-flush-workqueues-on-fileset-rem.patch

5.3-lucjan-ll20

- update LL-Brading v5.3
- add LL-elevator-set-default-scheduler-to-bfq-for-blk-mq.patch

5.3-lucjan-ll19

- add AUFS 20191014

5.3-lucjan-ll18

- add WireGuard 0.0.20191012

5.3-lucjan-ll17

- add BFQ-dev 20191008

5.3-lucjan-ll16-rc1 --> 5.3-lucjan-ll16

5.3-lucjan-ll16-rc1

- sync with upstream (drop ipv6-Properly-check-reference-count-flag-before-taki.patch,
                      drop ipv6-do-not-free-rt-if-FIB_LOOKUP_NOREF-is-set-on-su.patch,
                      drop iwlwifi-fw-don-t-send-GEO_TX_POWER_LIMIT-command-to-.patch,
                      drop x86-amd_nb-Add-PCI-device-IDs-for-family-17h-model-7.patch
                      drop hwmon-k10temp-Add-PCI-device-IDs-for-family-17h-mode.patch)

5.3-lucjan-ll15

- add BMQ v5.3.1

DROP 5.3-lucjan-ll15-rc1

5.3-lucjan-ll15-rc1

- sync with upstream (drop ipv6-Properly-check-reference-count-flag-before-taki.patch,
                      drop ipv6-do-not-free-rt-if-FIB_LOOKUP_NOREF-is-set-on-su.patch,
                      drop iwlwifi-fw-don-t-send-GEO_TX_POWER_LIMIT-command-to-.patch,
                      drop x86-amd_nb-Add-PCI-device-IDs-for-family-17h-model-7.patch
                      drop hwmon-k10temp-Add-PCI-device-IDs-for-family-17h-mode.patch)

5.3-lucjan-ll14

- add ath-do-not-enforce-EEPROM-regulatory-restrictions.patch

DROP 5.3-lucjan-ll14-rc1

5.3-lucjan-ll14-rc1

- sync with upstream (drop ipv6-Properly-check-reference-count-flag-before-taki.patch,
                      drop ipv6-do-not-free-rt-if-FIB_LOOKUP_NOREF-is-set-on-su.patch,
                      drop iwlwifi-fw-don-t-send-GEO_TX_POWER_LIMIT-command-to-.patch,
                      drop x86-amd_nb-Add-PCI-device-IDs-for-family-17h-model-7.patch
                      drop hwmon-k10temp-Add-PCI-device-IDs-for-family-17h-mode.patch)

5.3-lucjan-ll13

- add BFQ-dev 20191002

DROP 5.3-lucjan-ll13-rc1

5.3-lucjan-ll13-rc1

- sync with upstream (drop ipv6-Properly-check-reference-count-flag-before-taki.patch,
                      drop ipv6-do-not-free-rt-if-FIB_LOOKUP_NOREF-is-set-on-su.patch,
                      drop iwlwifi-fw-don-t-send-GEO_TX_POWER_LIMIT-command-to-.patch,
                      drop x86-amd_nb-Add-PCI-device-IDs-for-family-17h-model-7.patch
                      drop hwmon-k10temp-Add-PCI-device-IDs-for-family-17h-mode.patch)
                      
5.3-lucjan-ll12

- add ipv6-Properly-check-reference-count-flag-before-taki.patch
- add ipv6-do-not-free-rt-if-FIB_LOOKUP_NOREF-is-set-on-su.patch
- add iwlwifi-fw-don-t-send-GEO_TX_POWER_LIMIT-command-to-.patch
- add Bluetooth-hidp-Fix-assumptions-on-the-return-value-o.patch

5.3-lucjan-ll11

- add fpga-altera-cvp-Fix-function-definition-argument.patch
- add fpga-altera-pr-ip-Make-alt_pr_unregister-function-vo.patch
- add fpga-dfl-use-driver-core-functions-not-sysfs-ones.patch
- add fpga-dfl-fme-add-DFL_FPGA_FME_PORT_RELEASE-ASSIGN-io.patch
- add fpga-dfl-pci-enable-SRIOV-support.patch
- add fpga-dfl-afu-add-AFU-state-related-sysfs-interfaces.patch
- add fpga-dfl-add-id_table-for-dfl-private-feature-driver.patch
- add fpga-dfl-make-uinit-callback-optional.patch
- add fpga-dfl-fme-add-capability-sysfs-interfaces.patch
- add fpga-altera-cvp-Discover-Vendor-Specific-offset.patch
- add fpga-altera-cvp-Preparation-for-V2-parts.patch
- add fpga-altera-cvp-Add-Stratix10-V2-Support.patch
- add fpga-dfl-make-init-callback-optional.patch
- add fpga-dfl-fme-convert-platform_driver-to-use-dev_grou.patch
- add fpga-dfl-afu-convert-platform_driver-to-use-dev_grou.patch
- add fpga-dfl-afu-add-userclock-sysfs-interfaces.patch
- add fpga-dfl-afu-expose-__afu_port_enable-disable-functi.patch
- add fpga-dfl-afu-add-error-reporting-support.patch
- add fpga-dfl-afu-add-STP-SignalTap-support.patch
- add fpga-dfl-fme-add-global-error-reporting-support.patch
- add driver-core-add-dev_groups-to-all-drivers.patch

5.3-lucjan-ll10

- drop fpga-dfl-fme-support-512bit-data-width-PR.patch
- drop fpga-dfl-fme-add-DFL_FPGA_FME_PORT_RELEASE-ASSIGN-io.patch
- drop fpga-dfl-pci-enable-SRIOV-support.patch
- drop fpga-dfl-afu-add-AFU-state-related-sysfs-interfaces.patch
- drop fpga-dfl-afu-add-userclock-sysfs-interfaces.patch
- drop fpga-dfl-add-id_table-for-dfl-private-feature-driver.patch
- drop fpga-dfl-afu-export-__port_enable-disable-function.patch
- drop fpga-dfl-afu-add-error-reporting-support.patch
- drop fpga-dfl-afu-add-STP-SignalTap-support.patch
- drop fpga-dfl-fme-add-capability-sysfs-interfaces.patch
- drop fpga-dfl-fme-add-global-error-reporting-support.patch
- drop fpga-dfl-fme-add-thermal-management-support.patch
- drop fpga-dfl-fme-add-power-management-support.patch
- drop fpga-dfl-fme-add-performance-reporting-support.patch
- add staging-exfat-add-exfat-filesystem-code-to-staging.patch
- add i8042-decrease-debug-message-level-to-info.patch

5.3-lucjan-ll9

- add net-sched-allow-configuring-cake-qdisc-as-default.patch

5.3-lucjan-ll8

- add add-trace-events-for-open-exec-and-uselib.patch

5.3-lucjan-ll7

- add x86-umip-Add-emulation-spoofing-for-UMIP-covered-ins.patch

5.3-lucjan-ll6

- update LL-Brading v5.3

5.3-lucjan-ll5

- update LL-Brading v5.3

5.3-lucjan-ll4

- update LL-Brading v5.3

5.3-lucjan-ll3

- add futex-Change-WAIT_MULTIPLE-opcode-to-31.patch

5.3-lucjan-ll2

- add AUFS 20190923
- drop add-sysctl-to-disallow-unprivileged-CLONE_NEWUSER-by.patch
- drop ZEN-Add-CONFIG-for-unprivileged_userns_clone.patch
- add ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C.patch

5.3-lucjan-ll1-rc3 --> 5.3-lucjan-ll1

5.3-lucjan-ll1-rc3

- add AUFS 20190909

5.3-lucjan-ll1-rc2

- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch

5.3-lucjan-ll1-rc1

- add add-sysctl-to-disallow-unprivileged-CLONE_NEWUSER-by.patch
- add ZEN-Add-CONFIG-for-unprivileged_userns_clone.patch
- add block-bfq-DEBUG-add-logs-and-BUG_ONs.patch
- add block-bfq-DEBUG-log-inject-limit-reset.patch
- add block-bfq-DEBUG-log-think-time-state-change.patch
- add block-bfq-DEBUG-add-check-and-logs-on-rq_in_driver-i.patch
- add block-bfq-DEBUG-log-think-time-update.patch
- add block-bfq-DEBUG-add-logs-on-waker-detection.patch
- add ablock-bfq-DEBUG-add-BUG_ONs-on-waker-detection.patch
- add block-bfq-DEBUG-add-more-BUG_ONs.patch
- add block-bfq-DEBUG-check-that-injection-never-chooses-i.patch
- add block-bfq-DEBUG-add-more-checks-on-next_rq.patch
- add block-bfq-DEBUG-log-preemption-info.patch
- add block-bfq-DEBUG-log-per-queue-rq-completion-times.patch
- add block-bfq-DEBUG-log-TOTALLY_SEEKY.patch
- add block-bfq-update-inject-limit-only-after-injection-o.patch
- add block-bfq-reduce-upper-bound-for-inject-limit-to-max.patch
- add block-bfq-DEBUG-log-pid-of-queue-chosen-for-injectio.patch
- add block-bfq-increase-update-frequency-of-inject-limit.patch
- add block-bfq-push-up-injection-only-after-setting-servi.patch
- add block-bfq-raise-bfq-version-to-v11.patch
- add block-bfq-DEBUG-remove-stale-BFQ_BUG_ONs-in-bfq_bfqq.patch
- add port-bfq-Fix-the-missing-barrier-in-__bfq_entity_upd.patch
- add bfq-Extract-bfq_group_set_weight-from-bfq_io_set_wei.patch
- add Add-per-device-weight.patch
- add bfq-Fix-bfq-linkage-error.patch
- add block-bfq-delete-bfq-prefix-from-cgroup-filenames.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_B.patch
- add block-Fix-depends-for-BLK_DEV_ZONED.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O-.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch
- add Initialize-ata-before-graphics.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add print-CPU-that-faults.patch
- add x86-microcode-Force-update-a-uCode-even-if-the-rev-i.patch
- add x86-microcode-echo-2-reload-to-force-load-ucode.patch
- add fpga-dfl-fme-support-512bit-data-width-PR.patch
- add fpga-dfl-fme-add-DFL_FPGA_FME_PORT_RELEASE-ASSIGN-io.patch
- add fpga-dfl-pci-enable-SRIOV-support.patch
- add fpga-dfl-afu-add-AFU-state-related-sysfs-interfaces.patch
- add fpga-dfl-afu-add-userclock-sysfs-interfaces.patch
- add fpga-dfl-add-id_table-for-dfl-private-feature-driver.patch
- add fpga-dfl-afu-export-__port_enable-disable-function.patch
- add fpga-dfl-afu-add-error-reporting-support.patch
- add fpga-dfl-afu-add-STP-SignalTap-support.patch
- add fpga-dfl-fme-add-capability-sysfs-interfaces.patch
- add fpga-dfl-fme-add-global-error-reporting-support.patch
- add fpga-dfl-fme-add-thermal-management-support.patch
- add fpga-dfl-fme-add-power-management-support.patch
- add fpga-dfl-fme-add-performance-reporting-support.patch
- add cpu-5.3-add-a-CONFIG-option-that-sets-O3.patch
- add cpu-5.3-merge-graysky-s-patchset.patch
- add consolemap-Fix-a-memory-leaking-bug-in-drivers-tty-v.patch
- add futex-Split-key-setup-from-key-queue-locking-and-rea.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch
- add x86-amd_nb-Add-PCI-device-IDs-for-family-17h-model-7.patch
- add hwmon-k10temp-Add-PCI-device-IDs-for-family-17h-mode.patch
- add mm-ksm-introduce-ksm_madvise_merge-helper.patch
- add mm-ksm-introduce-ksm_madvise_unmerge-helper.patch
- add mm-ksm-proc-introduce-remote-merge.patch
- add mm-ksm-proc-add-remote-KSM-documentation.patch
- add loop-Better-discard-for-block-devices.patch
- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch
- add scsi-sd-block-Fix-regressions-in-read-only-block-dev.patch
- add scsi-sd-block-Update-fix-regressions-in-read-only-bl.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add ZEN-Allow-setting-the-number-of-available-virtual-TT.patch
- add ZEN-Add-Thinkpad-SMAPI-driver.patch
- add ZEN-Allow-TCP-YeAH-as-default-congestion-control.patch
- add ZEN-Add-VHBA-driver.patch
- add LL-Add-.ll-version.patch
- add LL-Brading v5.3
- add BMQ v1.00
- add AUFS 20190902
- add WireGuard 0.0.20190913

5.2-lucjan-ll42-rc1 --> 5.2-lucjan-ll42

5.2-lucjan-ll42-rc1

- sync with upstream (drop Btrfs-fix-unwritten-extent-buffers-and-hangs-on-futu.patch)

5.2-lucjan-ll41

- add BFQ-dev 20190915

DROP 5.2-lucjan-ll41-rc1

5.2-lucjan-ll41-rc1

- sync with upstream (drop Btrfs-fix-unwritten-extent-buffers-and-hangs-on-futu.patch)

5.2-lucjan-ll40

- add WireGuard 0.0.20190913

DROP 5.2-lucjan-ll40-rc1

5.2-lucjan-ll40-rc1

- sync with upstream (drop Btrfs-fix-unwritten-extent-buffers-and-hangs-on-futu.patch)

5.2-lucjan-ll39

- add Btrfs-fix-unwritten-extent-buffers-and-hangs-on-futu.patch

5.2-lucjan-ll38

- add BFQ-dev 20190912

5.2-lucjan-ll37

- add BFQ-dev 20190910

5.2-lucjan-ll36

- add bmq-5.2-unbreak-systemd-detect-virt.patch

5.2-lucjan-ll35

- add WireGuard 0.0.20190905

5.2-lucjan-ll34-rc1 --> 5.2-lucjan-ll34

5.2-lucjan-ll34-rc1

- sync with upstream (drop add mt76-usb-fix-rx-A-MSDU-support.patch)

5.2-lucjan-ll33

- add VHBA 20190831
- add AUFS 20190902

5.2-lucjan-ll32-rc1 --> 5.2-lucjan-ll32

5.2-lucjan-ll32-rc1

- sync with upstream (drop drm-amdgpu-pin-the-csb-buffer-on-hw-init-for-gfx-v8.patch and
                      iwlwifi-mvm-disable-TX-AMSDU-on-older-NICs.patch)

5.2-lucjan-ll31

- add x86-amd_nb-Add-PCI-device-IDs-for-family-17h-model-7.patch
- add hwmon-k10temp-Add-PCI-device-IDs-for-family-17h-mode.patch

DROP 5.2-lucjan-ll31-rc1

5.2-lucjan-ll31-rc1

- sync with upstream (drop drm-amdgpu-pin-the-csb-buffer-on-hw-init-for-gfx-v8.patch and
                      iwlwifi-mvm-disable-TX-AMSDU-on-older-NICs.patch)

5.2-lucjan-ll30

- add futex-Consolidate-duplicated-timer-setup-code.patch
- add futex-Cleanup-generic-SMP-variant-of-arch_futex_atom.patch
- add futex-Split-key-setup-from-key-queue-locking-and-rea.patch
- add futex-Implement-mechanism-to-wait-on-any-of-several-.patch

5.2-lucjan-ll29-rc1 --> 5.2-lucjan-ll29

5.2-lucjan-ll29-rc1

- add Fix-compilation-with-5.2.10.patch
- sync with upstream (drop iwlwifi-Add-support-for-SAR-South-Korea-limitation.patch and
                      ALSA-usb-audio-Fix-an-OOB-bug-in-parse_audio_mixer_u.patch)

5.2-lucjan-ll28

- add block-bfq-update-inject-limit-only-after-injection-o.patch
- add block-bfq-reduce-upper-bound-for-inject-limit-to-max.patch
- add block-bfq-DEBUG-log-pid-of-queue-chosen-for-injectio.patch
- add block-bfq-increase-update-frequency-of-inject-limit.patch
- add block-bfq-push-up-injection-only-after-setting-servi.patch
- add block-bfq-raise-bfq-version-to-v11.patch

DROP 5.2-lucjan-ll28-rc1

5.2-lucjan-ll28-rc1

- add Fix-compilation-with-5.2.10.patch
- sync with upstream (drop iwlwifi-Add-support-for-SAR-South-Korea-limitation.patch and
                      ALSA-usb-audio-Fix-an-OOB-bug-in-parse_audio_mixer_u.patch)

5.2-lucjan-ll27

- update graysky's patch

DROP 5.2-lucjan-ll27-rc1

5.2-lucjan-ll27-rc1

- add Fix-compilation-with-5.2.10.patch
- sync with upstream (drop iwlwifi-Add-support-for-SAR-South-Korea-limitation.patch and
                      ALSA-usb-audio-Fix-an-OOB-bug-in-parse_audio_mixer_u.patch)

5.2-lucjan-ll26

- add ALSA-usb-audio-Fix-an-OOB-bug-in-parse_audio_mixer_u.patch

DROP 5.2-lucjan-ll26-rc2

5.2-lucjan-ll26-rc2

- sync with upstream (drop iwlwifi-Add-support-for-SAR-South-Korea-limitation.patch)

5.2-lucjan-ll26-rc1

- add Fix-compilation-with-5.2.10.patch

5.2-lucjan-ll25

- add Add-ucode-reload-force-feature.patch
- add Print-cpu-number-when-we-print-a-crash.patch

DROP 5.2-lucjan-ll25-rc1

5.2-lucjan-ll25-rc1

- add Fix-compilation-with-5.2.10.patch

5.2-lucjan-ll24

- add drm-amdgpu-pin-the-csb-buffer-on-hw-init-for-gfx-v8.patch

5.2-lucjan-ll23-rc1 --> 5.2-lucjan-ll23

5.2-lucjan-ll23-rc1

- sync with upstream (drop netfilter-nf_tables-fix-module-autoload-for-redir.patch)

5.2-lucjan-ll22

- add BMQ 0.99

DROP 5.2-lucjan-ll22-rc1

5.2-lucjan-ll22-rc1

- sync with upstream (drop netfilter-nf_tables-fix-module-autoload-for-redir.patch)

5.2-lucjan-ll21

- add mt76-usb-fix-rx-A-MSDU-support.patch
- Revert-port-block-bfq-reset-last_completed_rq_bfqq-i.patch,
  Revert-port-block-bfq-move-update-of-waker-and-woken.patch and 
  Revert-port-block-bfq-move-update-of-waker-and-woken.patch -> 
  Drop-block-bfq-ports.patch
    
5.2-lucjan-ll20

- add Revert-port-block-bfq-reset-last_completed_rq_bfqq-i.patch
- add Revert-port-block-bfq-move-update-of-waker-and-woken.patch
- add Revert-port-block-bfq-handle-NULL-return-value-by-bf.patch
- add block-bfq-reset-last_completed_rq_bfqq-if-the-pointe.patch
- add block-bfq-move-update-of-waker-and-woken-list-to-que.patch
- add block-bfq-handle-NULL-return-value-by-bfq_init_rq.patch

5.2-lucjan-ll19

- add Revert-bfq-Fix-the-missing-barrier-in-__bfq_entity_u.patch
- add port-bfq-Fix-the-missing-barrier-in-__bfq_entity_upd.patch

5.2-lucjan-ll18

- add port-block-bfq-reset-last_completed_rq_bfqq-if-the-p.patch
- add port-block-bfq-move-update-of-waker-and-woken-list-t.patch
- add port-block-bfq-handle-NULL-return-value-by-bfq_init_.patch

5.2-lucjan-ll17

- add Revert-block-bfq-add-weight-symlink-to-the-bfq.weigh.patch
- add Revert-cgroup-let-a-symlink-too-be-created-with-a-cf.patch
- add bfq-Fix-the-missing-barrier-in-__bfq_entity_update_w.patch
- add bfq-Extract-bfq_group_set_weight-from-bfq_io_set_wei.patch
- add bfq-Add-per-device-weight.patch

5.2-lucjan-ll16

- resync AUFS

5.2-lucjan-ll15

- resync AUFS

5.2-lucjan-ll14

- add aufs-bump-to-v20190805.patch

5.2-lucjan-ll13

- update LL-Implement-ll-branding-v5.2.patch

5.2-lucjan-ll12-rc1 --> 5.2-lucjan-ll12

5.2-lucjan-ll12-rc1

- sync with upstream (drop drm-edid-Fix-a-missing-check-bug-in-drm_load_edid_fi.patch)

5.2-lucjan-ll11

- update LL-Implement-ll-branding-v5.2.patch

5.2-lucjan-ll10-rc1 --> 5.2-lucjan-ll10

5.2-lucjan-ll10-rc1

- sync with upstream (drop block-bfq-fix-rq_in_driver-check-in-bfq_update_injec.patch)

5.2-lucjan-ll9-rc1 --> 5.2-lucjan-ll9

5.2-lucjan-ll9-rc1

- sync with upstream (drop Revert-e1000e-fix-cyclic-resets-at-link-up-with-acti.patch and 
e1000e-start-network-tx-queue-only-when-link-is-up.patch`)

5.2-lucjan-ll8

- update LL-Implement-ll-branding-v5.2.patch
- add iwlwifi-Add-support-for-SAR-South-Korea-limitation.patch

5.2-lucjan-ll7

- add netfilter-nf_tables-fix-module-autoload-for-redir.patch

5.2-lucjan-ll6

- add block-bfq-add-logs-and-BUG_ONs.patch
- add block-bfq-DEBUG-log-inject-limit-reset.patch
- add block-bfq-DEBUG-log-think-time-state-change.patch
- add block-bfq-DEBUG-add-check-and-logs-on-rq_in_driver-i.patch
- add block-bfq-DEBUG-log-think-time-update.patch
- add block-bfq-DEBUG-add-logs-on-waker-detection.patch
- add block-bfq-DEBUG-add-BUG_ONs-on-waker-detection.patch
- add block-bfq-DEBUG-add-more-BUG_ONs.patch
- add block-bfq-DEBUG-check-that-injection-never-chooses-i.patch
- add block-bfq-DEBUG-add-more-checks-on-next_rq.patch
- add block-bfq-DEBUG-log-preemption-info.patch
- add block-bfq-DEBUG-log-per-queue-rq-completion-times.patch
- add block-bfq-DEBUG-log-TOTALLY_SEEKY.patch
- add block-bfq-check-also-in-flight-I-O-in-dispatch-plugg.patch
- drop block-initialize-the-write-priority-in-blk_rq_bio_pr.patch
- drop block-remove-blk_init_request_from_bio.patch
- drop block-remove-the-bi_phys_segments-field-in-struct-bi.patch
- drop block-simplify-blk_recalc_rq_segments.patch
- drop block-untangle-the-end-of-blk_bio_segment_split.patch
- drop block-mark-blk_rq_bio_prep-as-inline.patch
- drop blk-cgroup-factor-out-a-helper-to-read-rwstat-counte.patch
- drop blk-cgroup-pass-blkg_rwstat-structures-by-reference.patch
- drop blk-cgroup-introduce-a-new-struct-blkg_rwstat_sample.patch
- drop blk-cgroup-move-struct-blkg_stat-to-bfq.patch
- drop bfq-iosched-move-bfq_stat_recursive_sum-into-the-onl.patch
- drop block-rename-CONFIG_DEBUG_BLK_CGROUP-to-CONFIG_BFQ_C.patch
- drop block-improve-print_req_error.patch
- drop cgroup-export-css_next_descendant_pre-for-bfq.patch

5.2-lucjan-ll5

- add aufs-fix-version.patch
- add BMQ 0.98

5.2-lucjan-ll4

- add cpu-5.2-add-Goldmont-support.patch

5.2-lucjan-ll3

- add cpu-5.2-add-Zen-2-support.patch

5.2-lucjan-ll2-rc1 --> 5.2-lucjan-ll2

5.2-lucjan-ll2-rc1

- sync with upstream (drop block-bfq-NULL-out-the-bic-when-it-s-no-longer-valid.patch)

5.2-lucjan-ll1-rc4 -> 5.2-lucjan-ll1

5.2-lucjan-ll1-rc4

- add kbuild-add-fcf-protection-none-to-retpoline-flags.patch

5.2-lucjan-ll1-rc3

- add block-Fix-depends-for-BLK_DEV_ZONED.patch

5.2-lucjan-ll1-rc2

- add fpga-dfl-fme-mgr-fix-FME_PR_INTFC_ID-register-addres.patch
- add fpga-dfl-fme-remove-copy_to_user-in-ioctl-for-PR.patch
- add fpga-dfl-fme-align-PR-buffer-size-per-PR-datawidth.patch
- add fpga-dfl-fme-support-512bit-data-width-PR.patch
- add fpga-dfl-fme-add-DFL_FPGA_FME_PORT_RELEASE-ASSIGN-io.patch
- add fpga-dfl-pci-enable-SRIOV-support.patch
- add fpga-dfl-afu-add-AFU-state-related-sysfs-interfaces.patch
- add fpga-dfl-afu-add-userclock-sysfs-interfaces.patch
- add fpga-dfl-add-id_table-for-dfl-private-feature-driver.patch
- add fpga-dfl-afu-export-__port_enable-disable-function.patch
- add fpga-dfl-afu-add-error-reporting-support.patch
- add fpga-dfl-afu-add-STP-SignalTap-support.patch
- add fpga-dfl-fme-add-capability-sysfs-interfaces.patch
- add fpga-dfl-fme-add-global-error-reporting-support.patch
- add fpga-dfl-fme-add-thermal-management-support.patch
- add fpga-dfl-fme-add-power-management-support.patch
- add fpga-dfl-fme-add-performance-reporting-support.patch
- add block-set-rq_affinity-2-for-full-multithreading-I-O-.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add iwlwifi-mvm-disable-TX-AMSDU-on-older-NICs.patch
- update AUFS

5.2-lucjan-ll1-rc1

- add add-sysctl-to-disallow-unprivileged-CLONE_NEWUSER-by.patch
- add ZEN-Add-CONFIG-for-unprivileged_userns_clone.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_BFQ.patch
- add cgroup-let-a-symlink-too-be-created-with-a-cftype-fi.patch
- add block-bfq-add-weight-symlink-to-the-bfq.weight-cgrou.patch
- add block-initialize-the-write-priority-in-blk_rq_bio_pr.patch
- add block-remove-blk_init_request_from_bio.patch
- add block-remove-the-bi_phys_segments-field-in-struct-bi.patch
- add block-simplify-blk_recalc_rq_segments.patch
- add block-untangle-the-end-of-blk_bio_segment_split.patch
- add block-mark-blk_rq_bio_prep-as-inline.patch
- add blk-cgroup-factor-out-a-helper-to-read-rwstat-counte.patch
- add blk-cgroup-pass-blkg_rwstat-structures-by-reference.patch
- add blk-cgroup-introduce-a-new-struct-blkg_rwstat_sample.patch
- add blk-cgroup-move-struct-blkg_stat-to-bfq.patch
- add bfq-iosched-move-bfq_stat_recursive_sum-into-the-onl.patch
- add block-rename-CONFIG_DEBUG_BLK_CGROUP-to-CONFIG_BFQ_C.patch
- add block-improve-print_req_error.patch
- add cgroup-export-css_next_descendant_pre-for-bfq.patch
- add block-bfq-reset-inject-limit-when-think-time-state-c.patch
- add block-bfq-fix-rq_in_driver-check-in-bfq_update_injec.patch
- add block-bfq-update-base-request-service-times-when-pos.patch
- add block-bfq-bring-forward-seek-think-time-update.patch
- add block-bfq-detect-wakers-and-unconditionally-inject-t.patch
- add block-bfq-preempt-lower-weight-or-lower-priority-que.patch
- add block-bfq-re-schedule-empty-queues-if-they-deserve-I.patch
- add block-bfq-Init-saved_wr_start_at_switch_to_srt-in-un.patch
- add block-bfq-NULL-out-the-bic-when-it-s-no-longer-valid.patch
- add i8042-decrease-debug-message-level-to-info.patch
- add Increase-the-ext4-default-commit-age.patch
- add silence-rapl.patch
- add pci-pme-wakeups.patch
- add ksm-wakeups.patch
- add intel_idle-tweak-cpuidle-cstates.patch
- add bootstats-add-printk-s-to-measure-boot-time-in-more-.patch
- add smpboot-reuse-timer-calibration.patch
- add raid6-add-Kconfig-option-to-skip-raid6-benchmarking.patch
- add Initialize-ata-before-graphics.patch
- add reduce-e1000e-boot-time-by-tightening-sleep-ranges.patch
- add give-rdrand-some-credit.patch
- add ipv4-tcp-allow-the-memory-tuning-for-tcp-to-go-a-lit.patch
- add e1000e-increase-pause-and-refresh-time.patch
- add kernel-time-reduce-ntp-wakeups.patch
- add init-wait-for-partition-and-retry-scan.patch
- add print-fsync-count-for-bootchart.patch
- add Add-boot-option-to-allow-unsigned-modules.patch
- add Enable-stateless-firmware-loading.patch
- add Migrate-some-systemd-defaults-to-the-kernel-defaults.patch
- add xattr-allow-setting-user.-attributes-on-symlinks-by-.patch
- add use-lfence-instead-of-rep-and-nop.patch
- add do-accept-in-LIFO-order-for-cache-efficiency.patch
- add locking-rwsem-spin-faster.patch
- add thp-fix.patch
- add ata-libahci-ignore-staggered-spin-up.patch
- add cpu-5.2-merge-graysky-s-patchset.patch
- add cpu-5.2-add-a-CONFIG-option-that-sets-O3.patch
- add consolemap-Fix-a-memory-leaking-bug-in-drivers-tty-v.patch
- add drm-edid-Fix-a-missing-check-bug-in-drm_load_edid_fi.patch
- add wcd9335-fix-a-incorrect-use-of-kstrndup.patch
- add clk-sunxi-fix-a-missing-check-bug-in-sunxi_divs_clk_.patch
- add scsi-mpt3sas_ctl-fix-double-fetch-bug-in-_ctl_ioctl_.patch
- add io_uring-restructure-io_-read-write-control-flow.patch
- add mm-ksm-introduce-ksm_madvise_merge-helper.patch
- add mm-ksm-introduce-ksm_madvise_unmerge-helper.patch
- add mm-ksm-proc-introduce-remote-merge.patch
- add mm-ksm-proc-add-remote-KSM-documentation.patch
- add LL-Implement-ll-branding-v5.2.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add LL-elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add sched-core-nr_migrate-128-increases-number-of-tasks-.patch
- add LL-Add-.ll-version.patch
- add loop-Better-discard-for-block-devices.patch
- add Revert-e1000e-fix-cyclic-resets-at-link-up-with-acti.patch
- add e1000e-start-network-tx-queue-only-when-link-is-up.patch
- add scsi-sd-block-Fix-regressions-in-read-only-block-dev.patch
- add scsi-sd-block-Update-fix-regressions-in-read-only-bl.patch
- add ZEN-Add-Thinkpad-SMAPI-driver.patch
- add ZEN-Allow-setting-the-number-of-available-virtual-TT.patch
- add ZEN-Allow-TCP-YeAH-as-default-congestion-control.patch
- add ZEN-Add-VHBA-driver.patch
- add BMQ 0.97
- add AUFS 20190610
- add WireGuard 0.0.20190702

5.1-lucjan-ll31

- add fpga-dfl-fme-mgr-fix-FME_PR_INTFC_ID-register-addres.patch
- add fpga-dfl-fme-remove-copy_to_user-in-ioctl-for-PR.patch
- add fpga-dfl-fme-align-PR-buffer-size-per-PR-datawidth.patch
- add fpga-dfl-fme-support-512bit-data-width-PR.patch
- add fpga-dfl-fme-add-DFL_FPGA_FME_PORT_RELEASE-ASSIGN-io.patch
- add fpga-dfl-pci-enable-SRIOV-support.patch
- add fpga-dfl-afu-add-AFU-state-related-sysfs-interfaces.patch
- add fpga-dfl-afu-add-userclock-sysfs-interfaces.patch
- add fpga-dfl-add-id_table-for-dfl-private-feature-driver.patch
- add fpga-dfl-afu-export-__port_enable-disable-function.patch
- add fpga-dfl-afu-add-error-reporting-support.patch
- add fpga-dfl-afu-add-STP-SignalTap-support.patch
- add fpga-dfl-fme-add-capability-sysfs-interfaces.patch
- add fpga-dfl-fme-add-global-error-reporting-support.patch
- add fpga-dfl-fme-add-thermal-management-support.patch
- add fpga-dfl-fme-add-power-management-support.patch
- add fpga-dfl-fme-add-performance-reporting-support.patch
- add hwmon-Add-convience-macro-to-define-simple-static-se.patch

5.1-lucjan-ll30-rc1 --> 5.1-lucjan-ll30

5.1-lucjan-ll30-rc1

- sync with upstream (drop Bluetooth-Fix-minimum-encryption-key-size-check.patch)

5.1-lucjan-ll29

- add Bluetooth-Fix-minimum-encryption-key-size-check.patch

5.1-lucjan-ll28

- add WireGuard-20190702

5.1-lucjan-ll27

- add aufs-advanced-multi-layered-unification-filesystem-20190610.patch

5.1-lucjan-ll26

- add aufs-advanced-multi-layered-unification-filesystem-20190520.patch

5.1-lucjan-ll25

- update LL-Implement-ll-branding-v5.1.patch

5.1-lucjan-ll24

- add block-bfq-NULL-out-the-bic-when-it-s-no-longer-valid.patch

5.1-lucjan-ll23

- add block-bfq-Init-saved_wr_start_at_switch_to_srt-in-un.patch

5.1-lucjan-ll22

- add Revert-Revert-intel_idle-tweak-cpuidle-cstates.patch

5.1-lucjan-ll21

- add ata-libahci-ignore-staggered-spin-up.patch

5.1-lucjan-ll20

- update LL-Implement-ll-branding-v5.1.patch

5.1-lucjan-ll19

- add block-bfq-reset-inject-limit-when-think-time-state-c.patch
- add block-bfq-fix-rq_in_driver-check-in-bfq_update_injec.patch
- add block-bfq-update-base-request-service-times-when-pos.patch
- add block-bfq-bring-forward-seek-think-time-update.patch
- add block-bfq-detect-wakers-and-unconditionally-inject-t.patch
- add block-bfq-preempt-lower-weight-or-lower-priority-que.patch
- add block-bfq-re-schedule-empty-queues-if-they-deserve-I.patch

5.1-lucjan-ll18

- update LL-Implement-ll-branding-v5.1.patch

5.1-lucjan-ll17

- add LL-Implement-ll-branding-v5.1.patch

5.1-lucjan-ll16

- add block-bfq-fix-operator-in-BFQQ_TOTALLY_SEEKY.patch

5.1-lucjan-ll15

- add ZEN-Add-Thinkpad-SMAPI-driver.patch

5.1-lucjan-ll14

- add ZEN-Allow-setting-the-number-of-available-virtual-TT.patch
- add ZEN-Allow-TCP-YeAH-as-default-congestion-control.patch
- add ZEN-Add-VHBA-driver.patch

5.1-lucjan-ll13

- add CVE-from-clearlinux.patch

5.1-lucjan-ll12

- add andrea-thp-fix.patch (from clearlinux)

5.1-lucjan-ll11-rc1 --> 5.1-lucjan-ll11

5.1-lucjan-ll11-rc1

- sync with upstream (drop bcache-fix-stack-corruption-by-PRECEDING_KEY.patch)

5.1-lucjan-ll10

- add bcache-fix-stack-corruption-by-PRECEDING_KEY.patch

5.1-lucjan-ll9-rc1 --> 5.1-lucjan-ll9

5.1-lucjan-ll9-rc1

- sync with upstream (drop block-bfq-increase-idling-for-weight-raised-queues.patch and mm-compaction.c-fix-an-undefined-behaviour.patch)

5.1-lucjan-ll8

- drop block-bfq-delete-bfq-prefix-from-cgroup-filenames.patch

5.1-lucjan-ll7

- drop bmq-5.1-try-to-fix-lockup.patch
- add bmq-Fix-__ffs-usage-in-bmq_find_first_bit-bmq_find_n.patch

5.1-lucjan-ll6

- add bmq-5.1-try-to-fix-lockup.patch
- add block-bfq-add-weight-symlink-to-the-bfq.weight-cgrou.patch
- add cgroup-let-a-symlink-too-be-created-with-a-cftype-fi.patch

5.1-lucjan-ll5-r1 --> 5.1-lucjan-ll5

5.1-lucjan-ll5-rc1

- sync with upstream (drop mm-compaction-Make-sure-we-isolate-a-valid-PFN.patch)

5.1-lucjan-ll4

- add BMQ 0.96

5.1-lucjan-ll3

- add clearlinux-zen.patch

5.1-lucjan-ll2-r2 --> 5.1-lucjan-ll2

5.1-lucjan-ll2-rc2

- add bmq-5.1-re-introduce-READ-WRITE_ONCE.patch

5.1-lucjan-ll1-rc15 --> 5.1-lucjan-ll2-rc1

5.1-lucjan-ll1-rc14 --> 5.1-lucjan-ll1

5.1-lucjan-ll1-rc15

- sync with upstream (add scsi-block-patches-v5.1.6)

5.1-lucjan-ll1-rc14

- add bmq-5.1-re-sync-against-force-push.patch

5.1-lucjan-ll1-rc13

- add mm-compaction.c-fix-an-undefined-behaviour.patch
- add mm-compaction-Make-sure-we-isolate-a-valid-PFN.patch

5.1-lucjan-ll1-rc12

- drop dm-make-sure-to-obey-max_io_len_target_boundary.patch

5.1-lucjan-ll1-ll11

- add Revert-Revert-dm-eliminate-split_discard_bios-flag-f.patch
- add dm-make-sure-to-obey-max_io_len_target_boundary.patch

5.1-lucjan-ll1-rc10

- add Revert-dm-eliminate-split_discard_bios-flag-from-DM-.patch

5.1-lucjan-ll1-rc9

- add BMQ 0.95

5.1-lucjan-ll1-rc8

- sync with upstream

5.1-lucjan-ll1-rc7

- add ksm-5.1-revert-automerge-feature.patch
- add mm-ksm-introduce-ksm_madvise_merge-helper.patch
- add mm-ksm-introduce-ksm_madvise_unmerge-helper.patch
- add mm-ksm-proc-introduce-remote-merge.patch
- add mm-ksm-proc-add-remote-KSM-documentation.patch

5.1-lucjan-ll1-rc6

- drop blk-throttle-verify-format-of-bandwidth-limit-and-de.patch
- drop blkcg-Prevent-priority-inversion-problem-during-sync.patch
- drop blkcg-Prevent-priority-inversion-problem-during-sync.patch
- drop blk-mq-Use-static_rqs-to-iterate-busy-tags-v2.patch
- drop blk-mq-fix-races-related-with-freeing-queue.patch
- drop blk-mq-Fix-memory-leak-in-error-handling.patch
- drop block-break-loop-when-getting-target-major-number-in.patch
- drop block-Remove-redundant-unlikely-annotation.patch
- drop block-Fix-a-WRITE-SAME-BUG_ON.patch
- drop block-loop-set-GENHD_FL_NO_PART_SCAN-after-blkdev_re.patch
- drop block-Init-flush-rq-ref-count-to-1.patch
- drop block-Code-cleanup-for-bio_find_or_create_slab.patch
- drop block-Don-t-check-if-adjacent-bvecs-in-one-bio-can-b.patch
- drop block-Fix-use-after-free-of-gendisk.patch
- drop block-Add-a-req_bvec-helper.patch
- drop mm-Set-2048-max-kilobytes-to-read-ahead-for-filesyst.patch

5.1-lucjan-ll1-rc5

- add mm-ksm-implement-VM_UNMERGEABLE.patch

5.1-lucjan-ll1-rc4

- drop UKSM
- add mm-ksm-always-merge-anonymous-memory.patch

5.1-lucjan-ll1-rc3

- add Revert-bmq-Sync-c546951d9c93-sched-core-Use-READ_ONC.patch

5.1-lucjan-ll1-rc2

- drop nfp-make-friends-with-O3.patch
- add nfp-bpf-fix-static-check-error-through-tightening-sh.patch

5.1-lucjan-ll1-rc1

- add add-sysctl-to-disallow-unprivileged-CLONE_NEWUSER-by.patch
- add block-bfq-fix-some-typos-in-comments.patch
- add block-bfq-delete-bfq-prefix-from-cgroup-filenames.patch
- add block-Kconfig.iosched-set-default-value-of-IOSCHED_BFQ.patch
- add block-bfq-increase-idling-for-weight-raised-queues.patch
- add bfq-do-not-idle-for-lowest-weight-queues.patch
- add block-bfq-tune-service-injection-basing-on-request-s.patch
- add block-bfq-do-not-merge-queues-on-flash-storage-with-.patch
- add block-bfq-do-not-tag-totally-seeky-queues-as-soft-rt.patch
- add block-bfq-always-protect-newly-created-queues-from-e.patch
- add block-bfq-print-SHARED-instead-of-pid-for-shared-que.patch
- add block-bfq-save-resume-weight-on-a-queue-merge-split.patch
- add doc-block-bfq-add-information-on-bfq-execution-time.patch
- add blk-throttle-verify-format-of-bandwidth-limit-and-de.patch
- add blkcg-Prevent-priority-inversion-problem-during-sync.patch
- add blkcg-Prevent-priority-inversion-problem-during-sync.patch
- add blk-mq-Use-static_rqs-to-iterate-busy-tags-v2.patch
- add blk-mq-fix-races-related-with-freeing-queue.patch
- add blk-mq-Fix-memory-leak-in-error-handling.patch
- add block-break-loop-when-getting-target-major-number-in.patch
- add block-Remove-redundant-unlikely-annotation.patch
- add block-Fix-a-WRITE-SAME-BUG_ON.patch
- add block-loop-set-GENHD_FL_NO_PART_SCAN-after-blkdev_re.patch
- add block-Init-flush-rq-ref-count-to-1.patch
- add block-Code-cleanup-for-bio_find_or_create_slab.patch
- add block-Don-t-check-if-adjacent-bvecs-in-one-bio-can-b.patch
- add block-Fix-use-after-free-of-gendisk.patch
- add block-Add-a-req_bvec-helper.patch
- add block-Skip-media-change-event-handling-if-unsupporte.patch
- add cpu-5.1-merge-graysky-s-patchset.patch
- add cpu-5.1-add-a-CONFIG-option-that-sets-O3.patch
- add nfp-make-friends-with-O3.patch
- add BMQ 0.94
- add io_uring-fix-shadowed-variable-ret-return-code-being.patch
- add io_uring-restructure-io_-read-write-control-flow.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-o.patch
- add LL-elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add mm-Set-2048-max-kilobytes-to-read-ahead-for-filesyst.patch
- add sched-core-nr_migrate-128-increases-number-of-tasks-.patch
- add LL-Add-.ll-version.patch
- add loop-Better-discard-for-block-devices.patch
- add Revert-e1000e-fix-cyclic-resets-at-link-up-with-acti.patch
- add e1000e-start-network-tx-queue-only-when-link-is-up.patch
- add scsi-sd-block-Fix-regressions-in-read-only-block-dev.patch
- add scsi-sd-block-Update-fix-regressions-in-read-only-bl.patch
- add uksm-5.1-initial-submission.patch
- add uksm-5.1-apply-52d1e606ee733.patch
- add ZEN-Add-CONFIG-for-unprivileged_userns_clone.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch

5.0-lucjan-ll38-rc1

- sync with upstream (add scsi-block-patches-v5.0.20)

5.0-lucjan-ll37-rc1 --> 5.0-lucjan-ll37

5.0-lucjan-ll37-rc1

- sync with upstream

5.0-lucjan-ll36

- add add BMQ 0.93 v5.0.7+

5.0-lucjan-ll35-rc1 --> 5.0-lucjan-ll35

5.0-lucjan-ll35-rc1

- sync with upstream

5.0-lucjan-ll34-rc1 --> 5.0-lucjan-ll34

5.0-lucjan-ll34-rc1

- sync with upstream (drop udp-fix-GRO-reception-in-case-of-length-mismatch.patch, drop udp-fix-GRO-packet-of-death.patch)

5.0-lucjan-ll33

- add udp-fix-GRO-reception-in-case-of-length-mismatch.patch
- add udp-fix-GRO-packet-of-death.patch

5.0-lucjan-ll32-rc2 --> 5.0-lucjan-ll32

5.0-lucjan-ll32-rc2

- add BMQ 0.93

5.0-lucjan-ll32-rc1

- sync with upstream (drop block-bfq-fix-use-after-free-in-bfq_bfqq_expire.patch, drop block-loop-Do-not-print-warn-message-if-partition-sc.patch, resync block-bfq-fix-some-typos-in-comments.patch)

5.0-lucjan-ll31

- add block-Kconf-iosched-set-default-value-of-IOSCHED_BFQ.patch

5.0-lucjan-ll30-rc1 --> 5.0-lucjan-ll30

5.0-lucjan-ll30-rc1

- add UKSM-for-5.0.10.patch

5.0-lucjan-ll29

- add blk-mq-Fix-memory-leak-in-error-handling.patch

5.0-lucjan-ll28-rc1 --> 5.0-lucjan-ll28

5.0-lucjan-ll28-rc1

- sync with upstream (drop blk-iolatency-include-blk.h.patch)

5.0-lucjan-ll27

- add e1000e-start-network-tx-queue-only-when-link-is-up.patch

5.0-lucjan-ll26-rc1 --> 5.0-lucjan-ll26

5.0-lucjan-ll26-rc1

- sync with upstream

5.0-lucjan-ll25

- add bmq-Fix-yield.patch

5.0-lucjan-ll24

- add block-bfq-fix-some-typos-in-comments.patch
- fix block-bfq-fix-use-after-free-in-bfq_bfqq_expire.patch

5.0-lucjan-ll23

- add BMQ 0.92
- add block-bfq-fix-use-after-free-in-bfq_bfqq_expire.patch

5.0-lucjan-ll22

- add block-bfq-delete-bfq-prefix-from-cgroup-filenames.patch

5.0-lucjan-ll21-rc2 ---> 5.0-lucjan-ll21

5.0-lucjan-ll21-rc2

- add block-bfq-fix-ifdef-for-CONFIG_BFQ_GROUP_IOSCHED-y.patch

5.0-lucjan-ll21-rc1

- sync with upstream (drop block-bfq-fix-queue-removal-from-weights-tree.patch, block-bfq-fix-in-service-queue-check-for-queue-mergi.patch and block-loop-set-GENHD_FL_NO_PART_SCAN-after-blkdev_re.patch)

5.0-lucjan-ll20-rc2 ---> 5.0-lucjan-ll20

5.0-lucjan-ll20-rc2

- sync with upstream (drop blk-mq-Fix-sbitmap-ws_active-for-shared-tags.patch)

5.0-lucjan-ll20-rc1

- sync witn upstream (drop netfilter-nf_tables-fix-set-double-free-in-abort-pat.patch)

5.0-lucjan-ll19

- add blk-mq-Use-static_rqs-to-iterate-busy-tags-v2.patch
- add blk-mq-Fix-sbitmap-ws_active-for-shared-tags.patch
- add blk-mq-Add-trace-block-plug-and-unplug-for-multiple-.patch

5.0-lucjan-ll18

- add bmq-Fix-obviously-wrong-branch-statement-in-do_sched.patch

5.0-lucjan-ll17

- add blk-mq-Cleaup-code-and-update-comment.patch

5.0-lucjan-ll16

- add BMQ 0.91

5.0-lucjan-ll15

- add blkcg-Prevent-priority-inversion-problem-during-sync.patch
- add blkcg-Prevent-priority-inversion-problem-during-sync-update.patch

5.0-lucjan-ll14

- add blk-mq-Rmove-unused-nr_expired-from-blk_mq_hw_ctx.patch
- add blkcg-Fix-kernel-doc-warnings.patch
- add blk-iolatency-include-blk.h.patch
- add block-Unexport-blk_mq_add_to_requeue_list.patch

5.0-lucjan-ll13

- add mm-set-128-2048-min-max-kilobytes-to-read-ahead-for-.patch
- add sched-core-nr_migrate-128-increases-number-of-tasks-.patch

5.0-lucjan-ll12

- add block-Add-BLK_MQ_POLL_CLASSIC-for-hybrid-poll-and-re.patch
- add block-Fix-use-after-free-of-gendisk.patch

5.0-lucjan-ll11

- add bmq-Fix-BMQ-compile-fails-for-x86-UP-again.patch

5.0-lucjan-ll10

- blk-mq-nvme-Cancel-request-synchronously.patch

5.0-lucjan-ll9

- add BMQ 0.90

5.0-lucjan-ll8

- add blk-mq-Use-blk_mq_sched_mark_restart_hctx-to-set-RES.patch
- add block-Update-v3-Add-a-new-flag-BLK_MQ_POLL_CLASSIC-f.patch

5.0-lucjan-ll7

- add Makefile-Add-fno-builtin-bcmp-to-CLANG_FLAGS.patch

5.0-lucjan-ll6

- add netfilter-nf_tables-fix-set-double-free-in-abort-pat.patch

5.0-lucjan-ll5

- add fixes-5.0-merge-BFQ-improvements-v3

5.0-lucjan-ll4

- morf PDS-mq into BMQ

5.0-lucjan-ll3

- add lock-bfq-Fix-bugs-reduce-exec-time-and-boost-perform.patch

5.0-lucjan-ll2

- add block-Init-flush-rq-ref-count-to-1.patch
- add block-Code-cleanup-for-bio_find_or_create_slab.patch

5.0-lucjan-ll1

- add bfq-blk-mq-Fix-system-freeze-with-high-nr_requests.patch
- add block-break-loop-when-getting-target-major-number-in.patch
- add block-Refactor-register_blkdev-to-compare-major-numb.patch
- add block-Remove-redundant-unlikely-annotation.patch
- add block-Set-rq_affinity-2-for-full-multithreading-I-O-.patch
- add block-Fix-a-WRITE-SAME-BUG_ON.patch
- add block-Fix-NULL-pointer-dereference-in-register_disk.patch
- add block-loop-Do-not-print-warn-message-if-partition-sc.patch
- add block-loop-set-GENHD_FL_NO_PART_SCAN-after-blkdev_re.patch
- add blk-throttle-verify-format-of-bandwidth-limit-and-de.patch
- add block-add-a-new-flag-BLK_MQ_POLL_CLASSIC-for-hybrid-.patch
- add gcctunes-5.0-merge-graysky-s-patchset.patch
- add v5.0_pds099o.patch
- add pds-Fix-compilation-issue-with-CONFIG_ENERGY_MODEL.patch
- add pds-update_task_priodl-for-all-task-when-timeslice-e.patch
- add bfq-update-internal-depth-state-when-queue-depth-cha.patch
- add block-bfq-do-not-consider-interactive-queues-in-srt-.patch
- add block-bfq-avoid-selecting-a-queue-w-o-budget.patch
- add block-bfq-make-sure-queue-budgets-are-not-below-serv.patch
- add block-bfq-remove-case-of-redirected-bic-from-insert_.patch
- add block-bfq-consider-also-ioprio-classes-in-symmetry-d.patch
- add block-bfq-split-function-bfq_better_to_idle.patch
- add block-bfq-do-not-plug-I-O-of-in-service-queue-when-h.patch
- add block-bfq-unconditionally-plug-I-O-in-asymmetric-sce.patch
- add block-bfq-fix-sequential-rq-detection-in-rate-estima.patch
- add block-bfq-fix-queue-removal-from-weights-tree.patch
- add block-bfq-reduce-threshold-for-detecting-command-que.patch
- add block-bfq-port-commit-cfq-iosched-improve-hw_tag-det.patch
- add block-bfq-do-not-overcharge-writes-in-asymmetric-sce.patch
- add block-bfq-fix-in-service-queue-check-for-queue-mergi.patch
- add block-bfq-increase-idling-for-weight-raised-queues.patch
- add block-bfq-do-not-idle-for-lowest-weight-queues.patch
- add block-bfq-tune-service-injection-basing-on-request-s.patch
- add block-bfq-do-not-merge-queues-on-flash-storage-with-.patch
- add block-bfq-do-not-tag-totally-seeky-queues-as-soft-rt.patch
- add block-bfq-always-protect-newly-created-queues-from-e.patch
- add block-bfq-print-SHARED-instead-of-pid-for-shared-que.patch
- add block-bfq-save-resume-weight-on-a-queue-merge-split.patch
- add bfq-Avoid-double-definition-of-bfq_pid_to_str.patch
- add doc-block-bfq-add-information-on-bfq-execution-time.patch
- add fixes-5.0-merge-BFQ-improvements-v2.patch
- add add-sysctl-to-disallow-unprivileged-CLONE_NEWUSER-by.patch
- add uksm-5.0-initial-submission.patch
- add uksm-5.0-adopt-new-MMU-notifiers-API.patch
- add scsi-sd-block-Fix-regressions-in-read-only-block-dev.patch
- add scsi-sd-block-Update-fix-regressions-in-read-only-bl.patch
- add ZEN-Add-a-CONFIG-option-that-sets-O3.patch
- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch
- add add-sysctl-to-disallow-unprivileged-CLONE_NEWUSER-by.patch
- add ZEN-Add-CONFIG-for-unprivileged_userns_clone.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-option.patch
- add LL-elevator-set-default-scheduler-to-bfq-for-blk-mq.patch
- add LL-Add-.ll-version.patch

4.20-lucjan-ll46-rc1 ---> 4.20-lucjan-ll46

4.20-lucjan-ll46-rc1

- sync with upstream

4.20-lucjan-ll45

- add 4.20-bfq-sq-mq-v10r1-2K190304-rc2.patch

4.20-lucjan-ll44

- add 4.20-bfq-sq-mq-v10r1-2K190304-rc1.patch

4.20-lucjan-ll43

- add 4.20-bfq-sq-mq-v10r1-2K190304-rc1.patch

4.20-lucjan-ll42

- add 4.20-bfq-sq-mq-v10r1-2K190303-rc1.patch

4.20-lucjan-ll41

- add 4.20-bfq-sq-mq-v9r1-2K190302-rc1.patch

4.20-lucjan-ll40

- add PDS-mq 0.99n

4.20-lucjan-ll39

- add 0001-block-add-a-new-flag-BLK_MQ_POLL_CLASSIC-for-hybrid-.patch

4.20-lucjan-ll38

- add blk-throttle-verify-format-of-bandwidth-limit-and-de.patch

4.20-lucjan-ll37

- add 4.20-bfq-sq-mq-v9r1-2K190228-rc1.patch

4.20-lucjan-ll36

- add scsi-sd-block-Fix-regressions-in-read-only-block-dev.patch
- add scsi-sd-block-Update-fix-regressions-in-read-only-block-dev.patch

4.20-lucjan-ll35

- add x86-CPU-Add-Icelake-model-number.patch

4.20-lucjan-ll34-rc1 ---> 4.20-lucjan-ll34

4.20-lucjan-ll34-rc1

- drop net-crypto-set-sk-to-NULL-when-af_alg_release.patch (sync with upstream)

4.20-lucjan-ll33

- add net-crypto-set-sk-to-NULL-when-af_alg_release.patch
- add exec-Fix-mem-leak-in-kernel_read_file.patch

4.20-lucjan-ll32

- add pds-Fix-hrtick_start-too-short-for-new-tasks.patch

4.20-lucjan-ll31

- add block-Fix-NULL-pointer-dereference-in-register_disk.patch

4.20-lucjan-ll30

- add block-Fix-a-WRITE-SAME-BUG_ON.patch

4.20-lucjan-ll29-rc1 ---> 4.20-lucjan-ll29

4.20-lucjan-ll29-rc1

- sync with upstream (drop blk-mq-fix-a-hung-issue-when-fsync.patch)

4.20-lucjan-ll28

- add PDS-mq 0.99m
- drop x86-kvm-Fix-sched_smt_present-undefined.patch

4.20-lucjan-ll27

- add block-break-loop-when-getting-target-major-number-in.patch
- add block-Refactor-register_blkdev-to-compare-major-numb.patch
- add block-Remove-redundant-unlikely-annotation.patch

4.20-lucjan-ll26-rc2 ---> 4.20-lucjan-ll26

4.20-lucjan-ll26-rc2

- add x86-kvm-Fix-sched_smt_present-undefined.patch

4.20-lucjan-ll26-rc1

- sync with upstream (drop memstick-Prevent-memstick-host-from-getting-runtime-.patch)

4.20-lucjan-ll25

- add blk-mq-fix-a-hung-issue-when-fsync.patch
- add block-v2-0-3-iolatency-bug-fix.patch
- add blk-Optimization-for-classic-polling.patch

4.20-lucjan-ll24

- add 4.20-bfq-sq-mq-v9r1-2K190204-rc1.patch

4.20-lucjan-ll23

- drop blkcg-fix-ref-count-issue-with-bio_blkcg-using-task_.patch
- drop block-doc-add-slice_idle_us-to-bfq-documentation.patch

4.20-lucjan-ll22

- add blkcg-fix-ref-count-issue-with-bio_blkcg-using-task_.patch
- add block-doc-add-slice_idle_us-to-bfq-documentation.patch
- add block-bfq-remove-case-of-redirected-bic-from-insert_.patch
- add block-bfq-consider-also-ioprio-classes-in-symmetry-d.patch
- add block-bfq-split-function-bfq_better_to_idle.patch
- add block-bfq-do-not-plug-I-O-of-in-service-queue-when-h.patch
- add block-bfq-unconditionally-plug-I-O-in-asymmetric-sce.patch
- add block-bfq-fix-sequential-rq-detection-in-rate-estima.patch
- add block-bfq-fix-queue-removal-from-weights-tree.patch
- add block-bfq-reduce-threshold-for-detecting-command-que.patch
- add block-bfq-port-commit-cfq-iosched-improve-hw_tag-det.patch
- add block-bfq-do-not-overcharge-writes-in-asymmetric-sce.patch
- add block-bfq-fix-in-service-queue-check-for-queue-mergi.patch

4.20-lucjan-ll21

- add 4.20-bfq-sq-mq-v9r1-2K190128-rc1.patch (includes bfq-Increase-BLKCG_MAX_POLS.patch)

4.20-lucjan-ll20

- add 4.20-bfq-sq-mq-v9r1-2K190125-rc1.patch

4.20-lucjan-ll19

- add 4.20-bfq-sq-mq-v9r1-2K190124-rc1.patch

4.20-lucjan-ll18

- add bfq-do-not-consider-interactive-queues-in-srt-filter.patch
- add bfq-avoid-selecting-a-queue-w-o-budget.patch
- add bfq-make-sure-queue-budgets-are-not-below-service-re.patch

4.20-lucjan-ll17

- add 4.20-bfq-sq-mq-v9r1-2K190121-rc1.patch

4.20-lucjan-ll16

- add PDS-mq 0.99l
- add blk-mq-fix-updating-internal-depth-state-for-4.20-se.patch

4.20-lucjan-ll15

- add bfq-update-internal-depth-state-when-queue-depth-cha.patch

4.20-lucjan-ll14-rc2

- add forgotten patch (Check-presence-on-tree-of-every-entity-after-every-a.patch)

4.20-lucjan-ll14-rc1

- switch to diff --git

4.20-lucjan-ll13

- add LL-elevator-set-default-scheduler-to-bfq-mq-for-blk-mq.patch

4.20-lucjan-l12

- add infiniband-Fix-__read_overflow2-error-with-O3-inlini.patch

4.20-lucjan-ll11

- add 4.20-bfq-sq-mq-v9r1-2K190111-rc1.patch

4.20-lucjan-ll10

- add PDS-mq 0.99k

4.20-lucjan-ll9

- add 4.20-bfq-sq-mq-v9r1-2K190108-rc1.patch

4.20-lucjan-ll8

- add ZEN-scsi-Always-use-the-blk-mq-I-O-path.patch
- add LL-scsi-Always-use-the-blk-mq-I-O-path.patch
- drop add-ll-version.patch
- add LL-Add-.ll-version.patch

4.20-lucjan-ll7

- add LL-block-Kconf-iosched-fix-depends-for-BLK-CGROUPS-IOLATENCY

4.20-lucjan-ll6

- add ZEN-Add-a-CONFIG-option-that-sets-O3.patch
- add ZEN-Add-CONFIG-for-unprivileged_userns_clone.patch

4.20-lucjan-ll5

- add block-Set-rq_affinity-2-for-full-multithreading-I-O-.patch

4.20-lucjan-ll4

- add PDS-mq 0.99j

4.20-lucjan-ll3

- add block-Kconf-iosched-fix-depends-for-BLK-CGROUP-IOLATENCY.patch

4.20-lucjan-ll2

- add block-Fix-enables-BFQ-MQ-multi-queue-IO-scheduling-by-default.patch
- add LL-kconfig-add-750Hz-timer-interrupt-kernel-config-option.patch

4.20-lucjan-ll1-rc2 --> 4.20-lucjan-ll1

4.20-lucjan-ll1-rc2

- uksm from dolohow's github

4.20-lucjan-ll1-rc1

- sync with upstream
- add PDS-mq 0.99i
- add pds-Fix-missing-mainline-scheduler-API-for-psi.patch

4.19-lucjan-ll19

- add PDS-mq 0.99h
- add pds-Fix-NORMAL_PRIO-mess-up-with-ISO_PRIO.patch

4.19-lucjan-ll18

- add memstick-rtsx_usb_ms-Add-missing-pm_runtime_disable-.patch
- add misc-rtsx_usb-Use-USB-remote-wakeup-signaling-for-ca.patch
- add memstick-Prevent-memstick-host-from-getting-runtime-.patch
- add memstick-rtsx_usb_ms-Use-ms_dev-helper.patch
- add memstick-rtsx_usb_ms-Support-runtime-power-managemen.patch
- add pds-Fix-cpu-hot-plug-Oops.patch

4.19-lucjan-ll17-rc1 --> 4.19-lucjan-ll17

4.19-lucjan-ll17-rc1

- sync with upstream

4.19-lucjan-ll16

- drop uksm-4.19.9-rc.patch
- improve x86_64_defconfig-add-I-O-schedulers.patch (---> 4.19-bfq-sq-mq-v9r1-2K181212-rc1.patch)
- add bfq-Increase-BLKCG_MAX_POLS.patch

4.19-lucjan-ll15-rc2

- add uksm-4.19.9-rc.patch
- add PDS-mq 0.99g

4.19-lucjan-ll14

- add PDS-mq 0.99g

4.19-lucjan-ll14-rc1 --> 4.19-lucjan-ll15-rc1

4.19-lucjan-ll14-rc1

- add uksm-4.19.9-rc.patch

4.19-lucjan-ll13

- sync with upstream
- add pds-Fix-smt-boot-up-crash.patch

4.19-lucjan-ll12-rc4

- add blk-mq-punt-failed-direct-issue-to-dispatch-list.patch

4.19-lucjan-ll12-rc3

- add block-bfq-fix-decrement-of-num_active_groups.patch

- add block-bfq-fix-comments-on-__bfq_deactivate_entity.patch

4.19-lucjan-ll12-rc2

- add add 4.19-bfq-sq-mq-v9r1-2K181206-rc2.patch

4.19-lucjan-ll12-rc1

- sync with upstream

4.19-lucjan-ll11

- add pds-Sync-c5511d03ec09-sched-smt-Make-sched_smt_prese.patch

4.19-lucjan-ll10

- add 4.19-bfq-sq-mq-v9r1-2K181206-rc1.patch

4.19-lucjan-ll9

- add blk-mq-fix-corruption-with-direct-issue.patch
- x86_64_defconfig-add-I-O-schedulers.patch

4.19-lucjan-ll8

- add block-bfq-mq-fix-num_active_groups-update.patch

4.19-lucjan-ll7

- add PDS-mq 0.99f

4.19-lucjan-ll6

- add PDS-mq 0.99e

4.19-lucjan-ll5

- improve add-ll-version.patch

4.19-lucjan-ll4-rc3 ---> 4.19-lucjan-ll4

4.19-lucjan-ll4-rc3

- improve add-ll-version.patch

4.19-lucjan-ll4-rc2

- add PDS-mq 0.99d

4.19-lucjan-ll4-rc1

- drop block-bfq-correctly-charge-and-reset-entity-service-.patch (sync with upstream)

4.19-lucjan-ll3

- add add-ll-version.patch

4.19-lucjan-ll2

- add memstick-rtsx_usb_ms-Add-missing-pm_runtime_disable-.patch
- add misc-rtsx_usb-Use-USB-remote-wakeup-signaling-for-ca.patch
- add memstick-Prevent-memstick-host-from-getting-runtime-.patch
- add memstick-rtsx_usb_ms-Use-ms_dev-helper.patch
- add memstick-rtsx_usb_ms-Support-runtime-power-managemen.patch

4.19-lucjan-ll1

- sync with 4.19 line
- add 4.19-bfq-sq-mq-v9r1-2K181101-rc1.patch
- add PDS-mq 0.99c
- add block-bfq-correctly-charge-and-reset-entity-service-.patch
- add block-bfq-inject-other-queue-I-O-into-seeky-idle-que.patch
- add block-bfq-do-not-plug-I-O-if-all-queues-are-weight-r.patch
- add block-bfq-improve-asymmetric-scenarios-detection.patch
- add block-bfq-fix-asymmetric-scenarios-detection.patch
- add misc-rtsx_usb-Use-USB-remote-wakeup-signaling-for-ca.patch
- add memstick-Prevent-memstick-host-from-getting-runtime-.patch
- add memstick-rtsx_usb_ms-Use-ms_dev-helper.patch
- add memstick-rtsx_usb_ms-Support-runtime-power-managemen.patch
- add net-Add-and-use-skb_mark_not_on_list.patch
- add net-Add-and-use-skb_list_del_init.patch
- add net-Use-skb_list_del_init-for-gro_flush_oldest-too.patch
- add uksm-v4.19

4.18-lucjan-ll31

- add 4.18-bfq-sq-mq-v9r1-2K181101.patch

4.18-lucjan-ll30

- revert: update graysky's patch

4.18-lucjan-ll29

- update graysky's patch

4.18-lucjan-ll28

- add 4.18-bfq-sq-mq-v9r1-2K181024.patch
- add block-bfq-fix-asymmetric-scenarios-detection.patch

4.18-lucjan-ll27

- add block-bfq-improve-asymmetric-scenarios-detection.patch

4.18-lucjan-ll26

- add 4.18-bfq-sq-mq-v9r1-2K181012.patch

4.18-lucjan-ll25

- add 4.18-bfq-sq-mq-v9r1-2K181011.patch

4.18-lucjan-ll24

- add qxl-fix-null-pointer-crash-during-suspend.patch

4.18-lucjan-ll23

- add PDS-mq 0.99a

4.18-lucjan-ll22-rc1

- drop blk-mq-avoid-to-synchronize-rcu-inside-blk_cleanup_q.patch (sync with upstream)

4.18-lucjan-ll21-rc3 -> 4.18-lucjan-ll21

4.18-lucjan-ll21-rc3

- add pds-Fix-sugov_kthread_create-fail-to-set-policy.patch

4.18-lucjan-ll21-rc2

- add PDS-mq 0.98z

4.18-lucjan-ll21-rc1

- drop HID-core-fix-grouping-by-application.patch (sync with upstream)

- drop block-bfq-swap-puts-in-bfqg_and_blkg_put.patch (sync with upstream)

4.18-lucjan-ll20

- add 4.18-bfq-sq-mq-v9r1-2K180915.patch

4.18-lucjan-ll19-rc7

- add block-bfq-correctly-charge-and-reset-entity-service-.patch
- add block-bfq-inject-other-queue-I-O-into-seeky-idle-que.patch
- add block-bfq-do-not-plug-I-O-if-all-queues-are-weight-r.patch

4.18-lucjan-ll19-rc6

- add 4.18-bfq-sq-mq-v8r12-2K180913.patch, sync with upstream

4.18-lucjan-ll18

- add 4.18-bfq-sq-mq-v8r12-2K180913.patch

4.18-lucjan-ll18-rc* -> 4.18-lucjan-ll19-rc*

4.18-lucjan-ll18-rc5

- sync with upstream - drop drm-i915-Increase-LSPCON-timeout.patch

4.18-lucjan-ll18-rc4

- revert 4.18-lucjan-ll18-rc2

4.18-lucjan-ll18-rc3

- sync with upstream

4.18-lucjan-ll18-rc2

- drop blk-mq patches

4.18-lucjan-ll18-rc1

- sync with upstream

4.18-lucjan-ll17

- rebase uksm patch

4.18-lucjan-ll16-rc1 ---> 4.18-lucjan-ll16

4.18-lucjan-ll16-rc1

- sync with upstream - drop block-bfq-return-nbytes-and-not-zero-from-struct-cft.patch

4.18-lucjan-ll15

- add 4.18-bfq-sq-mq-v8r12-2K180906.patch

4.18-lucjan-ll14

- add block-bfq-swap-puts-in-bfqg_and_blkg_put.patch

4.18-lucjan-ll13

- add HID-core-fix-grouping-by-application.patch

4.18-lucjan-ll12

- add PDS-mq 0.98y

4.18-lucjan-ll11

- add PDS-mq 0.98x

4.18-lucjan-ll10

- add v4.18_pds098w_revert_data_structure_v2.patch

4.18-lucjan-ll9

- add v4.18_pds098w_revert_data_structure.patch

4.18-lucjan-ll8

- add 4.18-bfq-sq-mq-v8r12-2K180824.patch

4.18-lucjan-ll7

- add PDS-mq 0.98w

4.18-lucjan-ll6-rc2 ---> 4.18-lucjan-ll6

- stable branch

4.18-lucjan-ll6-rc2

- add drm/i915: Increase LSPCON timeout from Arch Linux

4.18-lucjan-ll6-rc1

- add pds-4.18-enable-CGROUP_SCHED.patch

4.18-lucjan-ll5

- rebase uksm patch

4.18-lucjan-ll4

- add 4.18-bfq-sq-mq-v8r12-2K180817.patch

4.18-lucjan-ll3

- add PDS-mq 0.98v

4.18-lucjan-ll2

- add block-bfq-readd-missing-reset-of-parent-entity-servi.patch
- add block-bfq-always-update-the-budget-of-an-entity-when.patch
- add block-bfq-reduce-write-overcharge.patch
- add block-bfq-improve-code-of-bfq_bfqq_charge_time.patch
- add block-bfq-return-nbytes-and-not-zero-from-struct-cft.patch

4.18-lucjan-ll1

- rebase against 4.18

4.17-lucjan-ll12

- add blk-mq-cleanup-blk_mq_get_driver_tag.patch
- add blk-mq-don-t-pass-hctx-to-blk_mq_mark_tag_wait.patch
- add blk-mq-introduce-new-lock-for-protecting-hctx-dispat.patch
- add blk-mq-reinit-q-tag_set_list-entry-only-after-grace-.patch
- add blk-mq-remove-synchronize_rcu-from-blk_mq_del_queue_.patch
- add blk-mq-avoid-to-synchronize-rcu-inside-blk_cleanup_q.patch

4.17-lucjan-ll11

- add v4.17.12+_pds098s.patch

4.17-lucjan-ll10

- add misc-rtsx_usb-Use-USB-remote-wakeup-signaling-for-ca.patch
- add memstick-Prevent-memstick-host-from-getting-runtime-.patch
- add memstick-rtsx_usb_ms-Use-ms_dev-helper.patch
- add memstick-rtsx_usb_ms-Support-runtime-power-managemen.patch
- add misc-rtsx_usb-memstick-rtsx_usb_ms-Avoid-long-delay-.patch


4.17-lucjan-ll9

- add ACPICA-AML-Parser-ignore-control-method-status-in-mo.patch

