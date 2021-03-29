## CHANGELOG

#### Starting from version 5.8-lucjan-ll19 it is necessary to use a PDS scheduler.
#### You must have GCC 11 to take advantages of the MZEN3/MSAPPHIRERAPIDS/MALDERLAKE/GENERIC_CPU2/GENERIC_CPU3/GENERIC_CPU4 optimizations. 
#### Otherwise the kernel will not compile properly.

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

